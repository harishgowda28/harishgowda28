 body {
	font-family: Arial, sans-serif;
}

header {
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding: 20px;
	background-color: #333;
	color: #fff;
}

nav ul {
	display: flex;
	list-style: none;
}

nav li {
	margin-left: 20px;
}

nav a {
	color: #fff;
	text-decoration: none;
}

main {
	max-width: 800px;
	margin: 0 auto;
	padding: 20px;
}

section {
	margin-bottom: 40px;
}

h2 {
	margin-top: 0;
}

ul {
	list-style: none;
	padding: 0;
}

li h3 {
	margin-bottom: 10px;
}

form label {
	display: block;
	margin-bottom: 5px;
}

form input, form textarea {
	display: block;
	margin-bottom: 20px;
	width: 100%;
	padding: 10px;
	border-radius: 5px;
	border: none;
}

form input[type="submit"] {
	background-color: #333;
	color: #fff;
	padding: 10px 20px;
	border-radius: 5px;
	border: none;
	cursor: pointer;
}

form input[type="submit"]:hover {
	background-color: #555;
}
