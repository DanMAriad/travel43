<template>
  <div class="icnos">
  <div class="icon" v-for="item in inconList" :key="item.id">
    <div class="icon_img">
      <img class="icon_img_style" :src="item.imgUrl">
    </div>
    <p class="icon_desc"></p>
  </div>
  

</template>

<script>

export default{
  name: 'HomeIcons',
  data: function(){
      return {
        iconList: [{
          id:'1001',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png',
          desc: '景点门票'
        },{
          id:'1002',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png',
          desc: '景点门票'
        },{
          id:'1003',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png',
          desc: '景点门票'
        }]
      }
  }
  }
</script>

<style scoped>
.icnos{
  widows: 100%;
  height: 0;
  padding-bottom: 50%;

}
.icon{
  width: 25%;
  height: 0;
  padding-bottom: 25%;
  float: left;
  position: relative;
}
.icon_img{
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: .44rem;
}
.icon_desc{
  position: absolute;
  height: .44rem;
  left: 0;
  right: 0;
  bottom: 0;
  text-align: center;
  
}
.icon_img_style{
  height: 100%;
  display: block;
  margin: 0 auto;
}
</style>
