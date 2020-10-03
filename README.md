<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
	<!-- For Social media icons -->
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

	<style>
		.background{
			background-image:url("background.jpg");
			background-size: cover;
			height: 100vh;
		}


		

		.fa:hover {
			opacity: 1;
		}
		
		.fa-google {
		background: #dd4b39;
		color: white;
		}

		.fa-linkedin {
		background: #007bb5;
		color: white;
		}

		.fa-youtube {
		background: #bb0000;
		color: white;
		}

		
	</style>

    <title>Home</title>
  </head>
  <body>
	<nav  class="navbar navbar-expand-lg navbar-dark bg-dark">
		<a class="navbar-brand" href="#">
			<img src="logo.png" width="30" height="30" class="d-inline-block align-top" alt="">
			Ganesh Patra
		</a>
		<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
		  <span class="navbar-toggler-icon"></span>

		</button>
	  
		<div  class="collapse navbar-collapse" id="navbarSupportedContent">
		  <ul class="navbar-nav mr-auto">
			<li class="nav-item active">
			  <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
			</li>
<!-- 			<li class="nav-item">
			  <a class="nav-link" href="#">About</a>
			</li> -->
			<li class="nav-item">
				<a class="nav-link" href="work.html">Work</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="journey.html">My Journey</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" target="_blank" href="https://drive.google.com/file/d/1NswRt2hW7vI_n7VAsYd_fSD7sna4wYDY/view?usp=sharing">Resume</a>
			</li>
			
		  </ul>
		</div>
	</nav>
		<div class="container-fluid background ">
			<div class="row">
				<div class="col" >
					<center><img src="ganesh.jpg" class="img-fluid"  style="border-radius: 50%; margin-top:30px; "></center>
				</div>
			</div>
			<div class="row" >
				<div class="col" style="color: white;">
					<center><h1>Vikas Patra</h1></center>
					<center><h7>Software Engineer | Machine Learning | Competitive programming </h7> </center>
					<center>
						<a href="#" class="fa fa-google"></a>
						<a href="https://www.linkedin.com/in/ganesh-patra/" target="_blank" class="fa fa-linkedin"></a>
						<a href="https://www.youtube.com/channel/UCqWcLKvibUdE08OgHc07CVA" target="_blank" class="fa fa-youtube"></a>
						<a href="https://www.github.com/92ganesh" target="_blank" class="fa fa-github"></a>
					</center>
				</div>
			</div>
		</div>

	<!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
	  <script>
		window.onload = function() {
		   //reloadPage();
		};

		function re(){
			location.reload(true);
		}


		function reloadPage(){
			setInterval(re, 500);
			//setInterval(console.log("check"),5000);
		}

	  </script>
	</body>
</html>
