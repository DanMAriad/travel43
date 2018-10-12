<template>
  <div class="header">
    <div class="header_left">
        左
    </div>
    <div class="header_input">
        中
    </div>
    <div class="header_right">
        右
    </div>
  </div>
</template>

<script>

export default {
  name: 'HomeHeader'
}
</script>

<style scoped>
.header{
    height: .86rem;
    line-height: .88rem;
    background-color: gold;
    display: flex;
}
.header_left{
    float: left;
    width: .6rem;
}.header_input{
    flex: 1;
    background-color: #ffffff;
    border-radius: 3px;
    height: .64rem;
    margin: .12rem;
    line-height: .64rem;
}.header_right{
    float: right;
}
</style>