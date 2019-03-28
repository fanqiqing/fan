<template>
	<div class="aspectratio">
		<div class="aspectratio-content">
			<div class="main"><input type="text" placeholder="搜索    菜谱/食材"></div>
			<div class="main1">热门分类</div>
			<div class="main2">
			<li><img src="../assets/tu13.gif" width="85%"></li>
			<li><img src="../assets/tu14.gif" width="85%"></li>
			<li><img src="../assets/tu15.gif" width="85%" ></li>
			<li><img src="../assets/tu16.gif" width="85%"></li>
			</div>
			<div class="main1">一日三餐</div>
			<div class="main2">
			<li><img src="../assets/tu13.gif" width="85%"></li>
			<li><img src="../assets/tu14.gif" width="85%"></li>
			<li><img src="../assets/tu15.gif" width="85%" ></li>
			<li><img src="../assets/tu16.gif" width="85%"></li>
			</div>
		</div>
	</div>
</template>

<script>
</script>

<style>
	.main input{
		width: 700px;
		height: 57px;
		margin-top: 38px;
		font-size: 30px;
		text-align: center;
	}
	.main1{
		font-size: 24px;
		margin-top: 22px;
	}
	.main2{
		display: flex;
		width: 750px;
		margin-top: 30px;
	}
	.main2 li{	
		flex: 1;
	}
</style>
