<template>
   <!-- 页面的图集1部分 -->
  <div id="hello">
	 <div class="container">
		<div class="star_top">
			<p id="til1">图集1</p>
		</div>
		<ul>
			<li>
				<div>
					<img src="../img/view1.png">
				</div>
				<h2>VIEW</h2>
				<p>蔚蓝的天，翠绿的山</p>
				<p class="money">&yen;9.9 付费下载 <span></span></p>
			</li>
			<li class="line"></li>
			<li>
				<div>
					<img src="../img/view1.png">
				</div>
				<h2>VIEW</h2>
				<p>蔚蓝的天，翠绿的山</p>
				<p class="money">&yen;9.9 付费下载 <span></span></p>
			</li>
			<li class="line"></li>
			<li>
				<div>
					<img src="../img/view1.png">
				</div>
				<h2>VIEW</h2>
				<p>蔚蓝的天，翠绿的山</p>
				<p class="money">&yen;9.9 付费下载 <span></span></p>
			</li>
			<li class="line"></li>
			<li>
				<div>
					<img src="../img/view1.png">
				</div>
				<h2>VIEW</h2>
				<p>蔚蓝的天，翠绿的山</p>
				<p class="money">&yen;9.9 付费下载 <span></span></p>
			</li>
		</ul>
	</div>
</div>
</template>

<script>
export default {
  name: 'hello',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.container{
	width: 1280px;
	margin: 0px auto;
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
#hello {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}
#hello{
	height: 700px;
	width: 100%;
	background-color: #F2F2F2;

}
#hello .star_top{
	text-align: center;
	margin: 10px;
	color: #006000;
	font-size: 40px;
	background-color: #F2F2F2;
}
#til1{
	text-align: center;
	margin: 10px;
	color: #006000;
	font-size: 40px;
	background: url("../img/view8.jpg") repeat-x 0px -96px;
	background-size: cover;
}
#hello ul{
	width: 1263px;
	margin: 10px auto;
}
#hello li{
	width: 300px;
	float: left;
	border-bottom: 4px solid #DFDFDF;
	transition: all .3s;
}
#hello li:hover{
	border-bottom: 4px solid #4FB59D;
	transform: translateY(-10px);
}
#hello li img{
	width: 300px;
}
#hello li h2{
	text-align: center;
	margin-top: 10px;
}
#hello li p{
	text-align: center;
	margin: 10px 0px; 
	font-size: 12px;
	color: #BDBDBD;
}
#hello .money{
	color: #00925F;
	font-size: 14px;
}
#hello li span{
	width: 13px;
	height: 13px;
	display: inline-block;
	vertical-align: middle;
	background: url("../img/icons-1.png") no-repeat -177px -1014px;
}
#hello .line{
	width: 0px;
	height: 450px;
	border-left: 1px solid #EAEAEA;
	margin: 0px 10px;
}

</style>
