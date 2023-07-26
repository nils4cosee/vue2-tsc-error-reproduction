<template>
  <div>
    Range: {{ range.min }} - {{ range.max }}
  </div>
</template>

<script setup lang="ts">

import {ref} from "vue";

const range = ref({min: 0, max: 10})

</script>

