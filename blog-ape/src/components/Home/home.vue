<template>
<!-- 首页 -->
<div class="home">
<div class="h-left">
<ContentLeft></ContentLeft>
</div>
</div>
</template>

<script>
import ContentLeft from './Hcontent/ContentL.vue';
export default {
components:{
  ContentLeft
}
};
</script>

<style lang='scss'>
.home{
  width: 900px;
  // border: 1px solid red;
  margin: 78px auto;
  .h-left{
    float: left;
    width: 660px;
  }
}
</style>
