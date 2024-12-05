<template>
  <div class="bg-neutral-500 flex flex-col items-center justify-center">
    <FadeWrapper>
      <div
        class="bg-white rounded-lg shadow-md p-6 mb-8 w-full max-w-lg"
        v-for="cert in certifications"
        :key="cert.title"
      >
        <div class="flex items-center">
          <div class="w-1/3">
            <img :src="cert.imagePath" class="w-full h-auto" />
          </div>
          <div class="w-2/3 pl-6">
            <h2 class="text-xl font-bold mb-2">{{ cert.title }}</h2>
            <p class="text-gray-600 mb-2">Earned in {{ cert.year }}</p>
            <p class="text-gray-600 mb-2">Certification Id : {{ cert.id }}</p>
            <p class="text-base">{{ cert.description }}</p>
          </div>
        </div>
      </div>
    </FadeWrapper>
  </div>
</template>

<script>
import FadeWrapper from "@/components/FadeWrapper.vue";
export default {
  data() {
    return {
      certifications: [
        {
          link: "https://www.credly.com/badges/9d319d5c-94f7-4851-8b0c-f160eb7ae312/public_url",
          title: "AWS Certified Developer",
          year: 2022,
          id: "1YBG7P5CDFF41199",
          description:
            "Demonstrates proficiency in building and deploying secure and scalable applications on the AWS platform.",
          imagePath: "/aws2.png",
        },
        {
          link: "https://www.credly.com/badges/9d319d5c-94f7-4851-8b0c-f160eb7ae312/public_url",
          title: "Kubernetes Certified Administrator",
          year: 2023,
          id: "LF-1ntu4zurrv",
          description:
            "Validates the skills and knowledge to configure, manage, and operate production-grade Kubernetes clusters.",
          imagePath: "/kubernetes2.png",
        },
      ],
    };
  },
  components: {
    FadeWrapper,
  },
};
</script>

<style></style>
