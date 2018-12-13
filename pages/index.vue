<template>
  <section class="container mx-auto">
    <div>
      <img
        src="undraw_setup_wizard_r6mr.svg"
        alt=""
        width="480px"
        class="mb-6"
      >
      <h1 class="title">Katelyn Ray</h1>
      <h2 class="subtitle">Welcome to my personal site</h2>
      <div class="links">
        <a
          href="Katelyn_Ray_Resume.pdf"
          title="Katelyn Ray Resume"
          target="_blank"
          class="button--purple">Download Resume</a>
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
  font-weight: 300;
  font-size: 100px;
  letter-spacing: 1px;
  @apply mb-6 text-purple-dark;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  word-spacing: 5px;
  padding-bottom: 15px;
  @apply text-purple-dark;
}

.links {
  padding-top: 15px;
}
</style>
