<script lang="ts" setup>
import NavbarView from '@/components/NavbarView.vue'
import FooterView from '@/components/FooterView.vue'
import headerBg from '@/assets/images/Header Background 1.png'
import pouchWebsite from '@/assets/images/Pouch mockup.jpg'
import pouchApp from '@/assets/images/poch mobile.jpg'
import beatfro from '@/assets/images/Beatfrom waitlist mockup.jpg'
import foodie from '@/assets/images/foodiee mockup.jpg'
</script>
<template>
  <header
    data-scroll-section
    class="h-screen px-10 md:p-40 flex flex-col justify-center gap-10 header relative"
  >
    <NavbarView />
    <img
      :src="headerBg"
      alt=""
      class="absolute top-0 h-full w-full object-cover left-0 z-[-1] opacity-50"
    />
    <div class="font-bold text-5xl">
      Hello, <br />
      I'm Jason.
    </div>
    <div class="font-medium text-2xl">I am proficient in designing apps and websites.</div>
    <div class="text-[#595959]">
      I'm a highly efficient web and app designer specializing in various interface designs. I
      prioritize speed without compromising quality and take pride in my work. Currently seeking
      freelance opportunities.
    </div>
    <div class="flex gap-2 md:gap-5 flex-wrap">
      <a
        href="https://twitter.com/jayescreated"
        target="_blank"
        rel="noopener noreferrer"
        class="bg-[#EFEFF1] p-2 rounded-xl text-sm px-6 flex gap-2 items-center"
      >
        <span>Twitter</span>
        <span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="18"
            height="18"
            fill="#413535"
            viewBox="0 0 256 256"
          >
            <path
              d="M200,64V168a8,8,0,0,1-16,0V83.31L69.66,197.66a8,8,0,0,1-11.32-11.32L172.69,72H88a8,8,0,0,1,0-16H192A8,8,0,0,1,200,64Z"
            ></path>
          </svg>
        </span>
      </a>
      <a
        href="https://dribbble.com/jayeshumbe"
        target="_blank"
        rel="noopener noreferrer"
        class="bg-[#EFEFF1] p-2 rounded-xl text-sm px-6 flex gap-2 items-center"
      >
        <span>Dribbble</span>
        <span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="18"
            height="18"
            fill="#413535"
            viewBox="0 0 256 256"
          >
            <path
              d="M200,64V168a8,8,0,0,1-16,0V83.31L69.66,197.66a8,8,0,0,1-11.32-11.32L172.69,72H88a8,8,0,0,1,0-16H192A8,8,0,0,1,200,64Z"
            ></path>
          </svg>
        </span>
      </a>
      <a
        href="mailto:jayeshumbe@gmail.com"
        target="_blank"
        rel="noopener noreferrer"
        class="bg-[#EFEFF1] p-2 rounded-xl text-sm px-6 flex gap-2 items-center"
      >
        <span>Email</span>
        <span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="18"
            height="18"
            fill="#413535"
            viewBox="0 0 256 256"
          >
            <path
              d="M200,64V168a8,8,0,0,1-16,0V83.31L69.66,197.66a8,8,0,0,1-11.32-11.32L172.69,72H88a8,8,0,0,1,0-16H192A8,8,0,0,1,200,64Z"
            ></path>
          </svg>
        </span>
      </a>
    </div>
  </header>
  <main data-scroll-section>
    <div class="px-10 md:px-40 flex flex-col gap-16 pb-40 pt-24">
      <div class="flex flex-col gap-2">
        <h3 class="text-3xl font-medium">Featured Projects</h3>
        <p class="text-[#595959]">
          Here are some of the projects i've worked on personally and professionally
        </p>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-10 gap-y-20">
        <div class="flex flex-col gap-4">
          <img :src="foodie" class="aspect-[148/105] bg-[#EFEFF1] object-cover rounded-2xl" />
          <div class="flex flex-col gap-2">
            <div class="text-2xl font-medium">chopBeta</div>
            <p class="text-[#595959]">
              Here are some of the projects I've worked on personally and professionally
            </p>
          </div>
        </div>
        <div class="flex flex-col gap-4">
          <img :src="beatfro" class="aspect-[148/105] bg-[#EFEFF1] object-cover rounded-2xl" />
          <div class="flex flex-col gap-2">
            <div class="text-2xl font-medium">Beatfro waitlist</div>
            <p class="text-[#595959]">
              Here are some of the projects I've worked on personally and professionally
            </p>
          </div>
        </div>
        <div class="flex flex-col gap-4">
          <img :src="pouchWebsite" class="aspect-[148/105] bg-[#EFEFF1] object-cover rounded-2xl" />
          <div class="flex flex-col gap-2">
            <div class="text-2xl font-medium">Pouch website</div>
            <p class="text-[#595959]">
              Here are some of the projects I've worked on personally and professionally
            </p>
          </div>
        </div>
        <div class="flex flex-col gap-4">
          <img :src="pouchApp" class="aspect-[148/105] bg-[#EFEFF1] object-cover rounded-2xl" />
          <div class="flex flex-col gap-2">
            <div class="text-2xl font-medium">Pouch USDT savings app</div>
            <p class="text-[#595959]">
              Here are some of the projects I've worked on personally and professionally
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="px-10 md:px-40 flex flex-col gap-16 pb-40">
      <div class="flex flex-col gap-2">
        <h3 class="text-3xl font-medium">My Spotify</h3>
        <p class="text-[#595959]">
          I'm a music enthusiast and a huge fan of Spotify. It's one of my top, if not the
          most-used, apps 😎. I'd love to share some of my favorite playlists with you.
        </p>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-10 gap-y-20">
        <iframe
          style="border-radius: 12px"
          src="https://open.spotify.com/embed/playlist/5AoCSM1Ji4K7qIykyPRhVt?utm_source=generator"
          width="100%"
          height="352"
          frameBorder="0"
          allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
          loading="lazy"
        ></iframe>
        <iframe
          style="border-radius: 12px"
          src="https://open.spotify.com/embed/playlist/0CpDMepAfWXIhrllmwZsI0?utm_source=generator"
          width="100%"
          height="352"
          frameBorder="0"
          allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
          loading="lazy"
        ></iframe>
        <iframe
          style="border-radius: 12px"
          src="https://open.spotify.com/embed/playlist/4WuYnGsijDo438YVcbFIfV?utm_source=generator"
          width="100%"
          height="352"
          frameBorder="0"
          allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
          loading="lazy"
        ></iframe>
      </div>
    </div>
  </main>
  <FooterView />
</template>
