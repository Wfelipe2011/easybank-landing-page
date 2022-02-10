<template>
  <header
    class="fixed z-50 flex items-center justify-between w-full px-4 py-6 mx-auto xl:container bg-base-200"
    :class="{ relative: !showModal }"
  >
    <nuxt-link to="/">
      <img src="~/assets/images/logo.svg" alt="logo" />
    </nuxt-link>

    <ul class="hidden gap-8 font-semibold lg:flex text-base-500">
      <nuxt-link class="tg" to="/">Home</nuxt-link>
      <nuxt-link class="tg" :to="{ name: 'AboutPage' }">About</nuxt-link>
      <nuxt-link class="tg" to="#contact">Contact</nuxt-link>
      <nuxt-link class="tg" to="#blog">Blog</nuxt-link>
      <nuxt-link class="tg" to="#careers">Careers</nuxt-link>
    </ul>
    <ButtonReqInvite class="hidden lg:block" />
    <button class="lg:hidden" @click="showModal = !showModal">
      <IconHamburguer />
    </button>

    <div
      class="fixed left-0 w-full h-screen pt-8 mt-1 top-16 bg-overlay"
      :class="{ hidden: !showModal }"
    >
      <div
        class="container max-w-sm p-2 mx-auto my-0 rounded bg-primary-content animationFadeIn"
      >
        <ul class="flex flex-col items-center gap-4 py-4 text-lg font-medium">
          <nuxt-link class="hover:text-secondary" to="/">Home</nuxt-link>
          <nuxt-link class="hover:text-secondary" :to="{ name: 'AboutPage' }"
            >About</nuxt-link
          >
          <nuxt-link class="hover:text-secondary" to="#contact"
            >Contact</nuxt-link
          >
          <nuxt-link class="hover:text-secondary" to="#blog">Blog</nuxt-link>
          <nuxt-link class="hover:text-secondary" to="#careers"
            >Careers</nuxt-link
          >
        </ul>
      </div>
    </div>
  </header>
</template>
<script>
import IconHamburguer from '~/assets/images/icon-hamburger.svg?inline'
export default {
  components: {
    IconHamburguer,
  },
  data() {
    return {
      showModal: false,
    }
  },
}
</script>
<style scoped>
.tg.nuxt-link-exact-active.nuxt-link-active::after {
  content: '';
  display: block;
  height: 4px;
  top: 30px;
  @apply w-full relative bg-secondary rounded-t-full;
}

.animationFadeIn {
  animation: fadeIn 0.3s ease-in-out;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translate3d(0, -40px, 0);
  }
  to {
    opacity: 1;
    transform: translate3d(0, 0, 0);
  }
}
</style>
