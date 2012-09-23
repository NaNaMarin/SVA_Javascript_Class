SVA_Javascript_Class
====================

Homework

<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
	<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<title>Condtionals</title>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
	<meta name="author" content="The Chopping Block, Inc." />
	<meta name="geo.country" content="US" />
	<meta name="dc.language" content="en" />
	<meta name="description" content="" />
	<meta name="keywords" content="" />
	
	<link rel="stylesheet" href="styles.css" type="text/css" media="screen" charset="utf-8" />
	
	<style type="text/css" media="screen">		
		/*local styles if any (quick tests and local only overrides)*/
	</style>
</head>
<body>

	<div class="wrap" >
		Project: Condtionals

	  <ul>
			<li>Display the prompt</li>
			<li>Take the value from the prompt and display on the screen</li>
		</ul>
		<p id="paragraph"></p> 
		
	
	</div>
	<script type="text/javascript" charset="utf-8">

		
		var answer = prompt("Please choose a number between 1-3", "");
		if (answer == "2")
  		alert("You win!");
		else if (answer == "3" || answer == "1")
  		alert("Please Try Again.");
		
		

		
		
	</script>
	
	
</body>
</html>
