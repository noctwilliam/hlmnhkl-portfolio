<template>
  <section id="projects" class="py-16 px-4 bg-gray-100">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold text-center">Projects</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mt-8">
        <!-- Example Project -->
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">Project Title</h3>
          <p class="mt-2">A brief description of the project, technologies used, and key features.</p>
          <a href="#" class="mt-4 inline-block text-blue-500">View Project</a>
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
