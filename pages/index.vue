<template>
  <div class="container screen">
    <div>
      <logo />
      <h1 class="title">
        Ubuntu 20.04 release date: April 2020
      </h1>
      <h2 class="subtitle">
        Ubuntu.space is under construction
      </h2>
      <p class="description">Site is not official and powered by Node.js developer and Ubuntu user since 2009.</p>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  head: {
    title: 'Ubuntu 20.04 release date: April 2020 | ubuntu.space'
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 35px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 22px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.description {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
}

.links {
  padding-top: 15px;
}
</style>
