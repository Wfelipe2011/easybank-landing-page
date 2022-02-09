<template>
  <div class="bg-white rounded card w-80 h-120">
    <img class="h-56" :src="require(`~/assets/images/${fileName}.jpg`)" />
    <div class="card-body">
      <h2 class="text-base-400">by {{ author }}</h2>
      <h2 class="font-normal cursor-pointer card-title hover:text-secondary">
        {{ title }}
      </h2>
      <p class="text-base-500">
        {{ textContent }}
      </p>
    </div>
  </div>
</template>
<script>
export default {
  props: {
    fileName: {
      type: String,
      default: 'image-confetti',
      required: true,
    },
    author: {
      type: String,
      default: '',
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
