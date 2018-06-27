<template>
<!-- 头部导航 -->
<header class="navbar">
<div class="main-conteinr">
<a href="#" class="logo">
<img src="https://cdn2.jianshu.io/assets/web/nav-logo-4c7bbafe27adc892f3046e6978459bac.png"/>
</a>
<!-- 导航栏 -->
<div class="navbar-content">
<ul>
  <li><a href="#" style="color:#ea6f5a">首页</a></li>
  <li><a href="#">下载App</a></li>
</ul>
</div>
<!-- 搜索内容 -->
<div class="search">
<form action="">
<input type="text" name="q" id="q" value="" autocomplete="off" placeholder="搜索" class="search-input" data-mounted="1">
<i class="icon iconfont icon-sousuo"></i>
</form>
</div>
<!-- 登录注册 -->
<div class="login">
<ul>
  <li><a href="#">登录</a></li>
  <li><a href="#">注册</a></li>
</ul>
</div>
</div>
</header>
</template>

<script>
export default {};
</script>

<style lang='scss'>
.navbar {
  width: 100%;
  height: 56px;
  background-color: #fff;
  margin-bottom: 20px;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1030;
  border: 1px solid #f0f0f0;
  .main-conteinr {
    width: 900px;
    margin: 0 auto;
    height: 56px;
    .logo {
      height: 56px;
      float: left;
      margin-left: -25px;
      padding: 0;
      img {
        height: 56px;
      }
    }
    .navbar-content {
      height: 56px;
      float: left;
      line-height: 56px;
      ul {
        display: inline-block;
        li {
          float: left;
          margin-right: 10px;
          a {
            padding: 15px;
            font-size: 17px;
            color: #333;
            text-decoration: none;
          }
        }
      }
    }
    .search {
      float: left;
      form {
        top: 9px;
        position: relative;
        input {
          padding: 0 40px 0 20px;
          width: 160px;
          outline: none;
          height: 38px;
          font-size: 14px;
          border: 1px solid #eee;
          border-radius: 40px;
          background: #eee;
        }
        .icon-sousuo {
          position: absolute;
          top: 13px;
          right: 5px;
          cursor: pointer;
          width: 30px;
          height: 30px !important;
          line-height: normal !important;
          padding: 0 !important;
          color: #969696 !important;
          text-align: center;
        }
      }
    }
    .login {
      float: right;
      ul {
        li {
          float: left;
          a {
            border: none;
            background: 0 0;
            color: #333;
            line-height: 56px;
            height: 50px;
            padding: 0 20px;
            margin: 0;
            text-align: center;
            display: inline-block;
            font-size: 14px;
          }
        }
      }
    }
  }
}
</style>
