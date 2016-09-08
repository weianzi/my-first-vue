<template>
  <div>
    <Display></Display>
    <Increment></Increment>
  </div>
</template>

<script>
import Display from './components/Display'
import Increment from './components/Increment'
import store from './vuex/store'

export default {
  components: {
    Display,
    Increment
  },
  store
}
</script>

<style>
html {
  height: 100%;
}
body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
</style>
