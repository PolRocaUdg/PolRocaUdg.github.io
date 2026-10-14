<!DOCTYPE html>
<html>
  <head>
    <title>Curriculum Vitae</title>
	<link rel="stylesheet" type="text/css" href="CV.css">
  </head>
  <body>
	<div class="grid">
    <header class="header"> 
	  <img src="f1.jp g" alt="Pol">
	  <div class="header-text">
	    <h1> Pol Roca Villagra </h1>
	    <h2> Computer Engineer </h2>
	  </div>

	</header>
	<aside class="sidebar">
	  <hr class="sidebar-line">
	  <h3> Contact Information </h3>
	  <ul>
		<li> u6103285@campus.udg.edu </li>
		<li> +683434484 </li>
		<li> Puigsacalm Street, 42, 17003 Girona </li>
	  </ul>
	  <hr class="sidebar-line">
	  <h3> Language expertise</h3>
	  <p>English: High (B2 Certified)</p>
	  <p>Spanish: Native</p>
	  <p>Catalan : Native</p>
	  <hr class="sidebar-line">
	  <h3> Skill Record</h3>
	  <ul class="Skills">
		<li> Programming skills in C, C++, Python, Java </li>
		<li> Experience in web development with tools such as HTML, CSS, Javascript </li>
		<li> Database management with SQL and PHP </li>
		<li> Experience with neuronal networks and AI in Python </li>
		<li> Expertise in operative system calls in both Windows and Linux </li>
		<li> Skills in Video game development with Godot and Unity. </li>
		<li> Proficient with video editing and visual effects </li>
		<li> Efficient problem solving capacity </li>
		<li> Good and effective leadership capabilities </li>
	  </ul>

	</aside>
	
	<main class="main"> 
	<h3 class="box">Personal Profile</h3>
	<p> I consider myself as a very pragmatic Engineer, with a very high adaptability to any 
	circumstances and always willing to take the rides of a new project. I’m confident in my 
	skills and expertise when working on my own, and when working in teams I am always willing 
	to shape myself into whatever the team needs the most to work in a competent way.</p>
	<h3 class="box">Education</h3>
	<p>INS La Fageda, Girona</p>
	<ul>
	  <li>2018-2022</li>
	  <ul>
	    <li>Upper Highschool education</li>
	  </ul>
	  <li>2022-2024</li>
	  <ul>
	    <li>Science-Technology Bachelor </li>
	  </ul>
	</ul>
	<p>Universitat de Girona, Girona</p>
	<ul>
	  <li>2024-2028</li>
	  <ul>
	    <li>Computer Engineering Degree</li>
	  </ul>
	</ul>
	<h3 class="box">Work Experience</h3>
	<p class="strong">Diagnosis and Repair of computers</p>
	<ul>
	  <li>Name: LABDOO</li>
	  <li>Type: Volunteering</li>
	  <li>Duration: 2021-2021</li>
	</ul>
	<p class="strong">Assistant in a tech device repair establishment </p>
	<ul>
	  <li>Name: Infotecnik</li>
	  <li>Type: Job</li>
	  <li>Duration: 2024-2024</li>
	</ul>
	<p class="strong">Front-end Web development</p>
	<ul>
	  <li>Name: König</li>
	  <li>Type: Job</li>
	  <li>Duration: 2025-2025</li>
	</ul>

	</main>
	</div>
</html>

p, h1, h2, h3, li{
	font-family: Garamond;
	font-weight: normal;
	margin-top: 0.05em;
	margin-bottom: 0.05em;
}
h3{
	margin: 1em;
	font-weight: bold;
}

.main h3{

}

li{
	margin-bottom: 0.5em;
	margin-top: 0.5em;
}

.sidebar li{
	max-width: 80%;
}

.sidebar p{
	margin-left: 1em;
}



.grid{
	display: grid;
	grid-template-columns: 300px 1fr; /*Side content and main content*/
	grid-template-rows: auto 1fr; /*Header and main content*/
	min-height: 100vh;
	grid-template-areas: 
    "header header"
    "sidebar main";
	
}

.header{
	grid-area: header;
	display: flex;
	align-items: center;
	background-color: #4A433E;
	gap: 1em;
	color: white;
	padding: 2em;
	
}

.header img{
  width: 130px;
  height: 130px;
  border-radius: 65px; 
  border: 2px solid #FFFFFF;
}

.sidebar{
	grid-area: sidebar;
	display: flex;
    flex-direction: column; 
	background-color: #4A433E;
	color: white;
}

.sidebar-line {
  border: none;
  border-top: 1px solid white;
  width: 90%;
  margin-bottom: 0.5em;
  margin-top: 0.5em;
}

.main {
	grid-area: main;
	background-color: #D0BFB6;
	padding: 2em;
}

.strong{
	font-weight: bold;
}

.box{
	color: white;
	background-color: #61554E;	
	display: inline-block;
	padding: 10px 10px;
	border-radius: 15px;
}
