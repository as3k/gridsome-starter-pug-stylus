<template lang="pug">
  layout
    .four-oh-four-container(class="absolute z-0 inset-0 min-h-screen flex flex-col items-center justify-center")
      .text(class="flex flex-col items-center text-center")
        .lg(class="text-6xl font-bold tracking-widest") 404
        .sm(class="text-lg mt-2") Page not found

</template>

<style lang="stylus" scoped>
</style>

<script>
export default {
  name: 'PageNotFound',
  metaInfo: {
    title: '404 Page Not Found'
  },
  data: () => ({

  }),
  props: [],
  computed: {},
  methods: {},
  mounted() {},
  components: {},
}
</script>