## Boilerplate HTML & CSS

> Remember - classes are re-usable and IDs are singular!

```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<link rel="stylesheet" type="text/css" href="styles/main.css">
</head>
<body>
	<section>
		<article id='headline-article'>
			<h1 class='box' id='headline-h1'>Title Dude</h1>
			<h2>Totally Radical</h2>
			<p class='paragraph'>Just a few words</p>
		</article>
		<article>
			<h1 class='box'>Bodacious</h1>
			<h2>Tubular</h2>
			<p class='paragraph'>Old words?</p>
		</article>
		<article>
			<h1 class='box'>Charmander</h1>
			<h2>Burninates you</h2>
			<p class='paragraph'>Strongbad crossover</p>
		</article>
	</section>

</body>
</html>
```

```css
h1 {
	font-size: 28px;
}

h2 {
	font-size: 20px;
}

#headline-article {
	font-weight: bold;
	font-style: italic;
}

#headline-h1 {
	font-size: 36px;
}

.paragraph {
	font-size: 16px;
	color: purple;
	font-family: 'Arial', sans-serif;
}

.box {
	border: 1px dashed navy;
}
```