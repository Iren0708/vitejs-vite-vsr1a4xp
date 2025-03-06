<script >
import { ref } from 'vue'
import HelloWorld from './components/HelloWorld.vue'
import lab3_1 from './components/Lab3/lab3_1.vue'
import lab3_2 from './components/Lab3/lab3_2.vue'
import lab3_3 from './components/Lab3/lab3_3.vue'
import lab3_4 from './components/Lab3/lab3_4.vue'
import lab3_5 from './components/Lab3/lab3_5.vue'
import lab3_6 from './components/Lab3/lab3_6.vue'
import lab3_7 from './components/Lab3/lab3_7.vue'

export default {
  components: {
    HelloWorld,
    lab3_1,
    lab3_2,
    lab3_3,
    lab3_4,
    lab3_5,
    lab3_6,
    lab3_7,
  }
}
</script>

<template>
  <HelloWorld msg="Vite + Vueeee" />
  <lab3_1 />
  <lab3_2 />
  <lab3_3 msg=""/>
  <lab3_4 msg=""/>
  <lab3_5 />
  <lab3_6 msg=""/>
  <lab3_7 msg=""/>
</template>

<style scoped>

</style>
