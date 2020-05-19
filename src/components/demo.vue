<template>
  <v-container>
    <v-row class="text-center" :style="{'color':color}">
      <v-col>1</v-col>
      <v-col>2</v-col>
      <v-col>3</v-col>
    </v-row>
    <v-row class="text-center">
      <v-col>4</v-col>
      <v-col>5</v-col>
      <v-col>6</v-col>
    </v-row>
  </v-container>
</template>

<script>
 export default {
   data () {
     return {
       
     }
   },
   props:{
     color:{
       type: String,
       default: 'red'
     }
   },
   methods: {

   }
 }
</script>

<style>

 
</style>


