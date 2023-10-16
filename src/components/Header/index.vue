<template>
    <div>
        <div class="header">
        <div class="main">
            <div class="left">
                <span>品优购欢迎您！</span> &nbsp; <a>请登录</a> &nbsp; <a href="#">注册</a>
            </div>
            <div class="right">
                <ul>
                    <li><a href="#">我的订单</a></li>
                    <li>|</li>
                    <li><a href="#">我的品优购&nbsp; <i class="el-icon-arrow-down"></i></a></li>
                    <li>|</li>
                    <li><a href="#">品优购会员</a></li>
                    <li>|</li>
                    <li><a href="#">企业采购&nbsp; <i class="el-icon-arrow-down"></i></a></li>
                    <li>|</li>
                    <li><a href="#">客户服务 &nbsp; <i class="el-icon-arrow-down"></i></a></li>
                    <li>|</li>
                    <li><a href="#">网站导航&nbsp; <i class="el-icon-arrow-down"></i></a></li>
                </ul>
            </div>
        </div>
        
    </div>
    <div class="center">
        <Logo></Logo>
        <Search></Search>
        <HotKey></HotKey>
        <Shoop></Shoop>
    </div>
    </div>
    
  
</template>

<script>


import Logo from './Logo.vue';
import Search from './Search.vue';
import HotKey from './HotKey.vue';
import Shoop from './Shoop.vue';
export default {
    name:'Header',
    components:{Logo,Search,HotKey,Shoop}
}
</script>

<style lang="scss" scoped>
.header {
    width: 100%;
    height: 30px;
    background: #f1f1f1;
    .main {
        // float: left;
        width: 1200px;
        margin: 0 auto;         
        line-height: 30px;
        
        justify-content: space-between;
        
        .left {
            float: left;
        }
        .right {
            float: right;
        }
        
        >a{
            color: #c81623;
        }
        li {
            display: inline;
            // height: 100%;
            line-height: 30px;
        }
        li:nth-child(even) {
            margin: 5px 10px;
        }
    }
}
.center {
        position: relative;
        width: 1200px;
        height: 105px;
        margin: 0 auto;
        // background: pink;
}
</style>