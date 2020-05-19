<template>
  <v-container>
    <v-row>
       <v-col>
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
    </v-row>
  </v-container>
</template>

<script>
 export default {
    props: {
     
    },
  }
</script>
