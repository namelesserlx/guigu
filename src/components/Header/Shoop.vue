<template>
    <div class="shoop">
       <a href="#"> <i class="el-icon-shopping-cart-1"></i>
        <span>我的购物车</span></a>
    </div>
  
</template>

<script>
export default {
    name:'Shoop'
}
</script>

<style lang="scss" scoped >
.shoop {
    position: absolute;
    top: 25px;
    right: 64px;
    width: 140px;
	height: 36px;
	background-color: #f7f7f7;
	border: solid 1px #dfdfdf;
    line-height: 36px;
    i {
        margin: 0 5px 0 15px;
    }
//    padding: 0 10px;
}
</style>