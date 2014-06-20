my-only-question
================

how do i set up may 3 sidebars to the left next to my posts?

<!---html--->
<!DOCTYPE html >
<html lang="en" >
<head>
<title>Portfolio</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" type="text/css" href="estilo.css">

</head>
<body class= "body">
<header class="mainHeader">
<h3>Este e o meu site</h3>

<nav><ul> 
	<li class="active"><a href="#">Home</a></li>
	<li><a href="#">Os Meus Projectos</a></li>
	<li><a href="#">Blog</a></li>
	<li><a href="#">Contactos</a></li>
	</ul>
</nav></header>
<div class="mainContent">
	<div class="content">
		<article class="bottomcontent">
			<header>
				<h2><a href="#" title="First Post">Segundo Post</a></h2>
			</header>
			<footer>
				<p class="post-info">Post feito por <i>Edmilson Semedo</i></p>
			</footer>
			<content>
				<p>e aki que fica toda a informacao sobre mim u up. You're gonna stay with us now.' 
				That's when I started adjusting to the streets a little bit".[16]
At age eleven, Jackson started boxing. The following year, Jackson started working with narcotics but informed 
his grandparents he attended school 
rograms.[17] During this time, he began bringing guns and drug money to school. When Jackson was fourteen years 
old, a neighbor opened a boxing gym for local youth. He recalled: "When I wasn't killing time in school, I was 
sparring in the gym or selling crack on the strip."[18] In the mid-1980s, Jackson competed in the Junior Olympics 
as an amateur boxer. He later stated: "I was competitive in the ring and hip-hop is competitive too... 
I think rappers condition themselves like boxers, s
o they all kind of feel like they're the champ".[19] At the age of sixteen, he was c hjhahahah</p>
			</content>
		</article>
		<article class="topcontent">
			<header>
				<h2><a href="#" title="Second Post">Primeiro Post</a></h2>
			</header>
			<footer>
				<p class="post-info">Post feito por <i>Edmilson Semedo</i></p>
			</footer>
			<content>
				<p>eu nem sei o que vou meter aki lol
				That's when I started adjusting to the streets a little bit".[16]
At age eleven, Jackson started boxing. The following year, Jackson started working with narcotics but informed 
his grandparents he attended school 
rograms.[17] During this time, he began bringing guns and drug money to school. When Jackson was fourteen years 
old, a neighbor opened a boxing gym for local youth. He recalled: "When I wasn't killing time in school, I was 
sparring in the gym or selling crack on the strip."[18] In the mid-1980s, Jackson competed in the Junior Olympics 
as an amateur boxer. He later stated: "I was competitive in the ring and hip-hop is competitive too... 
I think rappers condition themselves like boxers, s
o they all kind of feel like they're the champ".[19] At the age of sixteen, he was c hjhahahah</p>
			</content>
			
		</article>
	</div>
</div>
			<div class="top-sidebar">
				<article>
					<h2> Top Sidebar</h2>
					<p>Aqui fica uma foto minha e uma breve intro. </p>
				</article>
			</div>
			<div class="middle-sidebar">
				<article>
					<h2> Middle Sidebar</h2>
					<p>Usar o Geo e talvez um cont de visitas </p>
				</article>
			</div>
			<div class="bottom-sidebar">
				<article>
					<h2> Bottom Sidebar</h2>
					<p>Simbolos de linguagem usada pa criar o site </p>
				</article>
			</div>
			
</body>
</html>
<!--my css-->

body {
	background-color:#B3B3B3;
	color:#000305;
	font-size:87,5%;
	font-family:Arial;
	line-height:1.5;
	text-align:left;
}
 
a {
	text-decoration:none;
}
a:link, a:visited{
	color:#CF5C3F;
}
a:hover, a:active {
	background-color:#CF5C3F;
	color:#FFF;
	border-radius:30px;
}
.body{
	margin:0 auto;
	width:70%;
	clear: both;
}
.mainHeader img{
	width:30%;
	height:auto;
	margin:2% 0;
}
.mainHeader nav{
	background-color:#666;
	height:40px;
	border-radius:5px;
	-moz-border-radius:5px;
	-webkit-border-radius:5px;
}
.mainHeader nav ul{
	list-style:none;
	margin:0 auto;
}
.mainHeader nav ul li{
	float:left;
	display:inline;
}
.mainHeader nav a:link, .mainHeader nav a:visited{
	color:#FFF;
	display: inline-block;
	padding:10px 25px;
	height:20px;
}
.mainHeader nav a:hover, .mainHeader nav a:active,
.mainHeader nav .active a:link, .mainHeader nav active a:visited, .mainFooter p a, .mainFooter p a:hover{
	background-color:#CF5C3F;
	text-shadow: none;
}
.mainHeader nav ul li a {
	border-radius:5px;
}
.mainContent{
	width:70%;
	line-height:25px;
	overflow:hidden;
	border-radius:5px;
	-moz-border-radius:5px;
	-webkit-border-radius:5px;
}
.content{
	float:left;
}
.topcontent {
	background-color:#FFF;
	border-radius:5px;
	-moz-border-radius:5px;
	-webkit-border-radius:5px;
	padding:3% 5%;
	margin-top:2%;
}
.bottomcontent{
	background-color:#FFF;
	border-radius:5px;
	-moz-border-radius:5px;
	-webkit-border-radius:5px;
	padding:3% 5%;
	margin-top:2%;
}
.top-sidebar {
	width:21%;
	float:left;
	border-radius:5px;
	background-color:#FFFFFF;
	-moz-border-radius:5px;
	-webkit-border-radius:5px;
	margin-left:3%;
	margin-bottom:2%;
	padding:2% 3%;	
}
.middle-sidebar{
	width:20%;
	float: left;
	border-radius:5px;
	background-color:#FFFFFF;
	-moz-border-radius:5px;
	-webkit-border-radius:5px;
	margin-left:3%;
	margin-bottom:2%;
	padding:2% 3%;
}
.bottom-sidebar{
	width:21%;
	float: left;
	border-radius:5px;
	background-color:#FFFFFF;
	-moz-border-radius:5px;
	-webkit-border-radius:5px;
	margin-left:3%;
	margin-bottom:2%;
	padding:2% 3%;
}
