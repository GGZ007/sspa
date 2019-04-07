<template>
  <div id="pick">
   <div class="container">
		<div class="acc_top">
			<p id="til2">图集2</p>
		</div>
		<div class="acc_main">
			<div class="acc_left left">
				<div>
					<img src="../img/20150413174400N0dPnxUKHk.jpg">
				</div>
				<div class="acc_all">
					<p>OPPO手机官网AAESSORY配件</p>
					<ul>
						<li>nice</li>
						<li>nice</li>
						<li>nice</li>
						<li>nice</li>
						<li>nice</li>
						<li>nice</li>
					</ul>
					<h2 class="line"></h2>
					<p class="acc">全部<span></span></p>
				</div>
				<div>
					<img src="../img/20131120165101xYIYzhkVEy.jpg">
				</div>
				<div>
					<img src="../img/20150413174340NLV2gvV4FU.jpg">
				</div>
			</div>
			<div class="acc_right right">
				<div>
					<img src="../img/20150123182505RO822scYYt.jpg">
				</div>
				<div>
					<img src="../img/20141230145609l7Fsk7CdHy.jpg">
				</div>
				<div>
					<img src="../img/20141011101157yZEFpMrk0h.jpg">
				</div>
				<div>
					<img src="../img/201410270957132inlm3IwsV.jpg">
				</div>
			</div>
		</div>
	</div>
  </div>
</template>

<script>
export default {
  name: 'pick'
}
</script>
<style>
.container{
	width: 1280px;
	/*border: 1px solid #f00;*/
	margin: 0px auto;
}
.left{
	float: left;
}
.right{
	float: right;
}
#pick {
   font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}
#til2{
	text-align: center;
	margin: 10px;
	color: #006000;
	font-size: 40px;
	/*background-color: #7CFC00;*/
	background: url("../img/view9.png") repeat-x 0px -96px;
	background-size: cover;
}
#pick{
	height: 950px;
	background-color: #F6F6F6;
	overflow: hidden;
}

#pick .acc_top{
	text-align: center;
	margin: 20px 0px;
}


#pick .acc_main{
	width: 1090px;
	margin: 10px auto;
}
#pick .acc_left{
	width: 540px;
	height: 950px;
	/*border: 2px solid #000;*/
}
#pick .acc_left>div{
	float: left;
	border-bottom: 3px solid #EAEAEA;
	margin: 10px;
	transition: all .3s;
}
#pick .acc_left>div:hover{
	border-bottom: 3px solid #00925F;
	transform: translateY(-10px);
}
#pick .acc_left img{
	width: 250px;
}
#pick .acc_left>div:last-child img{
	width: 520px;
}
#pick .acc_all{
	width: 250px;
	height: 250px;
	border: 3px solid #EAEAEA;
	background-color: #fff;
	padding: 20px;
	box-sizing: border-box;
}
#pick .acc_all p:first-child{
	text-align: center;
	font-weight: bold;
	font-size: 14px;
	border-bottom: 1px solid #ccc;
	padding-bottom: 10px;
}
#pick .acc_all li{
	float: left;
	width: 100px;
	height: 40px;
	text-align: center;
	line-height: 40px;
}
#pick .acc_all li:hover{
	color: #00925F;
}
#pick .acc_all .line{
	width: 150px;
	height: 0;
	border-top: 1px solid #ccc;
	clear: both;
	margin: 15px auto;
}
#pick .acc_all p:last-child{
	text-align: center;
}
#pick .acc_all p:last-child:hover{
	color: #00925F;
}
#pick .acc_all span{
	width: 13px;
	height: 13px;
	display: inline-block;
	vertical-align: middle;
	background: url("../img/icons-1.png") no-repeat -177px -1014px;
	margin-left: 10px;
}
#pick .acc_right{
	width: 540px;
}
#pick .acc_right div{
	float: left;
	margin: 10px;
	border-bottom: 3px solid #EAEAEA;
	transition: all .3s;
}
#pick .acc_right div:hover{
	border-bottom: 3px solid #00925F;
	transform: translateY(-10px);
}
#pick .acc_right img{
	width: 250px;
}
#pick .acc_right div:first-child img{
	width: 520px;
	height: 250px;
}
#pick .acc_right div:last-child img{
	height: 241px;
}

</style>
