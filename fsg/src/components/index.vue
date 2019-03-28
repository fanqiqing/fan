<template>
	<div class="aspectratio">
    <div class="aspectratio-content">
		<div class="main">烘焙</div>
		<div class="main1">
		<div class="ma"><img src="../assets/tu.gif" width="100%" height="100%"></div>
		<div class="ma1"><img src="../assets/tu1.gif" width="100%" height="100%"></div>
		<div class="ma2"><input type="text" placeholder="搜索    菜谱/食材"></div>
		</div>
		<div class="main2">
			<ul class="ma3">
				<li>早餐</li>
				<li>甜点</li>
				<li>午餐</li>
				<li>晚餐</li>
			</ul>
			<ul class="ma3">
				<li>烘焙</li>
				<li>家常菜</li>
				<li>中式点心</li>
				<li>全部分类</li>
			</ul>
		</div>
		<div class="main3">专辑推荐</div>
		<div><img src="../assets/tu3.gif"></div>
		<div><img src="../assets/tu4.gif"></div>
		<div><img src="../assets/tu5.gif"></div>
		<div><img src="../assets/tu6.gif"></div>
		<div><img src="../assets/tu7.gif"></div>
		<div><img src="../assets/tu8.gif"></div>
		<div class="main4">
			<li><img src="../assets/tu9.gif" /></li>
			<li><img src="../assets/tu10.gif" /></li>
			<li><img src="../assets/tu11.gif" /></li>
			<li><img src="../assets/tu12.gif" /></li>
		</div>
	</div>
</div>
</template>

<style>
	.main{
		font-size: 24px;
		margin-top: 22px;
	}
	.main1{
		float: left;
		width: 750px;
		margin-top: 32px;
		content: none; 	
	}

	.ma{
		width: 229px;
		height: 180px;
		float: left;
		margin-left: 140px;
	}
	.ma1{
		width: 229px;
		height: 180px;
		float: left;
		margin-left:12px;
	}
	.ma2 input{
		width: 475px;
		height: 57px;
		margin-top: 38px;
		font-size: 30px;
		text-align: center;
	}
	.main2{
		width: 70%;
		margin-left: 15%;
		height: 150px;
		float: left;
		margin-top:10px;
	
	}
	.main2>ul {
		margin-top: 20px;
	}
	.main2 li{
		list-style: none;
		font-size: 20px;
		color: 757575;
	}
	.ma3{
		display: flex;
	}
	.ma3 li {
		flex: 1;
	}
	.main3{
		width: 750px;
		float: left;
		font-size:20px ;
	}
	.main4{
		display: flex;
		width: 550px;
		margin-left: 100px;
	}
	.main4 li{	
		flex: 1;
	}
	</style>