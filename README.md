# 1122
<body style="overflow-y:hidden"> 去掉x轴
<body style="overflow-x:hidden"> 去掉y轴
<body scroll="no">不显
<TD onmouseover="this.style.backgroundColor='#FFFFFF'" 
onmouseout="this.style.backgroundColor=''"
style="CURSOR: hand">
<body ondragstart=window.event.returnValue=false
oncontextmenu=window.event.returnValue=false onselectstart=event.returnValue=false>
<iframe name="pindex" src="index.asp" frameborder=false scrolling="auto" width="100%" 
height="100%" frameborder=no onload="document.all
['pindex'].style.height=pindex.document.body.scrollHeight" ></iframe>
<script type="text/javascript">
function doZoom(size)
{document.getElementById('zoom').style.fontSize=size+'px';}
</script>
<span id="zoom">需要指定大小的文字</span>
<a href="javascript:doZoom(16)">大</a> <a href="javascript:doZoom(14)">中</a> <a
href="javascript:doZoom(12)">小</a>
