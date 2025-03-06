<template> 
  <v-text-field 
  label="Email address"
  placeholder="johndoe@gmail.com"
  hint="Введите акутальную почту"
  type="email">
  </v-text-field>
  <input type="text" v-model="message1">
  <p>Ваше сообщение: {{ message1 }}</p>
<button @click="message">Изменить соо</button>
</template> 


<script >
export default {
  name: "lab3_1",
  data () {
    return {
      message1: "Hi, vue!"
    }
  },
  methods: {
    message(){
      this.message1 = ' Соо изменено'
    }
  }
};
</script>

<style scoped>

</style>