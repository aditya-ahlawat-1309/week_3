<!DOCTYPE html>
<html>
<head>
	<title>McDonald's Restaurant</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="styles.css">
	<link href="https://fonts.googleapis.com/css2?family=Satisfy&display=swap" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css2?family=Cousine&family=Satisfy&display=swap" rel="stylesheet">
</head>
<body>



<header>
	<nav id="header-nav" class="navbar navbar-default">
		<div class="container">
			<div class="navbar-header">
				<a href="main_file.html" class="pull-left visible-md visible-lg">
			    <div id="logo-img">
					<img src="https://miro.medium.com/max/2000/1*6JDbWUZmpWT_reZbXAaj4g.png" alt="" width="130" />
				</div>
				</a>

				<div class="navbar-brand">
					<a href="main_file.html"><h1>McDonald's Restaurant</h1></a>

				<p>
					<img id="k-logo" src="https://cpimg.tistatic.com/05364319/b/4/KOSHER-Certification-Service.png" alt="Kosher Certification"/>
					<span>KOSHER CERTIFICATION</span>
				</p>
			    </div>
			    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#collapsable-nav" aria-expanded="false">
			    	<span class="sr-only">Toggle Navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
			    </button>
			</div>

			<div id="collapsable-nav" class="collapse navbar-collapse">
				<ul id="nav-list" class="nav navbar-nav navbar-right">
					<li class="visible-xs active">
						<a href="main_file.html">
							<span class="glyphicon glyphicon-home"></span>Home
						</a>
						
					</li>
					<li>
						<a href="menu-categories.html">
							<span class="glyphicon glyphicon-cutlery"></span><br class="hidden-xs">Menu
						</a>
					</li>
					<li>
						<a href="#">
							<span class="glyphicon glyphicon-info-sign"></span><br class="hidden-xs">About
						</a>
					</li>
					<li>
						<a href="#">
							<span class="glyphicon glyphicon-certificate"></span><br class="hidden-xs">Awards
						</a>
					</li>

					<li id="Phone" class="hidden-xs">
						<a href="tel:+91-8901459471">
							<span>+91-8901459471</span></a><div>* We Deliver</div>
					</li>
				</ul>

		</div>
	</nav>

</header>

<div id="call-btn" class="visible-xs">
	<a class="btn" href="tel:+91-8901459471">
		<span class="glyphicon glyphicon-earphone"></span>
		+91-8901459471
	</a>
</div>
<div id="xs-deliver" class="text-center visible-xs">* We Deliver</div>

<div id="main-content" class="container">
	<div class="jumbotron">
		<img src="https://media-cdn.tripadvisor.com/media/photo-s/16/22/0a/8c/jumbotron.jpg" alt="Picture of restaurant"
		class="img-responsive visible-xs">
	</div>


	<div id="home-tiles" class= "row">
		<div class="col-md-4 col-sm-6 colxs-12">
			<a href="menu-categories.html"><div id="menu-tile"><span>Menu</span></div></a>
		</div>
		<div class="col-md-4 col-sm-6 col-xs-12">
			<a href="single-category.html"><div id="specials-tile"><span>specials</span></div></a>
		</div>
		<div class="col-md-4 col-sm-12 col-xs-12">
			<a href="https://goo.gl/maps/q5ho5UgjuPsxn19HA" target="_blank">
				<div id="map-tile">
					<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d54893.766601111885!2d76.83419226264918!3d30.694203287148877!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390f935e391459e9%3A0x5779c42c041ca7a3!2sMcDonald&#39;s%20India!5e0!3m2!1sen!2sin!4v1593144544872!5m2!1sen!2sin" width="100%" height="250" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
					<span>map</span>
				</div>
			</a>
		</div>
    </div>  <!-- end of home tiles -->
</div> <!-- end of main content -->

<footer class="panel-footer">
	<div class="container">
		<div class="row">
			<section id="hours" class="col-sm-4">
				<span>Hours:</span><br>
				Sun-Thurs: 11:15am -10:00pm<br>
				Fri : 11:15am - 2:30pm<br>
				Saturday Closed
				<hr class="visible-xs">
			</section>
			<section id="address" class="col-sm-4">
				<span>Address:</span><br>
				Sector-11 Panchkula<br>
				On main road Showrooms
				<p>* Delivery area within 3-4 miles, with minimum order of $20 plus $3 charge for all deliveries</p>
				<hr class="visible-xs">
			</section>
				<section id="testimonials" class="col-sm-4">
					<p>"the best fast food resturant in panchkula"</p>
					<p>"the amazing and delicious food of american company"</p>
					
				</section>

		</div>
		<div class="text-center">&copy; Copyright Mcdonald's Restaurant 2020
		</div>
	</div>
	
</footer>


<!-- jQuery  (Bootstrap plugins depend on it) -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</body>
</html>
