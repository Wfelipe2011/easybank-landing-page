<template>
  <div
    class="flex flex-col items-center justify-center mb-8 w-80 2xl:items-start"
  >
    <img :src="require(`~/assets/images/${fileName}.svg`)" />
    <h2 class="my-4 text-lg font-semibold">{{ title }}</h2>
    <p class="w-10/12 text-center text-base-500 2xl:text-left">
      {{ textContent }}
    </p>
  </div>
</template>
<script>
export default {
  props: {
    fileName: {
      type: String,
      default: 'icon-online',
      required: true,
    },
    title: {
      type: String,
      default: '',
      required: true,
    },
    textContent: {
      type: String,
      default: '',
      required: true,
    },
  },
}
</script>
