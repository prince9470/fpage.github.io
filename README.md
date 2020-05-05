# fpage.github.io
sample page
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Ultimate Frisbee - Teams</title>
	<link rel="stylesheet" href="hw1.css">
  <style>
    body{
  margin: 1%;
  padding: 2px;
}
header{
  background: #b3b3b3;
  background-image: url("../images/flywheel.jpg");
  padding: 0.05%;
  height: 300px;
} 
h1{
  font-variant-caps:  all-small-caps;
  text-align: center;
  font-size:60px;
  color: #ffffffeb;
}
nav a{
    text-align: center;
    display: inline-block;
    width: 20%;
    height:40px;
    padding-top: 15px;
    border-radius: 5px;
    text-decoration: none;
    background-color: #ffffff;
    color: #000000;
    opacity: 0.3;
    font-size: 18px;
    margin:20px;
}

nav a:link{
    background-color: #ffffff;
}

nav a:visited,.active{  /*To make current page navigation link show*/
    background-color: #ffffff;
    opacity:1;
}
nav a:hover{
    background-color: #ffffff;
    opacity: 1.0;   
}
header>nav>a:active{
    background-color: #00ddee;
    opacity: 1.0;
}
img{
  height: 200px;
  width: 300px;
  display: block;
  float: left;
  clear: both;
  margin: 25px;
  border: 4px solid black;
}
.left{
height: 120vh;
  width: 25%;
  margin-right: 2%;
 display:inline-block;
 float: left;
 background: #298000e3;
}
h2{
  font-variant-caps:  all-small-caps;
  text-align:left;
  font-size: 50px;
}
a{
  font-size: 20px;
}
p{
  font-size:25px;
}
th{
  font-size: 20px;
}
td{
  font-size: 20px;
} 
table{
  margin-left: 30%;
  padding-right: 5%;
  width: 70%;
  line-height: 5px;
}
th{
  background: #358000db;
  color: #ffffff;
  border-radius: 2px;
  padding: 1.9%; 
  border-top:    2px solid black;
  border-bottom: 4px solid black;
}
th:nth-child(1){
  padding-right: 15%;
  text-align: left;
  position: strict;
  clear: both;
}
th:nth-child(2){
padding-right: 0.5%;  
 text-align: center;
  position: relative;
}
th:nth-child(3){
  padding-right: 1%;
  text-align: center;
  position: strict;
}

td{
background: #18800047;
  text-align: center;
  padding: 2%;
  border-radius: 4px;
opacity: 0.6;
}
tr td:nth-child(1){
  text-align: left;
}
td:hover{
  opacity: 1;
}
</style>
</head>
<body>
	<header>
		<h1>Ulimate Frisbee Teams</h1>
		<nav>
			<a href="index.html">Home</a>
			<a href="history.html" class = "active">Teams</a>
			<a href="history.html">History</a>
			<a href="http://www.usaultimate.org/index.html" target="_blank">USA Ultimate</a>
		</nav>
	</header>
	<main>
		<aside class = "left">
			<a href="https://commons.wikimedia.org/wiki/File%3AUltimate_Frisbee%2C_Jul_2009_-_17.jpg"><img src="https://upload.wikimedia.org/wikipedia/commons/5/5d/Ultimate_Frisbee%2C_Jul_2009_-_19.jpg" alt="Creative Common Ultimate Photo" title="By Ed Yourdon [CC BY-SA 2.0 (http://creativecommons.org/licenses/by-sa/2.0)], via Wikimedia Commons"/> </a>

			<a href="https://commons.wikimedia.org/wiki/File%3AUltimate_Frisbee_Colorado_Cup_2005.jpg"><img alt="Ultimate Frisbee Colorado Cup 2005" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/Ultimate_Frisbee_Colorado_Cup_2005.jpg/512px-Ultimate_Frisbee_Colorado_Cup_2005.jpg"/></a>


			<a href="https://www.flickr.com/photos/paradisecoastie/15409853738/" title="Ultimate Frisbee"><img src="https://farm4.staticflickr.com/3948/15409853738_7dbfbfbac7_k.jpg"  alt="Ultimate Frisbee"></a>
		</aside>
		<section class = "right">
			<h2>College Teams</h2>
			<p>This is not meant to be a comprehensive list of all the teams, just a sampling from around the United States.  I focused on the ones that I though had cools names.</p>
			<table>
				<tr><th>Team Name</th>
					<th>Location</th>
					<th>League Type</th></tr>
				<tr>
					<td>Afterburn - Air Force</td>
					<td>Colorado</td>
					<td>Men's</td>
				</tr>
				<tr>
					<td>Cold Front (Bates College)</td>
					<td>Maine</td>
					<td>Women's</td>
				</tr>
				<tr>
					<td>Disco Inferno (Brown University)</td>
					<td>Rhode Island</td>
					<td>Women's</td>
				</tr>
				<tr>
					<td>Bad Habit (Catholic University)</td>
					<td>Washington DC</td>
					<td>Men's</td>
				</tr>
				<tr>
					<td>Jive Turkeys (Dickinson College)</td>
					<td>Pennsylvania</td>
					<td>Both</td>
				</tr>
				<tr>
					<td>Knights of the Round Disc(Longwood College)</td>
					<td>Virginia</td>
					<td>Men's</td>
				</tr>
				<tr>
					<td>Ninjas (University of Minnesota)</td>
					<td>Minnesota</td>
					<td>Women's</td>
				</tr>
				<tr>
					<td>Flying Squirrels (Hendrix College)</td>
					<td>Arizona</td>
					<td>Men's</td>
				</tr>
				<tr>
					<td>Superfly (Yale)</td>
					<td>Connecticut</td>
					<td>Men's</td>
				</tr>
				<tr>
					<td>Flywheel (University of Michigan</td>
					<td>Michigan</td>
					<td>Women's</td>
				</tr>
			</table>
		</section>
	</main>
</body>
</html>
