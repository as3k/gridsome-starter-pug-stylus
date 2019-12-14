<template lang="pug">
  .layout
    header.header
      
      strong
        g-link(to="/") {{ $static.metadata.siteName}}
      
      nav.nav
        g-link.nav__link(to="/") Home
        g-link.nav__link(to="/about") About

    slot
  
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style lang="stylus">

body 
  font-family -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif
  margin 0
  padding 0
  line-height 1.5


.layout
  max-width 760px
  margin 0 auto
  padding-left 20px
  padding-right 20px

.header 
  display flex
  justify-content space-between
  align-items center
  margin-bottom 20px
  height 80px


.nav__link 
  margin-left 20px

</style>
