<template>
  <header
    class="container mx-auto my-0 flex justify-between items-center py-6 px-4"
  >
    <nuxt-link to="/">
      <Logo />
    </nuxt-link>

    <ul class="hidden lg:flex gap-8 text-grayish-blue">
      <div>
        <nuxt-link class="tg" to="#home">Home</nuxt-link>
      </div>
      <nuxt-link class="tg" to="#about">About</nuxt-link>
      <nuxt-link class="tg" to="#contact">Contact</nuxt-link>
      <nuxt-link class="tg" to="#blog">Blog</nuxt-link>
      <nuxt-link class="tg" to="#careers">Careers</nuxt-link>
    </ul>
    <button
      class="hidden lg:block bg-gradient-to-r from-lime-green to-bright-cyan px-10 py-4 rounded-full text-light-grayish-blue font-bold relative right-0"
    >
      Request Invite
    </button>
    <button class="lg:hidden">
      <IconHamburguer />
    </button>
  </header>
</template>
<script>
import Logo from '~/assets/images/logo.svg?inline'
import IconHamburguer from '~/assets/images/icon-hamburger.svg?inline'
export default {
  components: {
    Logo,
    IconHamburguer,
  },
}
</script>
<style scoped>
.tg.nuxt-link-exact-active.nuxt-link-active::after {
  content: '';
  display: block;
  height: 4px;
  top: 38px;
  @apply w-full relative bg-lime-green rounded-t-full;
}
</style>
