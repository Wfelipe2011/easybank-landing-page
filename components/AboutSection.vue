<template>
  <section
    class="flex flex-col items-center justify-center w-full pt-4 pb-8 lg:items-start bg-light-grayish-blue"
  >
    <div class="md:p-4 xl:mx-auto xl:my-0 xl:container">
      <div class="mt-16">
        <h2
          class="w-64 mx-auto my-0 text-4xl text-center lg:w-full lg:text-left"
        >
          Why choose Easybank?
        </h2>
        <p
          class="mx-auto mt-4 mb-8 text-center w-80 text-grayish-blue md:w-6/12 lg:text-left lg:mx-0 lg:w-7/12 lg:pr-24 xl:w-5/12 xl:pr-8"
        >
          We leverage Open Banking to turn your bank account into your financial
          hub. Control your finances like never before.
        </p>
      </div>
      <div
        class="flex flex-col items-center justify-center gap-4 md:justify-evenly md:flex-row md:flex-wrap 2xl:justify-between lg:mx-auto lg:my-0"
      >
        <CardProducts
          title="Online Banking"
          file-name="icon-online"
          text-content="Our modern web and mobile applications allow you to keep track of your finances wherever you are in the world."
        />
        <CardProducts
          title="Simple Budgeting"
          file-name="icon-budgeting"
          text-content="See exactly where your money goes each month. Receive notifications when you're close to your hitting limits."
        />
        <CardProducts
          title="Fast Onboarding"
          file-name="icon-onboarding"
          text-content="We don't do branches. Open your account in minutes online and start taking control of your finances right away."
        />
        <CardProducts
          title="Open API"
          file-name="icon-api"
          text-content="Manage your savings, investments, pension, and much more from one account. Tracking your money has never been easier."
        />
      </div>
    </div>
  </section>
</template>
