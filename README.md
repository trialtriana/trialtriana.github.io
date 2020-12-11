<!DOCTYPE html>
<html>
<head>
	<title>parallax</title>
	<link rel="stylesheet" href="styleparallax.css">
</head>
<body>
	<section>
		<img src="back.jpg" id="back">
		<img src="moon.png" id="moon">
		<img src="mountain.png" id="mountain">
		<img src="road.png" id="road">
        <h2 id="text"><font face="Aliens Among Us"> Asep Rangga </font></h2>
	</section>
    <script type="text/javascript">
    	let back = document.getElementById("back");
    	let moon = document.getElementById("moon");
    	let mountain = document.getElementById("mountain");
    	let road = document.getElementById("road");
    	let text = document.getElementById("text");

    	window.addEventListener('scroll', function(){
    		var value = window.scrollY;

    		back.style.top = value * 0.5 + 'px';
    		moon.style.left = -value * 0.5 + 'px';
    		mountain.style.top = -value * 0.15 + 'px';
    		road.style.top = value * 0.15 + 'px';
            text.style.top = value * 1 + 'px';
    	})
    </script><br>
    <h2><font color="white" font face=""> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
    cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
    proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
    cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
    proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
    cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
    proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<a href="index2.html">Back</a></font></h2><br>
    <a href="index2.html>
</body>
</html>
