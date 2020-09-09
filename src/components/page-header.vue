<template lang="pug">
  header.page-header(class="relative z-10")
    .header-container(class="px-4 md:px-12 py-4 md:py-8 flex justify-between")
      h1(class="text-lg font-bold")
        g-link(to="/") Pug Stylus Tailwind
      
      nav(class="space-x-4")
        g-link(to="/") Home
        g-link(to="/about") About
        g-link(to="/blog") Blog
</template>

<style lang="stylus" scoped>
</style>

<script>
export default {
  name: 'PageHeader',
  data: () => ({

  }),
  props: [],
  computed: {},
  methods: {},
  mounted() {},
  components: {},
}
</script>