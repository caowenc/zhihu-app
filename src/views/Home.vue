<template>
<div>
  <div class="container">
  	<div class="nav gutter">
  		<div class="nav-bar">
  				<ul class="nav-list flex-left">
  					<li class="nav-item"><router-link to="/home/recommoned">推荐</router-link></li>
  					<li class="nav-item"><router-link to="/home/follow">关注</router-link></li>
  					<li class="nav-item"><router-link to="/home/hot">热榜</router-link></li>
  				</ul>				
  		</div>
  	</div>
  	<router-view />
  </div>
</div>
</template>

<script>



</script>
<style lang="scss" scoped>
	.router-link-active{
		border-bottom: 2px solid blue;	
		color: black;
	}
	.gutter{
		position: relative;
		margin-bottom: 10px;
	}
</style>
