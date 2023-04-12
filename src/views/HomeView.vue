<script setup>

import HomeCard from '../components/HomeCard.vue';

</script>

<template>

  <div class="p-8">
    <button 
      type="button"
      class="text-white text-2x1 font-semibold hover:underline cursor-pointer"
    >
      Podcasts to make you smarter
    </button>
  </div>
  <div class="py-1.5"></div>
  <div class="flex items-center">
    <HomeCard image="https://picsum.photos/id/30/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard image="https://picsum.photos/id/35/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard class="md:block hidden" image="https://picsum.photos/id/40/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard class="lg:block hidden" image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard class="xl:block hidden" image="https://picsum.photos/id/55/300/300" title="Title is here" subTitle="Subtitle is here"/>
  </div>

  <div class="p-8">
    <button 
      type="button"
      class="text-white text-2x1 font-semibold hover:underline cursor-pointer"
    >
      Recommended for you
    </button>
  </div>
  <div class="py-1.5"></div>
  <div class="flex items-center">
    <HomeCard image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard image="https://picsum.photos/id/38/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard class="md:block hidden" image="https://picsum.photos/id/43/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard class="lg:block hidden" image="https://picsum.photos/id/48/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard class="xl:block hidden" image="https://picsum.photos/id/53/300/300" title="Title is here" subTitle="Subtitle is here"/>
  </div>
  
  <div class="p-8">
    <button 
      type="button"
      class="text-white text-2x1 font-semibold hover:underline cursor-pointer"
    >
      New for users from users
    </button>
  </div>
  <div class="py-1.5"></div>
  <div class="flex items-center">
    <HomeCard image="https://picsum.photos/id/39/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard image="https://picsum.photos/id/41/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard class="md:block hidden" image="https://picsum.photos/id/23/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard class="lg:block hidden" image="https://picsum.photos/id/28/300/300" title="Title is here" subTitle="Subtitle is here"/>
    <HomeCard class="xl:block hidden" image="https://picsum.photos/id/21/300/300" title="Title is here" subTitle="Subtitle is here"/>
  </div>

</template>
