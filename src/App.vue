<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
  {{ statefulSingleton }}
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import { useStatefulSingleton } from './useStatefulSingleton'
export default {
  name: 'App',
  components: {
    HelloWorld
  },
  setup() {
    return {
      ...useStatefulSingleton()
    }
  }
}
</script>
