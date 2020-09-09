<template lang="pug">
  .layout(class="relative")
    page-header
    
    div(v-if="spicy" class="w-full bg-red-500 h-24")

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
