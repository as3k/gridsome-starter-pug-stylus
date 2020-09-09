<template lang="pug">

  Layout
    .container(class="mx-auto")
      //- Learn how to use images here: https://gridsome.org/docs/images
      g-image(alt="example image" src="~/favicon.png" width="135")

      h1 Hello, world!

      p Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores

      p.home-links
        a(href="https://gridsome.org/docs/" target="_blank" rel="noopener") Gridsome Docs
        a(href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener") GitHub
    
</template>
  
<style lang="stylus">
</style>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>
