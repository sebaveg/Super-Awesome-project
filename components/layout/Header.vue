<template lang="pug">
  header
    nav.flex.items-center.justify-between.bg-purple-500.p-2
      div.text-white
        nuxt-link(to="/"): h1.text-2xl.font-bold {{ title }}
      div.flex
        div
          nuxt-link(to="/articles").block.inline-block.text-white.font-semibold.mr-4 Articles
          nuxt-link(to="/about").block.inline-block.text-white.font-semibold.mr-4 About
          nuxt-link(to="/blog").block.inline-block.text-white.font-semibold.mr-4 Blog
        div
          nuxt-link(to="/auth/signin" class="hover:bg-white hover:text-purple-500").inline-block.text-sm.text-white.border.rounded.ml-2.px-2 Iniciar sesión
          nuxt-link(to="/auth/signup" class="hover:bg-white hover:text-purple-500").inline-block.text-sm.text-white.border.rounded.ml-2.px-2 Registrarse
    
</template>

<script>
export default {
  data: () => ({
    title: 'Awesome project'
  })
}
</script>
