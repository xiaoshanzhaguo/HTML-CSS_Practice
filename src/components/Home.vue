<template>
  <div class="hello">
    <div class="header">
        <div class="header_left">
            <ul>
                <li><a href="#">小米商城</a></li>
                <li><a href="#">MIUI</a></li>
                <li><a href="#">IoT</a></li>
                <li><a href="#">云服务</a></li>
                <li><a href="#">天星数科</a></li>
                <li><a href="#">有品</a></li>
                <li><a href="#">小爱开放平台</a></li>
                <li><a href="#">企业团购</a></li>
                <li><a href="#">资质证照</a></li>
                <li><a href="#">协议规则</a></li>
                <li><a href="#">下载app</a></li>
                <li><a href="#">Select Location</a></li>
            </ul>
        </div>
        <div class="header_right">
            <ul>
                <li><a href="#">登录</a></li>
                <li><a href="#">注册</a></li>
                <li><a href="#">消息通知</a></li>
            </ul>
            <div class="shopCar">
                <a href="#">
                    <i class="iconfont icon-gouwuchekong"></i>
                    <span>购物车</span>
                    <span>(0)</span>
                </a>
                <div class="white-area">购物车中还没有商品，赶紧选购吧！</div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
@import '../assets/css/index.css';
@import '../assets/css/home.less';
</style>
