<template>
    <nav-top>
        <div slot="dhwz-left"><img class="dhlogo" src="~assets/images/nav/logo.png" alt=""></div>
        <div class="dhbox" id="dhboxx"  slot="dhwz-right">
            <nav-top-item path="/home">
                <div slot="item-text">首页</div>
            </nav-top-item>
            <nav-top-item path="/my">
                <div slot="item-text">关于我</div>
            </nav-top-item>
            <nav-top-item path="/home">
                <div slot="item-text"></div>
            </nav-top-item>
            <nav-top-item path="/home">
                <div slot="item-text">首页</div>
            </nav-top-item>
        </div>
    </nav-top>
</template>


<script>
import NavTop from "components/common/navtop/NavTop"
import NavTopItem from "components/common/navtop/NavTopItem"

export default {
    name:"MainNav",
    components:{
        NavTop,
        NavTopItem
    }
}
</script>

<style>

.topdh{
	position:fixed;
	width: 100%;
	top:0px;
	z-index: 9999999;
	height: 85px;
}
.dhwz{
	margin-top: 35px;

}

.dhbox{
	position: absolute;
	top: 30px;
	text-align:center;
	right: 200px;
}
.dhfont{
	text-decoration:none;
	color:rgb(255, 255, 255);
	margin-left: 40px;
	font-size: 16px;
}
.dhfont:hover{
	border-bottom:2px solid black;
}
.dhlogo{
	position: absolute;
	left: 200px;
	width:220px;
	height:60px;
	top: 12px;
}
</style>