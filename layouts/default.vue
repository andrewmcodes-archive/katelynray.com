<template>
  <div>
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

.button--purple {
  display: inline-block;
  text-decoration: none;
  padding: 10px 30px;
  color: #fff;
  background-color: #794acf;
  border-radius: 4px;
  border: 1px solid white;
}

.button--purple:hover {
  border: 1px solid #794acf;
  color: #794acf;
  background-color: #fff;
}

.button--white {
  display: inline-block;
  text-decoration: none;
  padding: 10px 30px;
  border-radius: 4px;
  color: #794acf;
  background-color: #fff;
  border: 1px solid #794acf;
}

.button--white:hover {
  background-color: #794acf;
  color: #fff;
  border: 1px solid white;
}
</style>
