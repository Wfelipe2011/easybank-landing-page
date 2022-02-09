<template>
  <section
    class="container flex flex-col items-center justify-center pt-16 pb-8 mx-auto my-0 overflow-hidden"
  >
    <!-- items-center justify-center gap-4 pt-8 pb-16 mx-auto md:justify-evenly md:flex-wrap 2xl:justify-between lg:mx-auto lg:my-0" -->
    <div class="xl:w-full">
      <h2
        class="w-64 mx-auto my-0 text-4xl text-center lg:w-full 2xl:text-left"
      >
        Last Article
      </h2>
      <div
        class="flex flex-col items-center justify-center gap-4 pt-16 pb-8 mx-auto my-0 md:w-192 2xl:w-full md:flex-row md:flex-wrap 2xl:justify-between"
      >
        <CardArticle
          file-name="image-currency"
          author="Claire Robinson"
          title="Receive money in any currency with no fees"
          text-content="the world is getting smaller and we're becoming more mobile. So why should you be forced to only receive money in a single..."
        />
        <CardArticle
          file-name="image-restaurant"
          author="Wilson Hutton"
          title="Treat yourself without worrying about money"
          text-content="Our simple budgeting feature allows you to separate out your spending and set realistic limits each month. That means you..."
        />
        <CardArticle
          file-name="image-plane"
          author="Wilson Hutton"
          title="Take your Easybank card wherever you go"
          text-content="We want you to enjoy your travels. This is why we don't charge any fees on purchases while you're abroad. We'll even show you..."
        />
        <CardArticle
          file-name="image-confetti"
          author="Claire Robinson"
          title="Our invite-only Beta accounts are now live!"
          text-content="After a lot of hard work by the while team, we're excited to launch our closed beta. It's easy to request an invite through the site..."
        />
      </div>
    </div>
  </section>
</template>
