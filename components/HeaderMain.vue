<template>
  <header
    class="container relative z-10 flex items-center justify-between px-4 py-6 mx-auto my-0 bg-base-200"
  >
    <nuxt-link to="/">
      <img src="~/assets/images/logo.svg" alt="logo" />
    </nuxt-link>

    <ul class="hidden gap-8 font-semibold lg:flex text-base-500">
      <div>
        <nuxt-link class="tg" to="/">Home</nuxt-link>
      </div>
      <nuxt-link class="tg" to="#about">About</nuxt-link>
      <nuxt-link class="tg" to="#contact">Contact</nuxt-link>
      <nuxt-link class="tg" to="#blog">Blog</nuxt-link>
      <nuxt-link class="tg" to="#careers">Careers</nuxt-link>
    </ul>
    <ButtonReqInvite class="hidden lg:block" />
    <button class="lg:hidden">
      <IconHamburguer />
    </button>
  </header>
</template>
<script>
import IconHamburguer from '~/assets/images/icon-hamburger.svg?inline'
export default {
  components: {
    IconHamburguer,
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
</style>
