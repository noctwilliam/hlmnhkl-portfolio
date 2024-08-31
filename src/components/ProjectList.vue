<template>
  <section id="projects" class="outline outline-1 outline-offset-0 outline-gray-300 py-16 px-4 bg-gray-700">
    <div class="container mx-auto text-white">
      <h2 class="text-3xl font-bold text-center">Projects</h2>
      <!-- Update grid classes for responsive layout -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 mt-8">
        <!-- Example Project -->
        <div class="p-6 rounded-lg shadow-md bg-gray-900 text-white">
          <h3 class="text-xl font-semibold">MindGuard</h3>
          <img src="/images/project1.png" alt="MindGuard Project" class="w-auto h-auto mt-4 rounded-lg shadow-md" />
          <p class="mt-2 text-justify">
            The MindGuard project is a web-based mental health assessment tool using machine learning models for PHQ-9 depression severity analysis and sentiment analysis, built with Python, Flask, and supporting libraries like nltk, scikit-learn, and Seaborn.
          </p>
          <a href="https://hlmnhkl-mindguard.netlify.app" class="hover:bg-gray-300 hover:text-gray-950 mt-12 inline-block bg-gray-700 text-white py-2 px-4 rounded-lg" target="_blank" rel="noopener noreferrer">View Project</a>
        </div>
        <div class="p-6 rounded-lg shadow-md bg-gray-900 text-white">
          <h3 class="text-xl font-semibold">Recipe App</h3>
          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-2">
            <img src="/images/project2 (1).png" alt="RecipeApp" class="w-60 h-auto mt-4 rounded-lg shadow-md" />
            <img src="/images/project2 (2).png" alt="RecipeApp" class="w-60 h-auto mt-4 rounded-lg shadow-md" />
            <img src="/images/project2 (3).png" alt="RecipeApp" class="w-60 h-auto mt-4 rounded-lg shadow-md" />
          </div>
          <p class="mt-2 text-justify">
            The Recipe App is a Flutter-based mobile application that allows users to browse, manage, and store recipes with detailed instructions and images, using JSON as the data source.
          </p>
        </div>
        <div class="p-6 rounded-lg shadow-md bg-gray-900 text-white">
          <h3 class="text-xl font-semibold">Laptop Cost Estimation</h3>
          <div>
            <img src="/images/project3 (1).png" alt="LaptopCostEstimation" class="w-auto h-auto mt-4 rounded-lg shadow-md" />
          </div>
          <p class="mt-2 text-justify">
            The project is a Cost Estimation application, using technologies such as Python, Flask, and scikit-learn. Key features include a machine learning model for price prediction, a web interface for user interaction, and necessary configuration files for deployment.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectList',
};
</script>

<style scoped>
section {
  padding: 4rem 0;
}
</style>
