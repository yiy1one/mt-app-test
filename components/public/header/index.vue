<template>

  <el-row :gutter="15" calss="m-header">
    <el-col :span="6">
      <Geo/>
    </el-col>
    <el-col :span="6"></el-col>
    <el-col :span="6"></el-col>
  </el-row>

</template>

<script>
import Geo from './geo'
import Nav from './nav'
export default {
  components:{
    Geo
  }
}
</script>

<style lang="scss">
  @import "@/assets/css/public/layout.scss";

</style>
