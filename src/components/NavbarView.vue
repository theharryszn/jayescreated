<script setup lang="ts">
import { gsap } from 'gsap'
import { onBeforeRouteLeave } from 'vue-router'

const openMenu = () => {
  gsap.to('#mobile-menu', {
    translateX: 0,
    duration: 0.5,
    ease: 'easeIn'
  })
}

const closeMenu = () => {
  gsap.to('#mobile-menu', {
    translateX: window.innerWidth,
    ease: 'easeIn'
  })
}

onBeforeRouteLeave(() => {
  closeMenu()
})
</script>
<template>
  <nav
    data-scroll-fixed
    class="px-5 md:px-10 py-6 flex items-center gap-5 justify-between text-sm absolute left-0 top-0 w-full"
  >
    <RouterLink to="/" class="">jayescreated</RouterLink>
    <div class="items-center gap-10 hidden md:flex">
      <RouterLink to="/resume" class="bg-white p-3 rounded-full px-6 cursor-pointer link-pill"
        >Resume</RouterLink
      >
      <RouterLink to="/about" class="bg-white p-3 rounded-full px-6 cursor-pointer link-pill"
        >About</RouterLink
      >
      <RouterLink to="/blog" class="bg-white p-3 rounded-full px-6 cursor-pointer link-pill"
        >Blog</RouterLink
      >
    </div>
    <div class="flex md:hidden" @click="openMenu">MENU</div>
  </nav>
  <div
    id="mobile-menu"
    class="fixed z-[99] dark:bg-zinc-950 bg-zinc-50 p-10 gap-10 flex md:hidden flex-col w-screen h-screen transform translate-x-[100vh]"
  >
    <div class="flex" @click="closeMenu">CLOSE</div>
    <RouterLink to="/" class="text-3xl">Home</RouterLink>
    <RouterLink to="/works" class="text-3xl">Works</RouterLink>
    <RouterLink to="/resume" class="text-3xl">Resume</RouterLink>
  </div>
</template>
