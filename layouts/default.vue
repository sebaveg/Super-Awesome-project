<template lang="pug">
  #app
    Header
    main.min-h-screen
      nuxt
    Footer
</template>

<script>
import Header from '~/components/layout/Header'
import Footer from '~/components/layout/Footer'
export default {
  name: 'Layout',
  components: { Header, Footer }
}
</script>
