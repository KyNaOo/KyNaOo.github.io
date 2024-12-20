<template>
  <div class="bg-[#083D77] py-8">
    <FadeWrapper>
      <div class="max-w-4xl mx-auto space-y-4 flex gap-8 items-center">
        <div class="w-full">
          <div
            class="bg-white rounded-lg shadow-md p-4 flex flex-col items-center space-y-4"
          >
            <div class="mb-2">
              <img
                src="/github.png"
                alt="Company Logo"
                class="w-24 h-24 rounded-full object-contain"
              />
            </div>
            <a
              href="https://github.com/KyNaOo"
              class="text-sm font-bold block text-center"
              >My Github</a
            >
            <img
              src="https://github-readme-streak-stats.herokuapp.com/?user=kynaoo&theme=tokyonight"
              alt="mystreak"
            />
          </div>
        </div>

        <div class="w-full">
          <div
            class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center h-full space-y-2"
          >
            <h2 class="text-xl font-bold mb-4">
              Some Projects I have worked on
            </h2>
            <div class="flex justify-center">
              <a
                href="https://github.com/KyNaOo/Trello_mobile_app"
                target="_blank"
                rel="noopener noreferrer"
                className="transform transition-transform duration-300 hover:scale-105 w-full"
              >
                <img
                  src="https://github-readme-stats.vercel.app/api/pin/?username=kynaoo&repo=Trello_mobile_app&theme=dracula"
                  alt="GitHub Repo Card"
                  class="max-w-full"
                />
              </a>
            </div>
            <div class="flex justify-center">
              <img
                src="https://github-readme-stats.vercel.app/api/pin/?username=madushadhanushka&repo=simple-sqlite&theme=dracula"
                alt="GitHub Repo Card"
                class="max-w-full"
              />
            </div>
            <div class="flex justify-center">
              <img
                src="https://github-readme-stats.vercel.app/api/pin/?username=madushadhanushka&repo=simple-sqlite&theme=dracula"
                alt="GitHub Repo Card"
                class="max-w-full"
              />
            </div>
            <div class="flex justify-center">
              <img
                src="https://github-readme-stats.vercel.app/api/pin/?username=madushadhanushka&repo=simple-sqlite&theme=dracula"
                alt="GitHub Repo Card"
                class="max-w-full"
              />
            </div>
            <div class="flex justify-center">
              <img
                src="https://github-readme-stats.vercel.app/api/pin/?username=madushadhanushka&repo=simple-sqlite&theme=dracula"
                alt="GitHub Repo Card"
                class="max-w-full"
              />
            </div>
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
