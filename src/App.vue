<template>
  <div id="app">
    <h1>I am parent component!</h1>
    <Nested/>
  </div>
</template>

<script>
import Nested from './components/Nested'
export default {
  name: 'App',
  components: {
    Nested
  }
}
</script>

<style>

</style>
