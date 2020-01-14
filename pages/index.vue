<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">personal-site</h1>
      <h2 class="subtitle">Personal developer website</h2>
      <div class="links">
        <a class="button--green" href="https://nuxtjs.org/" target="_blank">
          Documentation
        </a>
        <a
            class="button--grey"
            href="https://github.com/nuxt/nuxt.js"
            target="_blank">
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: { Logo }
}
</script>

<style>
.container {
  align-items: center;
  display: flex;
  justify-content: center;
  margin: 0 auto;
  min-height: 100vh;
  text-align: center;
}

.title {
  color: #35495e;
  display: block;
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 100px;
  font-weight: 300;
  letter-spacing: 1px;
}

.subtitle {
  color: #526488;
  font-size: 42px;
  font-weight: 300;
  padding-bottom: 15px;
  word-spacing: 5px;
}

.links {
  padding-top: 15px;
}
</style>
