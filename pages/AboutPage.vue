<template>
  <main>
    <section
      class="flex items-center w-full mb-16 rounded-md min-height-content xl:container md:mx-auto md:my-0 sm:mx-auto sm:my-0 lg:flex-row"
    >
      <h1 class="p-4 text-6xl font-bold text-primary">This is about page</h1>
    </section>
  </main>
</template>
<script>
export default {
  name: 'AboutPage',
  layout: 'DefaultLayout',
}
</script>
<style scoped>
.min-height-content {
  height: calc(100vh - 304px);
}
</style>
