<template lang="pug">
  .layout(class="relative")
    page-header

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
</style>

<script>
import PageHeader from '../components/page-header'

export default {
  data: () => ({
    
  }),
  components: { PageHeader }
}
</script>
