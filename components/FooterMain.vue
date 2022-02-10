<template>
  <footer class="bg-primary">
    <section class="grid py-8 mx-auto my-0 md:grid-cols-8 lg:container md:px-4">
      <div
        class="flex flex-col items-center justify-center pt-8 md:items-start md:col-span-2 md:justify-start"
      >
        <nuxt-link to="/" class="mb-8 lg:mb-10">
          <img src="~/assets/images/logo-white.svg" alt="logo" />
        </nuxt-link>
        <div class="flex justify-between gap-4">
          <nuxt-link to="#">
            <img src="~/assets/images/icon-facebook.svg" alt="facebook" />
          </nuxt-link>
          <nuxt-link to="#">
            <img src="~/assets/images/icon-youtube.svg" alt="youtube" />
          </nuxt-link>
          <nuxt-link to="#">
            <img src="~/assets/images/icon-twitter.svg" alt="twitter" />
          </nuxt-link>
          <nuxt-link to="#">
            <img src="~/assets/images/icon-pinterest.svg" alt="pinterest" />
          </nuxt-link>
          <nuxt-link to="#">
            <img src="~/assets/images/icon-instagram.svg" alt="instagram" />
          </nuxt-link>
        </div>
      </div>

      <div
        class="py-8 text-base-300 md:flex md:justify-start md:items-center md:gap-16 md:col-span-4"
      >
        <ul
          class="flex flex-col items-center justify-center gap-2 mb-2 md:mb-0 md:items-start"
        >
          <nuxt-link class="hover:text-secondary" to="#">About Us</nuxt-link>
          <nuxt-link class="hover:text-secondary" to="#">Contact</nuxt-link>
          <nuxt-link class="hover:text-secondary" to="#">Blog</nuxt-link>
        </ul>
        <ul
          class="flex flex-col items-center justify-center gap-2 md:items-start"
        >
          <nuxt-link class="hover:text-secondary" to="#">Careers</nuxt-link>
          <nuxt-link class="hover:text-secondary" to="#">Support</nuxt-link>
          <nuxt-link class="hover:text-secondary" to="#"
            >Privacy Policy</nuxt-link
          >
        </ul>
      </div>

      <div
        class="flex flex-col items-center gap-4 pb-8 text-base-500 md:items-end md:pt-8 md:col-span-2 md:justify-start"
      >
        <ButtonReqInvite />
        <p class="md:text-right">&copy; Easybank. All Rights Reserved</p>
      </div>
    </section>
  </footer>
</template>
<style scoped></style>
