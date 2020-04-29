<template>
  <nuxt-link :to="'jokes/' + id">
    <div class="joke">
      <p>{{ joke }}</p>
    </div>
  </nuxt-link>
</template>

<script>
export default {
  name: 'Joke',
  props: {
    joke: { type: String, default: null },
    id: { type: String, default: null }
  }
}
</script>

<style>
.joke {
  padding: 1rem;
  border: 1px solid #ccc;
  margin: 1rem 0;
}
</style>
