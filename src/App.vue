<template>
  <div
    class="
      w-full
      h-screen
      flex
      items-center
      justify-center
      overflow-hidden
      bg-gradient-to-br
      from-indigo-600
      to-purple-800
    "
  >
    <div class="absolute opacity-0 z-50">
      <img class="w-[442px]" src="/assets/images/iphone-12.jpg" alt="" />
    </div>
    <div
      class="
        bg-black
        w-[422px]
        h-[866px]
        rounded-[3.8rem]
        flex
        items-center
        justify-center
        ring-gray-800 ring-8
      "
    >
      <div
        style="background-image: url(/assets/images/wallpaper.jpg)"
        class="
          bg-cover
          w-[390px]
          h-[834px]
          rounded-[3rem]
          relative
          overflow-auto
        "
      >
        <div
          class="
            bg-black
            fixed
            block
            h-8
            w-52
            left-1/2
            -translate-x-1/2
            rounded-b-[1.2rem]
          "
        ></div>
        <div class="py-8 px-4 w-full"></div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>
