<!DOCTYPE html>
<html>
<head>
	<title>myPrinta</title>

	<!-- Required meta tags always come first -->
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width initial-scale=1.0">
	<meta http-equiv="x-ua-compatible" content="ie=edge">
	
	<!--latest complied  CSS -->
	<link rel="stylesheet" href="./css/bootstrap.css">
  <link rel="stylesheet" type="text/css" href="./fonts/font-awesome/css/font-awesome.css">
  <link rel="stylesheet" href="./css/my_printa.css">
  <link rel="stylesheet" href="./css/animate.css">
  <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/baguettebox.js/1.8.1/baguetteBox.min.css">
</head>

<body>
	<header>
		<div class="container">
			<div class="logo">
				<img src="img/myprinta.png" srcset="img/myprinta@2x.png 2x,
             img/myprinta@3x.png 3x"alt="myprinta">
			</div>
			<nav>
				<div class="menu">
					<ul>
						<li class="active"><a href="">WHO WE ARE</a></li>
						<li><a href="">MISSION</a></li>
						<li><a href="">WHY CHOOSE US</a></li>
						<li><a href="">CONTACT US</a></li>
					</ul>
				</div>
			<div class="hamburger">
				<span class="line"></span>
				<span class="line"></span>
				<span class="line"></span>
			</div>
			</nav>
		</header>
		<div class="mobile-menu">
				<ul>
					<li class="active"><a href="#">WHO WE ARE</a></li>
					<li><a href="#">MISSION</a></li>
					<li><a href="#">WHY CHOOSE US</a></li>
					<li><a href="#">CONTACT US</a></li>
				</ul>
			</div>
		</div>
	

		<div class="container">
		<div class="row">
			<div class="col-md-8 order-md-first col-sm-8 order-sm-last first">
				<h3>The new standard in the online printing</h3>
				<p>Myprinta is Africa's leading customer centric online printing company.<br>
				We handle numerous printing jobs for forward-thinking<br>
				businesses and individuals around the world.</p>
				<img src="img/get_in_touch.png">
			</div>

			<div class="col-md-4 second col-sm-4 order-md-last order-sm-first">
				<div class="first_image">
					<img src="img/opening_soon.png">
				</div>

				<div class="second_image">
					<img src="img/ellipse1.png" >
				</div>

			</div>
		</div>
	</div>

<script src="jquery-3.2.1.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js"></script>
	<script type="text/javascript" src="./js/wow.js"></script>
	<script type="text/javascript" src="./js/contact_me.js"></script>
	<script type="text/javascript" src="./js/jqBootstrapValidation.js"></script>
	<script>
	new WOW().init();
	</script>
<script type="text/javascript" src="./js/bootstrap.js"></script>
<script>
	$(".hamburger").click(function(){

		$(this).toggleClass("is-active"); 
		$(".mobile-menu").toggle();
	});
</script>
</body>
</html>

