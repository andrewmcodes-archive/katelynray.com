<template>
  <section class="container mx-auto">
    <transition name="fade">
      <div class="px-4">
        <img
          src="https://res.cloudinary.com/onshore-studios/image/upload/v1547170754/katelynray/working_late.svg"
          alt="setup wizard illustration"
          width="480px"
          class="mb-6"
        >
        <h1 class="title">Hi! I'm Katelyn</h1>
        <h2 class="subtitle">Checkout my resume to learn more about me <br >or shoot me an email to get in touch!</h2>
        <div class="links">
          <a
            href="mailto:katelyn.ray34@gmail.com?Subject=Hello"
            title="Katelyn Ray Email"
            target="_blank"
            class="button--white"
          >Email Me</a>
          <a
            href="Katelyn_Ray_Resume.pdf"
            title="Katelyn Ray Resume"
            target="_blank"
            class="button--purple"
          >Download Resume</a>
        </div>
      </div>
    </transition>
  </section>
</template>

<style>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.3s cubic-bezier(0.55, 0, 0.1, 1);
}

.fade-enter,
.fade-leave-to {
  opacity: 0;
}

.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Montserrat', 'Source Sans Pro', -apple-system,
    BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 600;
  letter-spacing: 1px;
  color: #6c63ff;
  @apply text-5xl mb-4;
}

.subtitle {
  font-weight: 350;
  word-spacing: 2px;
  /* color: #6c63ff; */
  @apply text-xl leading-loose mb-6 text-purple-darker;
}

.links {
  padding-top: 15px;
}
</style>
