<template>
  <section class="container">
    <div>
      <logo />
      <h1 class="title">
        myssr--ceshi
      </h1>
      <h2 class="subtitle">
        My doozie Nuxt.js project
      </h2>
      <div class="links">
        <a
          href="/news"
          target="_blank"
          class="button--grey"
        >NEWS</a>
        <a
          id="p"
          href="/about"
          target="_blank"
          class="button--grey"
        >ABOUT</a>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
export default {
  components: {
    Logo
  },
  data() {
    return {
    }
  },
  mounted() {
    // eslint-disable-next-line no-console
    console.log(document.getElementById('p'))
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
