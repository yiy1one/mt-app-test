<template>

  <el-row :gutter="0" class="m-header">
    <el-col :span="5">
      <Geo/>
    </el-col>

    <el-col :span="5">
      <User/>
    </el-col>

    <el-col :span="14">
      <Navbar/>
    </el-col>

  </el-row>

</template>

<script>
import Geo from './geo'
import Navbar from './nav'
import User from './user'
export default {
  components:{
    Geo,
    User,
    Navbar
  }
}
</script>

<style lang="scss">
  


</style>
