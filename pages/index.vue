<template>
  <div class="min-w-screen min-h-screen w-full h-full bg-[#161618] text-white">
    <div
      class="p-12 h-screen w-screen flex flex-col items-center justify-center"
    >
      <h1 class="text-[108px] font-bold text-center">
        STOP LIVING IN YOUR FUCKING PHONE!
      </h1>
      <h2 class="mb-5 text-lg font-normal">
        you have to think about wtf you're doing with your life.
      </h2>
      <div class="inline-flex justify-between gap-4">
        <button
          class="px-4 py-3 rounded-full bg-white font-bold text-black border-[5px] border-white hover:bg-transparent hover:text-white transition-all duration-300 ease-in-out"
        >
          yeah.
        </button>

        <button
          class="px-4 py-3 rounded-full bg-white font-bold text-black border-[5px] border-white hover:bg-transparent hover:text-white transition-all duration-300 ease-in-out"
        >
          nah i'm a terrible loser.
        </button>
      </div>
    </div>
  </div>
</template>
<script setup>
const landingTexts = ref([
  "STOP LIVING IN YOUR FUCKING PHONE!",
  "STOP SCROLLING MINDLESSLY.",
  "STOP FEELING FAKE EMOTIONS",
  "STOP JUST CONSUMING",
  "START TO LIVE",
]);
const whattheydontcare = ref([
  "you",
  "your life",
  "your hapiness",
  "your health",
]);
</script>
<style scoped>
.dollarbg {
  background-image: url("/dollar.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-clip: content-box;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
