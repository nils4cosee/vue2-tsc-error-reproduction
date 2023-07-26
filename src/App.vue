<template>
  <div>
    Range: {{range.min}} - {{range.max}}
  </div>
</template>

<script lang="ts">

import Vue, {ref} from "vue";


export default Vue.extend({
  name: "App",
  setup() {
    const range = ref({min: 0, max: 10})
    return {
      range
    }
  }
})
</script>

