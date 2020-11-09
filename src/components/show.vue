<template>
    <el-carousel height="410px" id="show" >
      <el-carousel-item v-for="item in 4" :key="item">
        <h3 class="small"> </h3>
      </el-carousel-item>
      <div class="Test" >
      </div>
    </el-carousel>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('../assets/css/show.css');
</style>
