<template>
  <section class="container mx-auto">
    <div class="px-4">
      <img src="undraw_setup_wizard_r6mr.svg" alt="setup wizard illustration" width="480px" class="mb-6">
      <h1 class="title">Katelyn Ray</h1>
      <div class="links">
        <a
          href="Katelyn_Ray_Resume.pdf"
          title="Katelyn Ray Resume"
          target="_blank"
          class="button--purple"
        >Download Resume</a>
      </div>
    </div>
  </section>
</template>

<style>
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
  font-weight: 500;
  letter-spacing: 1px;
  @apply mb-6 text-purple-dark text-5xl mb-8;
}

.subtitle {
  font-weight: 300;
  word-spacing: 2px;
  padding-bottom: 15px;
  @apply text-purple-dark text-3xl;
}

.links {
  padding-top: 15px;
}
</style>
