<template>
    <div class="home-bg">
        <div id="top"></div>
        <div id="topbg"></div>
        <div class="xh">
            <a href="#about" class="xhtb"></a>
        </div>
        <div id="toptt">
            <div class="wxtx" id="wxtxx"></div>
            <h1>record my life</h1>
            <h2>/*这是127的个人主页*/</h2>
        </div>
    </div>
</template>

<script>
export default {
    name:"Bg"
}
</script>

<style>
.home-bg{
	width:100%;
	height:100vh;
	background-repeat:no-repeat;
    background: url(assets/images/bg/bg.jpg) no-repeat;
	background-size:cover;
	background-attachment:fixed;
}
#toptt{
	position:absolute;
	top:35%;
	width:100%;
	text-align:center;
	cursor:default;
    -webkit-user-select:none;
   -moz-user-select:none;
   -ms-user-select:none;
   user-select:none;
}
.wxtx{
    background: url(assets/images/bg/life.gif);
	width: 150px;
	height: 150px;
	border-radius: 50%;
	overflow: hidden;
	background-size:cover;
	margin: 0 auto;
}
</style>