<template>
  <div>
    HelloWorld component
    {{ statefulSingleton }}
  </div>
</template>

<script>
import { useStatefulSingleton } from '../useStatefulSingleton'

export default {
  name: 'HelloWorld',
  setup() {
    return {
      ...useStatefulSingleton()
    }
  }
}
</script>
