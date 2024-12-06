<script>
import FadeWrapper from "@/components/FadeWrapper.vue";
export default {
  components: {
    FadeWrapper,
  },
};
</script>
<template>
  <div
    class="flex-grow bg-gradient-to-r from-[#38598b] to-[#a2a8d3] flex items-center justify-center text-white"
  >
    <FadeWrapper>
      <div class="max-w-3xl text-center px-4 sm:px-6 lg:px-8">
        <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold mb-6">
          Welcome to Qin-Hao's Portfolio !
        </h1>
        <p class="text-lg sm:text-xl lg:text-2xl mb-8 leading-relaxed">
          Hey i'm looking for an apprenticeship
        </p>
        <div
          class="flex flex-col sm:flex-row items-center justify-center space-y-4 sm:space-y-0 sm:space-x-6"
        >
          <a
            href="/contact"
            class="bg-white hover:bg-gray-300 text-black font-medium py-3 px-6 rounded-md transition-colors"
          >
            Contact me
          </a>
        </div>
      </div>
    </FadeWrapper>
  </div>
</template>

<style scoped></style>
