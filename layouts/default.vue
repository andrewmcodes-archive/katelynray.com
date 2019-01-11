<template>
  <div class="background-grey">
    <nuxt/>
  </div>
</template>

<style>
html {
  font-family: 'Montserrat', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.background-grey {
  background-color: #f8fafc;
}
.button--purple {
  display: inline-block;
  text-decoration: none;
  padding: 10px 30px;
  color: #f8fafc;
  background-color: #6c63ff;
  border-radius: 4px;
  border: 1px solid #f8fafc;
}

.button--purple:hover {
  border: 1px solid #6c63ff;
  color: #6c63ff;
  background-color: #f8fafc;
}

.button--white {
  display: inline-block;
  text-decoration: none;
  padding: 10px 30px;
  border-radius: 4px;
  color: #6c63ff;
  background-color: #f8fafc;
  border: 1px solid #6c63ff;
}

.button--white:hover {
  background-color: #6c63ff;
  color: #f8fafc;
  border: 1px solid #f8fafc;
}
</style>
