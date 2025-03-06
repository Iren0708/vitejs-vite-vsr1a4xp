<template>
<p>Ваше число: {{ chvst }}</p>
  <v-text-field label="Число возводимое в степень"
type="int" v-model="chvst"></v-text-field>
<p>Ваша степень: {{ step }}</p>
<v-text-field label="Cтепень"
type="int" v-model="step"></v-text-field>


<p>Итог: {{ itog }}</p>
</template>


<script>
export default {
  name: "lab3_2",
  data () {
    return {
      chvst: '',
      step: '',
      itog: '',
    }
  },
  methods: {
    input: function() {

    },
    chislo(){
      this.chvst = 0;
    },
    stepp(){
      this.step = 0;
    },
    it(chvst,step){
      this.itog = Math.pow(chvst,step);
    },
  }
};
</script>


<style scoped>
p {
  padding: 20px;
}
</style>