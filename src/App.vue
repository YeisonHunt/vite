<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hellooooo Vue 3.0 + Vite" />
  <Another />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Another from './components/Another.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Another
  }
}
</script>
