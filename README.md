# task6*{margin: 0;padding: 0;}

.header{
	width: 100%;
	height: 60px;
	background-color: #5ac0ce;
	position: fixed;
	left: 0;
	top: 0;
	z-index: 10;
}
.midle_box{
	width: 30%;
	height: 48px;
	position: absolute;
	margin: 0 auto;
	padding-top: 4px;
	position: absolute;
	display: inline-flex;
	transform: translateX(120%);
	
}
	.a{background:  #6acdfe;color:white;width: 45%;height:80%;  border-radius: 8px;text-align: center;padding-top: 3%; 
		font-size: 150%;z-index:1;position:absolute;}
	.b{background:#ffffff;width: 45%;height:80%;left:40%;border-radius: 8px;text-align: center;padding-top: 3%; 
		font-size: 150%;color: #5ac0ce; position:absolute;z-index:2;}

.footer{
	width: 100%;
	display: flex;
	height: 74px;
	justify-content: space-around;
	background-color: #f9fafc;
	position: fixed;
	bottom: 0;
	left: 0;
	z-index: 10;
}

.choose{
	width: 100%;
	border-bottom: 1px solid gray;
	display: flex;
}
	.dropdown1{
		width: 33%;
		height: 65px;
		border-right: 1px solid gray;
		display: flex;
		align-items: center;
	}
	.dropdown2{
		width: 33%;
		height: 65px;
		border-right: 1px solid gray;
		display: flex;
		align-items: center;
	}
	.dropdown3{
		width: 33%;
		height: 65px;
		border-right: 1px solid gray;
		display: flex;
		align-items: center;
	}
	
	.btn-info{
		
		flex: 1;
		font-size: 20px;
		outline: none;
		background-color:transparent;
        border-style:none;

            position: relative;
    display: inline-block;
    width: 150px;
    height: 25px;
	}
	.caret{
		
		cursor: pointer; 
		float: right;
		margin-right: 10px;
	        transform: translateY(300%);
	    border-top: 4px dashed; 
	    border-right: 4px solid transparent;
	    border-left: 4px solid transparent;
		
	}
	.select1{
		font-size: 20px;
		outline: none;
		border: none;
		flex: 1;
	}
	.cur-select{
		    position: absolute;
    display: block;
    width: 150px;
    height: 25px;
    line-height: 25px;
    background: #f80 url(ico-arrow.png) no-repeat 125px center;
    text-indent: 10px;
	}
	.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
}

	.big_box{
		width: 100%;
		position: relative;
		top: 40px;
		/*border: 1px solid gray;*/
	}
	.content{
		width: 100%;
		/*border: 1px solid #ff5841;*/
	}
	.service_date{
		width: 100%;
		padding-top: 15px;
		color: gray;
	}
	.service_time{
		width:70%;float:left;font-size: 18px; overflow: hidden;text-overflow: ellipsis;white-space: nowrap;
	}
	.price{
		width:30%;color: red;
		margin-bottom: 5px; 
		float:left;
		font-size: 18px;
		margin-right:0px;
		overflow: hidden;text-overflow: ellipsis;white-space: nowrap;
		
	}
	.location{
		width: 100%;
		padding-top: 20px;
		color: gray;
		padding-bottom: 15px;
		border-bottom: 1px solid black;
	}

	.big_locate{
		width:48px;
		height:48px;/*给元素设置宽高*/
		float: right;
		display: inline-flex;
		background:url("sprite.png") scroll 0px 0px no-repeat transparent;/*引入雪碧图*/
		transform: scale(0.5);
	}
	.calendar_pic{
		width:42px;
		height:35px;/*给元素设置宽高*/
		background:url("sprite.png") scroll 0px 0px no-repeat transparent;/*引入雪碧图*/
		background-position: 12px -240px;
		transform: scale(0.7);
		float: left;
		margin-right: 6px;
	}
	.locat_pic{
		width:42px;
		height:35px;/*给元素设置宽高*/
		background:url("sprite.png") scroll 0px 0px no-repeat transparent;/*引入雪碧图*/
		background-position: 14px -144px;
		transform: scale(0.8);
		float: left;
		margin-right: 4px;
	}
	.float_box{
		float: left;
	}
	.home_box{
		width:50px;
		height:50px;/*给元素设置宽高*/ 
		background:url("sprite.png") scroll 0px 0px no-repeat transparent;/*引入雪碧图*/
		background-position: 0px -79px;
		transform: scale(0.7) ;
		
	}
	.write_box{
		width:100px;
		height:100px;/*给元素设置宽高*/
		background:url("sprite.png") scroll 0px 0px no-repeat transparent;/*引入雪碧图*/
		background-position: 0px -300px;
		transform: scale(0.75) translateY(-20%) ;

		
	}
	.man_box{
		width:50px;
		height:50px;/*给元素设置宽高*/
		background:url("sprite.png") scroll 0px 0px no-repeat transparent;/*引入雪碧图*/
		background-position: -70px 0px;
		transform: scale(0.7) ;
	}
	.p1{
		color: #8accd4;
		padding-left:9px;
		transform: translateY(-10%);
	}

	.p2{
		color: gray;
		padding-left:10px;
		transform: translateY(-10%);
	}


.btn-select {
position: relative;
display: inline-block;
height: 25px;
width: 100%;
text-align: center;
font: 20px "Microsoft YaHei";

}

.btn-select .cur-select {
position: absolute;
display: block;
width: 150px;
height: 25px;
line-height: 25px;
background: #f80 url(ico-arrow.png) no-repeat 125px center;
text-indent: 10px;
}

/*.btn-select:hover .cur-select {
background-color: #f90;
}*/

.btn-select select {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 25px;
opacity: 0;

font: 20px "Microsoft YaHei";
color: #f80;
}

/*.btn-select select option {
text-indent: 10px;
}

.btn-select select option:hover {
background-color: #f80;
color: #fff;
}
*/
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width,minimum-scale=1.0,maximum-scale=1.0,user-scalable=no">
	<link rel="stylesheet" type="text/css" href="task6.css">
	
	<title>task6</title>
<script type="text/javascript">
	window.onload=function(){
		
	};
</script>>
</head>
<body>
	<div class="header">
		<div class="midle_box"><div class="a" >找雇主</div><div class="b">找护工</div></div>
		<div class="big_locate"></div>
	</div>
	
	<div class="big_box">
		<div class="choose">
		<div class="dropdown1">
		<a class="btn-select" id="btn_select0">
           
            <span>所在地</span> <span class="caret"></span>           
            <select class="select1">
				<option>北京</option>
				<option>上海</option>
				<option>广州</option>
				<option>深圳</option>
				<option>选项五</option>
			</select></a>
		</div>

       
		<div class="dropdown2"><a class="btn-select" id="btn_select1">
           
            <span>食宿</span> <span class="caret"></span>           
            <select class="select1">
				<option>选项一</option>
				<option>选项二</option>
				<option>选项三</option>
				<option>选项四</option>
				<option>选项五</option>
			</select></a>
       </div>
		<div class="dropdown3"><a class="btn-select" id="btn_select2">
           
            <span>健康情况</span> <span class="caret"></span>           
            <select class="select1">
				<option>健康</option>
				<option>体弱</option>
				<option>选项三</option>
				<option>选项四</option>
				<option>选项五</option>
			</select></a>
       </div>
		<div style="clear: both;"></div>
		</div>
	
		<div class="content">
			<div class="service_date">
				<div class="calendar_pic"></div><span style="line-height: 35px;">服务日期</span></div>
				<div class="service_time">
					
						<span style="margin-left:46px;">1020-9-9至2202-6-6<span>
					</div>
					<div  class="price">
						<span style="margin-right:20px;">25元/小时<span>

				</div>
				<div class="location">
				<div class="locat_pic"></div>北京.通州.果园</div>
		</div>
		<div class="content">
			<div class="service_date">
				<div class="calendar_pic"></div><span style="line-height: 35px;">服务日期</span></div>
				<div class="service_time">
						<span style="margin-left:46px;">1020-9-9至2202-6-6<span>
					</div>
					<div  class="price">
						<span style="margin-right:20px;">25元/小时<span>
				</div>
				<div class="location">
				<div class="locat_pic"></div>北京.通州.果园</div>
		</div>
		<div class="content">
			<div class="service_date">
				<div class="calendar_pic"></div><span style="line-height: 35px;">服务日期</span></div>
				<div class="service_time">
						<span style="margin-left:46px;">1020-9-9至2202-6-6<span>
					</div>
					<div  class="price">
						<span style="margin-right:20px;">25元/小时<span>
				</div>
				<div class="location">
				<div class="locat_pic"></div>北京.通州.果园</div>	</div>
	<div style="width: 10%;height: 190px;"></div>
	<div class="footer">
		<div class="float_box">	
		<div class="home_box"></div>
		<p class="p1">首页</p>
		</div>	
		<div class="write_box"></div>
		<div class="float_box">	
		<div class="man_box" ></div> 
		<p class="p2">我的</p>
		</div>			
	</div>
</body>

<script>
function c(id) {
return document.getElementById(id);
}
window.onload = function () {

			var btnSelect0 = c("btn_select0");
			var curSelect0 = btnSelect0.getElementsByTagName("span")[0];
			var oSelect0 = btnSelect0.getElementsByTagName("select")[0];
			var aOption0 = btnSelect0.getElementsByTagName("option");
			oSelect0.onchange = function () {
				var text=oSelect0.options[oSelect0.selectedIndex].text;
				
				curSelect0.innerHTML = text;
			}
	
	var btnSelect1 = c("btn_select1");
			var curSelect1 = btnSelect1.getElementsByTagName("span")[0];
			var oSelect1 = btnSelect1.getElementsByTagName("select")[0];
			var aOption1 = btnSelect1.getElementsByTagName("option");
			oSelect1.onchange = function () {
				var text=oSelect1.options[oSelect1.selectedIndex].text;
				
				curSelect1.innerHTML = text;
			}

				var btnSelect2 = c("btn_select2");
			var curSelect2 = btnSelect2.getElementsByTagName("span")[0];
			var oSelect2 = btnSelect2.getElementsByTagName("select")[0];
			var aOption2 = btnSelect2.getElementsByTagName("option");
			oSelect2.onchange = function () {
				var text=oSelect2.options[oSelect2.selectedIndex].text;
				
				curSelect2.innerHTML = text;
			}

			var oA=document.getElementsByClassName('header')[0].getElementsByClassName('midle_box')[0].getElementsByClassName('a')[0];
			var oB=document.getElementsByClassName('header')[0].getElementsByClassName('midle_box')[0].getElementsByClassName('b')[0];
			oA.onclick = function () {
				this.style.zindex = 20;
				//alert(this.style.zindex);
		};
};
</script>
</html>
