<template>
  <div class="home">
    {{info.name}}
    {{info.age}}
  </div>
</template>

<script lang="ts">
import { ref, defineComponent } from '@vue/composition-api'

export default defineComponent({
  setup() {
    const info = ref({
      name: 'andy',
      age: 28
    })
    return {
      info
    }
  }
})

</script>
