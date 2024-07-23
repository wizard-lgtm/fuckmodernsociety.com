<template>
  <div class="min-h-screen min-w-screen flex flex-col text-center">
    <div class="flex flex-col md:flex-row gap-4">
      <div class="flex flex-col gap-[100px] w-1/2">
        <h2 class="text-[48px] lg:text-[72px] flex-1 leading-none">
          The world has never been more connected
        </h2>
        <video
          autoplay
          muted
          loop
          class="w-full h-full object-cover md:h-[400px]"
        >
          <source
            src="https://res.cloudinary.com/dyhcjtotx/video/upload/v1721715547/seengirl_ocyzmm.mp4"
            type="video/mp4"
          />
          Your browser does not support the video tag.
        </video>
      </div>

      <div class="flex-1 w-1/2 flex md:flex-col gap-[100px]">
        <video autoplay muted loop class="w-full h-full object-cover h-[400px]">
          <source
            src="https://res.cloudinary.com/dyhcjtotx/video/upload/v1721715548/seenboy_brwnaj.mp4"
            type="video/mp4"
          />
          Your browser does not support the video tag.
        </video>
        <h2 class="text-[48px] lg:text-[72px] flex-1 leading-none">
          yet the people never have been more lonely.
        </h2>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style></style>
