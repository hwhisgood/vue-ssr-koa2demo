<template>
  <div class="welcome">
    welcome to {{name}}
  </div>
</template>

<script>
export default {
  name: 'welcome',
  props: {
    name: {
      type: String,
      default: ''
    }
  },
  data () {
    return {}
  }
}
</script>

<style lang="scss">

</style>
