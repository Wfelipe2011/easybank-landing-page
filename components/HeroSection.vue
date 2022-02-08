<template>
  <section
    class="flex flex-col-reverse items-center w-full rounded-md sm:mx-auto sm:my-0 lg:flex-row lg:px-4"
  >
    <div
      class="flex flex-col justify-center text-center align-middle lg:text-left"
    >
      <h1 class="mx-auto my-0 text-5xl text-dark-blue w-96">
        Next generation digital banking
      </h1>
      <p class="mx-auto my-8 text-lg text-grayish-blue w-96">
        Take your fubabcual life online. Your Easybank account will be a
        one-stop-shop for spending, saving budgeting, investing, and much more
      </p>
      <div class="flex justify-center lg:justify-start">
        <ButtonReqInvite />
      </div>
    </div>
    <div class="w-full overflow-hidden bg-intro-img">
      <img
        class="relative max-w-md mx-auto my-0 -top-40 lg:-top-20 lg:-right-40 lg:max-w-lg"
        src="~/assets/images/image-mockups.png"
      />
    </div>
  </section>
</template>
<style lang="css" scoped>
.bg-intro-img {
  background: url('~/assets/images/bg-intro-mobile.svg') no-repeat center center;
  background-size: cover;
  @media (min-width: 1024px) {
    background: url('~/assets/images/bg-intro-desktop.svg') no-repeat center
      center;
    background-position: 0% -100px;
    background-size: cover;
  }
  @media (min-width: 1536px) {
    background-position: 0% -400px;
  }
}
</style>
