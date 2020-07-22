<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld :msg="msg?.test?.foo" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  setup() {
    return {
      msg: {
        test: null
      }
    }
  }
}
</script>
