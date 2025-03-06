<template>
  
      <v-dialog max-width="500">
        <template v-slot:activator="{ props: activatorProps }">
          <v-btn
            v-bind="activatorProps"
            color="surface-variant"
            text="Открыть диалог"
            variant="flat"
          ></v-btn>
        </template>

        <template v-slot:default="{ isActive }">
          <v-card title="Диалог">
            <v-card-text>
              
              <v-text-field 
              v-model="mes">
              </v-text-field>
              <v-text-field 
              v-model="mes2">
              </v-text-field>
            </v-card-text>

            <v-card-actions>
              <v-spacer></v-spacer>
              
              <v-btn @click="vyvod" text="вывод в консоль" />
              <v-btn
                text="Закрыть диалог"
                @click="isActive.value = false"
              ></v-btn>
            </v-card-actions>
          </v-card>
        </template>
      </v-dialog>
    
</template>


<script >
export default {
  name: "lab3_5",
  data(){
    return {
      mes:'123',
      mes2:'ipjl',

    }
  },
  methods:{
    vyvod(){
      console.log(this.mes,this.mes2)
    }
  }

};
</script>