<template>
  <v-container>
    <v-row>
       <v-col cols="6">
        <!-- 顶部 Toggle 切换栏 | styles form: layout/_group.styl -->
        <v-btn-toggle mandatory>
          <v-btn color="transparent" width="12em">
            进行中
          </v-btn>
          <v-btn color="transparent" width="12em">
            已结案
          </v-btn>
        </v-btn-toggle>
        <!-- 顶部 Toggle -->
      </v-col>
      <!-- 栅格 -->
      <v-col cols="6">
        <v-row
          :align="alignment"
          :justify="justify"
          class="grey lighten-5"
        >
          <v-card
            v-for="n in 3"
            :key="n"
            class="ma-3 pa-6"
            outlined
            tile
          >
            Column
          </v-card>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
 export default {
    data:() => ({
      alignment:'center',
      justify: 'center'
    })
  }
</script>
