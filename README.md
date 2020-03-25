# trial
<!DOCTYPE html>
<html>
<body>
<style>
.header{
text-align:center;
color:green;
font-size: 40px ;
font-family: "Times New Roman", Times, serif;
font-weight: bold;
}
.time{
text-align: right;
font-size: 20px;
}
.sidebar{
position: relative;
float: left;
height: 100%;
background-color: red;
border-radius: 20px;

width:25%;
 margin:10px;
}

.sidebar ol li{
font-size: 20px;
height:6%;
margin:30px;
background-color: yellow;
list-style-type: none;
border-radius: 20px;
}
.sidebar ol li:hover{
background-color: green;
color:white;
font-weight: bold;
}
.content {
	position: relative;
	float:left;
	margin-left:7%; 
	width:50%;

}
</style>
<h1 class="header">CORONTIME ESSENTIALS</h2>

<p align="right" id="time"></p>
<div class="sidebar">
	<ol>
		<li><a href="C:\Users\krithikha\Desktop\dsc proj\mask.html" target="iframe_a">mask </a></li>
		<li> Sanitizer</li>
		<li> hbjsn </li>
		<li> jhj</li>
		<li> jjn</li>
		<li> enter some shittt </li>
	</ol>
</div>
<div class="content">
<iframe height="500px" width="100%" src="" name="iframe_a"></iframe>
</div>
<script>
var date = new Date();
var n = date.toDateString();
var time = date.toLocaleTimeString();
document.getElementById('time').innerHTML = n + ' ' + time;

</script>
</body>
</html> 
