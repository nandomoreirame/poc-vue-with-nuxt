<template>
  <section class="container">
    <div>
      <hello/>
      <nuxt-link to="/about">About page</nuxt-link>
    </div>
  </section>
</template>

<script>
import Hello from '~/components/Hello.vue'

export default {
  components: {
    Hello
  }
}
</script>

<style lang="sass">
</style>
