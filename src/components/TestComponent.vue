<template>
  <div>
    <h1>devil</h1>
  </div>
</template>

<script>
export default {
  name: 'TestComponent',
  components: {},
  data() {
    return {}
  },
//   props: [''],
//   inject: [''],
  provide() {
    return {}
  },
  computed: {},
  watch: {},
  methods: {},
  beforeCreate() {},
  created() {
    const t = { a: 2e3, b: 3e3 }
    console.log('t', t?.name?.ss ?? 'is', t)
  },
  beforeMount() {},
  mounted() {},
  beforeUpdated() {},
  updated() {},
  beforeDestroy() {},
  destroyed() {}
}
</script>
<style lang='' scoped>
</style>