<template>
  <v-container fluid>
    <p>{{ selected }}</p>
    <v-checkbox
      v-model="selected"
      label="Эдвард"
      value="Эдвард"
    ></v-checkbox>
    <v-checkbox
      v-model="selected"
      label="Джейкоб"
      value="Джейкоб"
    ></v-checkbox>
  </v-container>
</template>


<script>
export default {
  name: "lab3_7",
  }
import { ref } from 'vue'

  const selected = ref(['John'])
</script>