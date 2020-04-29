<template>
  <div>
    <h1>About page</h1>
    <p>Vue and Nuxt web app</p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'About the app',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Vue and Nuxt web app'
        }
      ]
    }
  }
}
</script>

<style></style>
