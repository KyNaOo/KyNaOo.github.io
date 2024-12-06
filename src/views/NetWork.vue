<template>
  <div class="bg-[#a2a8d3] py-8">
    <FadeWrapper>
      <div class="max-w-4xl mx-auto space-y-8">
        <div class="bg-white rounded-lg shadow-md p-6 flex items-center">
          <div class="flex-shrink-0 mr-6">
            <img
              src="/github.png"
              alt="Company Logo"
              class="w-32 h-32 rounded-full object-contain"
            />
          </div>
          <div>
            <h3 class="text-xl font-bold mb-2">Github</h3>
            <p class="text-gray-700">
              <img
                src="https://github-readme-streak-stats.herokuapp.com/?user=kynaoo&theme=tokyonight"
                alt="mystreak"
              />
            </p>
          </div>
        </div>
      </div>
    </FadeWrapper>
  </div>
</template>

<script>
import FadeWrapper from "@/components/FadeWrapper.vue";
export default {
  components: {
    FadeWrapper,
  },
};
</script>

<style scoped></style>
