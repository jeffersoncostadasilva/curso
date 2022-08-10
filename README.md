<html>
<head> <title>Friendly Pet</title>
<link rel="stylesheet" href="style.css" type="text/css" />
<meta charset="utf-8">
<link rel="icon" type="imagem/png" href="img/logocortada.png" width="50px" height="50px" />
<link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">

<style>
/*Slider*/
#slider {overflow: hidden;}
#slider figure {position: relative;width: 625%;margin: 0;left: 0;animation: 20s slider infinite;}
#slider figure img {width: 16%;float: left;}

@keyframes slider {
	0% {left: 0;}
	20% {left: 0;}
	25% {left: -100%;}
	45% {left: -100%;}
	50% {left: -200%;}
	70% {left: -200%;}
	75% {left: -300%;}
	95% {left: -300%;}
	100%{left: -400%;}
}
</style>
</head>

<body>

<div id="total">

<div id="topo">

      <div id="menu">
		<div id="logo">
		<a href="index.html">
		<img src="img/logonova2.png" width="110px" height="60px">
		</a>
		</div>
		<div id="links">
		 <a href="index.html" style="color:rgb(140, 142, 35); border-bottom: solid #8e2723 3px;"> HOME </a>
		 <a href="quemsomos.html"> QUEM SOMOS </a>
		 <a href="serviços.html"> SERVIÇOS </a>
		
		 <a href="contatos.html"> CONTATOS </a>
      </div>
	  </div>
	  
	 
</div>

<div id="banner">
   	
	<div id="slider">
			<figure>
            <img src="img/nene.jpg"alt="nene" width="460" height="345">>
			<img src="img/vascoaa.jpg"alt="vascoaa" width="460" height="345"> >
			<img src="img/vascoaaa.jpg"alt="vascoaaa" width="460" height="345"> >
			<img src="img/vascos.jpg"alt="vascos" width="460" height="345">>
			<img src="img/vascosa.jpg"alt="vascosa" width="460" height="345"> >
			</figure>
	</div>

	<>
		var myIndex=0
		carousel();
		
		function carousel(){
		var i;
		var x= document.getElementsByClassName("mySlides");
		for(i=0;i < x.length; i++){
		  x[i].style.display ="none";
		}
		myIndex++;
		if(myIndex > x.length) {myIndex=1}
		x[myIndex-1].style.display = "block";
		setTimeout(carousel, 4000);//Change image every 0,10 seconds	 
		
		}
		</>
	</div>
	
</div>

	<div id="conteudo">
	
	<div id="teste">
	<img src="img/criança.jpg" width="370" height="250">
	<img src="img/criançaa.jpg"  width="370" height="250" style="margin-left:4%">
	<img src="img/criançaaa.webp"  width="370" height="250" style="margin-left:4%">
	</div>
	
	</div>
		<br><br>
		<hr class="hr"/>

		<h2 class="mapa">Onde estamos</h2>
	  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3673.279460544278!2d-43.23264858539865!3d-22.97674884614684!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9bd5b700b6191d%3A0xb1ae310fe7c55482!2sR.+Marqu%C3%AAs+de+S%C3%A3o+Vicente%2C+124+-+G%C3%A1vea%2C+Rio+de+Janeiro+-+RJ%2C+22451-041%2C+Brasil!5e0!3m2!1spt-BR!2sus!4v1563231896395!5m2!1spt-BR!2sus" 
	  width="750px" height="450px" frameborder="0" style="float:left; margin-left:6%; margin-top: 1%; border:0; border-radius: 15px;" allowfullscreen></iframe>
	  
	  <div id="c1">
		<a href="serviços.html"><div class="container">
			<img src="img/veter.png" alt="Avatar" class="image">
			<div class="overlay">Serviços</div>
		  </div></a>
		
		  <a href="serviços.html#pet"><div class="container">
			<img src="img/petshop.jpg" alt="Avatar" class="image">
			<div class="overlay">Pet Shop</div>
		  </div></a>
		</div>

		
	 <div id="rodape">
	 
	  <div id="r1">
	
	  </div>  
	  
	  <div id="r2">
	  <div id="txt">
	  <br>
	  <p>Contatos<br>
	 </p>
	  <h3>Friendly Pet<br>
	  Tel (21) 5725-4222</h3>
	  </div>
	
		<li><img src="img/Whats.svg" width="26px" height="26px"> 
	   	<img src="img/instagram.svg" width="26px" height="26px">  
		<img src="img/facebook.svg" width="26px" height="26px"> 
		<img src="img/gmail.svg" width="26px" height="26px">  </li>
		  
	  </div>
	  	  
	  <div id="r3"> <font face="Roboto" color="#808080">
	  <p>Desenvolvido por Hypertech. © Copyright 2020; Todos os direitos reservados </p> </font>
	  </div>
	   	 
	 </div>
	 	 
</div>	 
</body>
</html>
