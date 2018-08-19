<template lang="html">
  <div>
    <h1>I am a nested component</h1>
    <a href="https://github.com/shanegibney/vue-nested-components">Return to repo</a>
    <NestedNested/>
  </div>
</template>

<script>
import NestedNested from './NestedNested'
export default {
  name: 'Nested',
  components: {
    NestedNested
  },
  data(){
    return
  }
}
</script>

<style lang="css">
</style>
