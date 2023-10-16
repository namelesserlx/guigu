<template>
  <div class="logo">
    <h1><a href="#" title="品优购">品优购</a></h1>
  </div>
</template>

<script>
export default {
    name:'Logo'
}
</script>

<style scoped lang="scss">
.logo {
    position: absolute;
    top: 25px;
    
    width: 175px;
    height: 56px;
    a {
      display: block;
      width: 175px;
      height: 56px;
      font-size: 0;
      background: url(../../../public/images/logo.png);
    }
}

</style>