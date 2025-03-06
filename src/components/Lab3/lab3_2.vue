<template>
  <div>
<p>Ваше число: {{ chvst }}</p>
  <v-text-field label="Число возводимое в степень"
 v-model="chvst"></v-text-field>
<p>Ваша степень: {{ step }}</p>
<v-text-field label="Cтепень"
v-model="step"></v-text-field>


<p>Итог: {{ itog }}</p>
</div>
</template>


<script>
export default {
  name: "lab3_2",
  data () {
    return {
      value: null,
      step: null,
    }
  },
  computed:{
    itog(){
      return Math.pow(this.chvst, this.step);
    }
  },
  

};
</script>


<style scoped>
p {
  padding: 20px;
}
</style>