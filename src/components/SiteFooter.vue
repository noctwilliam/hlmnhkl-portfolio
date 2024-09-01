<template>
  <footer class="outline outline-1 outline-offset-1 outline-gray-300 bg-gray-900 text-white text-center py-4">
    <div class="container mx-auto text-center">
      <p>&copy; {{ new Date().getFullYear() }} Hilman Haikal. All rights reserved.</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'SiteFooter',
};
</script>

<style scoped>
footer {
  background-color: rgb(17 24 39);
  color: white;
  text-align: center;
  padding: 1rem;
}
</style>
