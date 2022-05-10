<html>
<head>
	<title>BUDDYKOTTU</title>
	<style>
	
		*{
			margin:0;
			padding:o;
		}
	
	    #navbar{
			
			display:flex;
			align-items:center;
			position:relative;
		}
		#navbar ul{
			display:flex;
			align-items:center;
		}
		#navbar::before{
			content:"";
			background-color:black;
			height:100%;
			width:100%;
			position:absolute;
			z-index:-1;
			opacity:0.2;
		}
		#logo{
				margin:4px 6px;
		}
		#logo img{
			margin:5px 5px;
			height:50px;
			width:5opx;
			border-radius:15px;
		}
		.tertiary-part{
			font-family: 'Varela Round', sans-serif;
			font-weight:bold;
			color:#1938a9c7;
			font-size:22px;
		}
		.items{
			padding:10px;
			list-style:none;
		}
		.items a{
			text-decoration:none;
			font-family: 'Varela Round', sans-serif;
			font-weight:normal;
			font-size:18px;
			color:black;
			padding:5px;
			
			
		}
		.items a:hover{
			background-color:black;
			color:white;
			border-radius:20px;
		}
		.forms{
			position:absolute;
			left:80%;
			
			
		}
		.form-one {
			
			list-style:none;
			padding:10px;
			margin:5px;
			
		}
		.form-one a{
			text-decoration:none;
			padding:5px;
			cursor:pointer;
			font-family: 'Varela Round', sans-serif;
			font-weight:normal;
			font-size:18px;
			color:black;
			background:lightgrey;
			border-radius:20px;
			
		}
		.form-one a:hover{
			background:black;
			color:white;
			border-radius:20px;
			
		}
		#deals{
			background-color:#ebe7e7;
			justify-content:center;
			margin:1px;
			display:flex;
		}
		#deals .box{
			margin:18px;
			text-align:center;
			
		}
		#deals .box img{
			height:80px;
			width:80px;
			border-radius:30px;
			padding:7px;
		}
		.fourth-part{
			font-family: 'Varela Round', sans-serif;
			font-weight:normal;
			font-size:15px;
			cursor:pointer;
		}
		.fourth-part:hover{
			color:blue;	
		}
		#poster{
			width:100%;
			height:200px;

		}
		.sliders{
			<!-- display:flex; -->
			justify-content:center;
			animation-name: photos;
			animation-iteration-count: infinite;
			animation-timing-function: linear;
			animation-duration:20s;
			width:99.3%;;
			height:40%;
		    align-items:center;
			background-size: cover;
			background-repeat: no-repeat;
			background-position: center;
			
		}
	@keyframes photos{
			0%{
				background-image:url("C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-freestocksorg-291762.jpg");
				
			}
			30%{
				background-image:url("C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-andrea-piacquadio-974911.jpg");
			}
			60%{
				background-image:url("C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-artem-beliaikin-1051744.jpg");
			}
			100%{
				background-image:url("C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-freestocksorg-291762.jpg");
				
			}
		
	</style>
</head>
<body>
	<nav id="navbar">
		<div id="logo">
			<img src="C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-andrea-piacquadio-972995.jpg"> 
	    </div>
	<h3 class="tertiary-part">BUDDYKOTTU</h3>
	<ul>
		<li class="items"><a href="#">Home</a></li>
		<li class="items"><a href="#">Latest</a></li>
		<li class="items"><a href="#">Services</a></li>
		<li class="items"><a href="#">Contact US</a></li>
		<li class="items"><a href="#">About Us</a></li>
	</ul>
		
		<ul class="forms">
			<li class="form-one"><a href="#">Log In</a></li>
			<li class="form-one"><a href="#">Register</a></li>
		</ul>
	  
	</nav>
	
	
	<section id="deals">
		<div class="box"><img src="C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-max-fischer-5869605.jpg">
			<h4 class="fourth-part">Offers</h4>
		</div>
		<div class="box"><img src="C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-luci-6791447 (1).jpg">
			<h4 class="fourth-part">Mobiles</h4>
		</div>
		<div class="box"><img src="C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-ricardo-esquivel-4011762.jpg">
			<h4 class="fourth-part">wearables</h4>
		</div>
		<div class="box"><img src="C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-gustavo-fring-4127636.jpg">
			<h4 class="fourth-part">Women wear</h4>
		</div>
		<div class="box"><img src="C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-raul-reynoso-1018911.jpg">
			<h4 class="fourth-part">Men Wear</h4>
		</div>
		<div class="box"><img src="C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-victoria-borodinova-1620760.jpg">
			<h4 class="fourth-part">Kids wear</h4>
		</div>
		<div class="box"><img src="C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-angele-j-128402.jpg">
			<h4 class="fourth-part">Groceries</h4>
		</div>
		<div class="box"><img src="C:/Users/home/AppData/Contacts/Downloads/Desktop/wordpress photos/pexels-curtis-adams-4469155.jpg">
			<h4 class="fourth-part">Appliances</h4>
		</div>
	</section>
	
	 <section class="posters">
		<div class="sliders">
			<!-- <p>Can’t do enough online shopping! No pesky sales people and it’s so much fun to get presents delivered to my door.</p> -->
		</div>
	</section>
	
</body>
</html>
