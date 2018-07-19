<template>
  <section class="home">
    <div>
      <div class="screen">
        <object>  
          <embed src="/letter.svg">
        </object>

          <nuxt-link to="/works">Works</nuxt-link>
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>
