
<template>
  <div id="app">
  <!-- 页面的顶部 -->
    <div id="top">
	  <div class="container"></div>
    </div>
	<!-- 页面的头部 -->
	<div id="header">
	    <ul class="right">
			<li><a href="#">NULL</a></li>
			<li><a href="#">NULL</a></li>
		</ul>
	</div>
	<!-- 页面的导航 -->
    <div id="nav">
	 <div class="container">
		<div class="logo left">
			<p id="log">NM$L</p>
		</div>
		<ul class="right">
			<li><router-link v-bind:to="'/'">图集1Home</router-link></li>
			<li><router-link v-bind:to="'/pick'">图集2About</router-link></li>
			<li><router-link v-bind:to="'/about'">登录</router-link></li>
		</ul>			
	    </div>
     </div>
	 <router-view></router-view>
	 <div id="footer">
	<div class="container">
		<p>
			<img src="../img/i-f-logo.png">
			<span>@2020 成都市1202007</span>
			<a href="#">版权说明</a>
			<a href="#">作者介绍</a>
			<a href="#">返回顶部</a>
			
		</p>
	</div>
</div>
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>
<!-- css格式 -->
<style>
*{
	margin: 0;
	padding: 0;
	font-size: 14px;
}
.left{
	float: left;
}
.right{
	float: right;
}
.container{
	width: 1280px;
	/*border: 1px solid #f00;*/
	margin: 0px auto;
}
ol,ul{
	list-style-type: none;
}
a{
	color: #666;
	text-decoration: none;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
   background: #eee;    
   font-size: 14px;
   color: #000;
   margin: 0;
   padding: 0;
}
#top{
	height: 5px;
	background-color: #00925F;
}
#header{
	height: 30px;
	background-color: #2D2D2D;
}
#header .header_left div{
	float: left;
	margin: 5px 10px 0px;
}
#header ul li{
	float: left;
	line-height: 30px;
}
#header li a{
	color: #B2B2B2;
	font-size: 14px;
	border-right: 1px solid #B2B2B2;
	padding: 0px 15px;
}
#header li a:hover{
	color: #00925F;
}
#nav{
	height: 90px;
	background: url("../img/view7.jpg") repeat-x 0px -96px;
	background-size: cover;
}
#log{
	color: #006000;
	font-size: 40px;
	margin: 5px 100px;
	padding: 10px 10px;
	border: 2px solid #FF9D6F;
	border-radius: 15px;
}
#nav li{
	float: left;
	margin: 0px 15px;
	line-height: 90px;
}
#nav li a{
	color: #666666;
	font-weight: bold;
}
#nav li a:hover{
	color: #00925F;
}
#footer{
	height: 40px;
	background-color: #2D2D2D;
}
#footer p{
	line-height: 40px;
}
#footer img{
	margin-left: 20px;
}
#footer p span{
	color: #828282;
	margin: 0px 430px 0px 20px;
}
#footer p a{
	color: #fff;
	margin: 0px 10px;
}
#footer p a:hover{
	color: #00925F;
}
</style>

