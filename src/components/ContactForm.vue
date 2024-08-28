<template>
  <section id="contact" class="py-16 text-center">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold mb-8">Contact</h2>
      <form class="max-w-lg mx-auto">
        <div class="mb-4">
          <label for="name" class="block text-sm font-medium mb-2">Name</label>
          <input id="name" type="text" class="w-full border border-gray-300 rounded-md p-2" />
        </div>
        <div class="mb-4">
          <label for="email" class="block text-sm font-medium mb-2">Email</label>
          <input id="email" type="email" class="w-full border border-gray-300 rounded-md p-2" />
        </div>
        <div class="mb-4">
          <label for="message" class="block text-sm font-medium mb-2">Message</label>
          <textarea id="message" rows="4" class="w-full border border-gray-300 rounded-md p-2"></textarea>
        </div>
        <button type="submit" class="bg-blue-600 text-white px-4 py-2 rounded-md">Send</button>
      </form>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactForm',
};
</script>

<style scoped>
section {
  padding: 4rem 0;
}
</style>
