<template>
  <section id="projects" class="py-16">
    <div class="container mx-auto text-center">
      <h2 class="text-3xl font-bold mb-8">Projects</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 gap-8">
        <!-- Example project item -->
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold mb-2">Project 1</h3>
          <p class="text-gray-600">A brief description of Project 1.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold mb-2">Project 2</h3>
          <p class="text-gray-600">A brief description of Project 2.</p>
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
