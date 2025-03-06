<template>
  
  
  <v-container>
    <v-row justify="center">
      <v-date-picker width="400" v-model="date"></v-date-picker>
    </v-row>
  </v-container>

</template>

<script>
  export default {
  name: "lab3_3",
  data () {
    return {
      date: new Date(),
    }
  },
  methods: {}
}
</script>