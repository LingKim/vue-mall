<template>
     <h1>
       jenkins构建项目成功
     </h1>
</template>

<script>
	export default {
		name: "ShoppingMall",
    data (){
		  return {
		    locationIcon:require('../../assets/images/location.png'),
        bannerPicArray: [
          {imageUrl:'http://7xjyw1.com1.z0.glb.clouddn.com/simleVueDemoPic001.jpg'},
          {imageUrl:'http://7xjyw1.com1.z0.glb.clouddn.com/simleVueDemoPic002.jpg'},
          {imageUrl:'http://7xjyw1.com1.z0.glb.clouddn.com/simleVueDemoPic003.jpg'},
        ]
      }
    }
	}
</script>

<style scoped>
  .search-bar {
    height: 2.2rem;
    background-color: #e5017d;
    line-height: 2.2rem;
    overflow: hidden;
  }

  .search-input {
    width: 100%;
    height: 1.3rem;
    border-left:0;
    border-right: 0;
    border-top:0;
    border-bottom: 1px solid #fff !important;
    background-color: #e5017d;
    color: #fff;
  }

  .location-icon {
    width: 80%;
    padding-top: .2rem;
    padding-left: .3rem;
  }

  .search-button {
    margin-left: .5rem;
  }

  .swipe-area {
    clear: both;
    max-height: 15rem;
    overflow: hidden;
  }
</style>







