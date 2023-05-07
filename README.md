<!DOCTYPE html>
<html>
<head>
	<title>My Portfolio</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<h1>My Name</h1>
		<nav>
			<ul>
				<li><a href="#about">About</a></li>
				<li><a href="#projects">Projects</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="about">
			<h2>About Me</h2>
			<p>Write a short bio about yourself here.</p>
		</section>
		<section id="projects">
			<h2>My Projects</h2>
			<ul>
				<li>
					<h3>Project 1</h3>
					<p>Write a short description of project 1 here.</p>
				</li>
				<li>
					<h3>Project 2</h3>
					<p>Write a short description of project 2 here.</p>
				</li>
				<li>
					<h3>Project 3</h3>
					<p>Write a short description of project 3 here.</p>
				</li>
			</ul>
		</section>
		<section id="contact">
			<h2>Contact Me</h2>
			<form>
				<label for="name">Name:</label>
				<input type="text" id="name" name="name"><br>

				<label for="email">Email:</label>
				<input type="email" id="email" name="email"><br>

				<label for="message">Message:</label>
				<textarea id="message" name="message"></textarea><br>

				<input type="submit" value="Send">
			</form>
		</section>
	</main>
</body>
</html>
