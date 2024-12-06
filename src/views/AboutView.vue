<template>
  <div class="bg-[#a2a8d3] py-8">
    <FadeWrapper>
      <div class="max-w-4xl mx-auto space-y-8">
        <div class="bg-white rounded-lg shadow-md p-6 flex items-center">
          <div class="flex-shrink-0 mr-6">
            <img
              src="/pdp.png"
              alt="Profile Picture"
              class="w-32 h-32 rounded-full"
            />
          </div>
          <div>
            <h1 class="text-3xl font-bold mb-2">Qin-Hao Wu</h1>
            <p class="text-gray-500 mb-4">FullStack Developer</p>
            <p class="text-gray-700 mb-8">
              Hi there! My name is Qin-Hao Wu and I'm a FullStack Developer with
              a passion for building innovative solutions. I have experience
              working with a variety of technologies.
            </p>
          </div>
        </div>
        <div class="bg-white rounded-lg shadow-md p-6 flex items-center">
          <div class="flex-shrink-0 mr-6">
            <img
              src="/epitech.png"
              alt="Company Logo"
              class="w-32 h-32 rounded-full object-contain"
            />
          </div>
          <div>
            <h3 class="text-xl font-bold mb-2">Student</h3>
            <p class="text-gray-500 mb-2">Epitech (2023 - XXXX)</p>
            <p class="text-gray-700">
              Inside Epitech i have worked on multiple projects, from fullstack
              projects to Devops projects with a lot of different stack.
            </p>
          </div>
        </div>
        <div class="bg-white rounded-lg shadow-md p-6 flex items-center">
          <div class="flex-shrink-0 mr-6">
            <img
              src="/kering.png"
              alt="Company Logo"
              class="w-32 h-32 rounded-full object-contain"
            />
          </div>
          <div>
            <h3 class="text-xl font-bold mb-2">FullStack Developer / DevOps</h3>
            <p class="text-gray-500 mb-2">Qindi Wu Consulting (2023 - 2024)</p>
            <p class="text-gray-700">
              Building an showcase website for the company Qindi Wu Consulting
              and deploying it. Stack used for the website : -VueJs -Tailwindcss
              Stack used for the deployment : -gitlab pipeline -Docker -AWS
            </p>
          </div>
        </div>
        <div class="bg-white rounded-lg shadow-md p-6 flex items-center">
          <div class="flex-shrink-0 mr-6">
            <img
              src="/hermes.png"
              alt="Company Logo"
              class="w-32 h-32 rounded-full object-contain"
            />
          </div>
          <div>
            <h3 class="text-xl font-bold mb-2">Intern</h3>
            <p class="text-gray-500 mb-2">Hermès (XXXX - XXXX)</p>
            <p class="text-gray-700">
              During my internship at Globex Corporation, I gained valuable
              experience in front-end development, working with frameworks like
              Vue.js and React.
            </p>
          </div>
        </div>
        <div class="bg-white rounded-lg shadow-md p-6 flex items-center">
          <div class="flex-shrink-0 mr-6">
            <img
              src="/capgemini.png"
              alt="Company Logo"
              class="w-32 h-32 rounded-full object-contain"
            />
          </div>
          <div>
            <h3 class="text-xl font-bold mb-2">Intern</h3>
            <p class="text-gray-500 mb-2">Capgemini (XXXX - XXXX)</p>
            <p class="text-gray-700">
              During my internship at Globex Corporation, I gained valuable
              experience in front-end development, working with frameworks like
              Vue.js and React.
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
