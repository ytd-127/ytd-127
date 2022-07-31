<template>
  <div class="home">
    <bg></bg>
    <about></about>
    <job></job>
    <work></work>
    <log></log>

  </div>
</template>

<script>

import Bg from "./childComps/Bg.vue"
import About from "./childComps/Abot.vue"
import Job from "./childComps/Job.vue"
import Work from "./childComps/Work.vue"
import Log from "./childComps/Log.vue"

export default {
    name:"Home",
    components:{
        Bg,
        About,
        Job,
        Work,
        Log
    }
}
</script>

<style>
body{
	margin:0;
	max-width: 100%;
}

.xh{
	position: absolute;
	top: 100%;
	margin-top: -50px;
	width: 100%;
}
.xhtb{
	position: absolute;
	left: 50%;
	margin-left: -10px;
	border-right: 3px solid rgba(255,255,255,0.5);
    border-top: 3px solid rgba(255,255,255,0.5);
    height: 20px;
	width: 20px;
	-webkit-transform: rotate(135deg);
    transform: rotate(135deg);

}
.xhtb:hover{
	border-right: 3px solid rgb(255, 255, 255);
    border-top: 3px solid rgb(255, 255, 255);
	
}

h1{
	font-size:40px;
	color:rgb(255, 255, 255);
}
h2{
	font-size:20px;
	color:rgb(255, 255, 255);
	
}
h3 {
    font-size:30px;

}
#about,#work,#job,#log,#footer{
	position: relative;
	width: 100%;
	text-align: center;
	padding-top: 80px;
	padding-bottom: 100px;
    cursor:default;
    -webkit-user-select:none;
   -moz-user-select:none;
   -ms-user-select:none;
   user-select:none;
	
}
.hg1 {
	position: absolute;
	left: 50%;
	margin-left: -35px;
	margin-top: -30px;
	width: 70px;
	border-bottom: 4px solid #ffffff;
}
.hg {
	position: absolute;
	left: 50%;
	margin-left: -25px;
	margin-top: -10px;
	width: 50px;
	border-bottom: 3px solid #7299CC;
}
#work {
    background-color:rgb(255,255,255);


}
#job {
    background-color:rgb(245,245,245);
}
.aboutwz {
	position: relative;
	margin-top: 40px;
	width: 100%;
	font-size: 17px;
	background: white;

}
.aboutwz p{
	margin-top: 25px;
	color:rgb(90,90,90);

}

.bqbox{
	margin-top: 50px;

}
.bq {
    padding:10px;
    color:#646464;
    background:#f0f0f0;
}
.bq:hover {
    background:#989898;
    color:black;
    }
.worklist {
    position:relative;
	margin-top:50px;
	left: 10%;
	width: 80%;
}

.worklink {

	position: relative;
    display:inline-block;
    width:300px;
	height:250px;
	margin-top: 30px;
	margin-left: 15px;
	margin-right: 15px;
	margin-bottom: 30px;
	background: white;
	text-align: left;
	cursor: pointer;
	border-radius: 8px;
	overflow: hidden;
	box-shadow: 0 0 10px rgb(0 0 0/5%);
}
.worklink:hover{
	box-shadow: 0 0 30px rgb(0 0 0/20%);

}
.worklinkpic{
    position:absolute;
    width:100%;
    height:155px;
	background-size: cover !important;
}
#worklinkpic_a{

	background-size: cover;
}

.worklinktextbox {
    background-color:white;

}
.worklinktextbox{
	padding-left: 20px;
	padding-top: 165px;

}
.worklinktext1{
	font-size: 15px;
	line-height: 0px;
	font-weight: bold;
}
.worklinktext2{
	line-height: 25px;
	font-size: small;
	white-space: nowrap;

}
.worklinktext3{

	font-size: 11px;
    line-height: 5px;
    color: rgba(0,0,0,0.5);
}

#log{
	background-color: rgb(245, 245, 245);
}
#logbox{
	
	width: 100%;
}
.logone{
	display:inline-block;
	padding-left: 80px;
	padding-right: 80px;
}
#footer{
	background-repeat:no-repeat;
	background-size:cover;
	background-attachment:fixed;
}
.footerbox{
	display: inline-block;
	margin-left: 50px;
	vertical-align:top;

}
.footerbox a{
	display: block;
	text-decoration:none;
	color:white;

}
.footerbox a:hover{
	color:#7299CC ;

}
.footertt{
font-size: 17px;
color: white;
}
.footerbox img{
	width: 100px;
	height: 100px;

}

</style>