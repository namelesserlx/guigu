<template>
  <div class="search">
    <input type="text">
    <button>搜索</button>
  </div>
</template>

<script>
export default {
    name:'Search',
}
</script>

<style lang="scss" scoped>
.search {
    position: absolute;
    // float: left;
    top: 24px;
    left:347px;
    width: 540px;
    height: 33px;
    border: 2px solid red;
    input {
        position: absolute;
        top: 1px;
        width: 455px;
        height: 31px;
    }
    button {
      position: absolute;
      
      // top: 1px;
      left: 455px;
      width: 86px;
      height: 33px;
      background-color: #b1191a;
      font-size: 18px;
      color: #ffffff;;
    }

}

</style>