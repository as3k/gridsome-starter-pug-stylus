<template lang="pug">

  Layout
    .homepage-hero(class="bg-blue-200")

      .hero-container(class="grid grid-cols-2 md:grid-cols-4")
        .gridsome(class="h-20 bg-gridsome flex items-center justify-center py-32 md:py-48")
          g-image(src="~/assets/gridsome-dark.svg" class="h-16")
        .pug(class="h-20 bg-pug flex items-center justify-center py-32 md:py-48")
          g-image(src="~/assets/pug.svg" class="h-24")
        .stylus(class="h-20 bg-stylus flex items-center justify-center py-32 md:py-48")
          g-image(src="~/assets/stylus.svg" class="h-16")
        .tailwind(class="h-20 bg-tailwind flex items-center justify-center py-32 md:py-48")
          g-image(src="~/assets/tailwind.svg" class="h-16")

    .container(class="max-w-2xl px-4 mx-auto mt-16 text-center")

      h1(class="font-bold text-4xl leading-tight") The 
        span(class="italic") Easiest 
        | way to develop on Gridsome!

      p(class="text-xl mt-8 leading-loose text-gray-700") As if developing on Gridsome wasn't easy enough already, When you mix Pug, Stylus, and TailwindCSS into the mix development gets taken to the next level!

      
      
</template>
  
<style lang="stylus">
  $gridsome-green = #00a672
  $pug-red = #a86454
  $tailwind-cyan = #edf2f7
  $stylus-orange = #ff6347

  .bg-gridsome
    background-color $gridsome-green
  .bg-pug
    background-color $pug-red
  .bg-tailwind
    background-color $tailwind-cyan
  .bg-stylus
    background-color $stylus-orange

</style>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>
