<template>
  <div>
    {{ title }}
  </div>
</template>

<script>
import { ref } from 'vue'
export default {
  setup() {
    const title = ref('title')
    return {
      title
    }
  }
}
</script>

<style lang="scss" scoped></style>
