<template>
  <button @click='increment'>加1</button>
</template>
<script>
import { incrementCounter } from '../vuex/actions'
export default {
  vuex: {
    actions: {
      increment: incrementCounter
    }
  }
}
</script>

<style scoped>
button {
  border:0;
  width: 100px;
  line-height: 30px;
  display: block;
  font-size: 20px;
  background: #ccc;
}
</style>
