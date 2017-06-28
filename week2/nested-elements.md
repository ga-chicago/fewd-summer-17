## Nested Elements with Classes

#### style.css

```css
/* this is a css comment */
/* these comments can be read by anyone */

.pink-items {
  background: pink;
}

.lime-items {
  background: lime;
}

.secret {
  color: black;
  background: black;
}

.snow {
  background: aliceblue;
}

h1 {
  padding: 20px; /* bubble wrap */
  margin: 20px; /* white space between tags */
  border: 5px solid purple; /* our cardboard box */
}

h2 {
  padding: 50px;
  margin: 2px;
  border: 15px dashed green;
  border-radius: 50px;
}
```

#### index.html

```html
<!DOCTYPE html>
<html>

<head>

  <meta charset="UTF-8">

  <title>The Box Model</title>

    <link rel="stylesheet" href="css/style.css" media="screen" type="text/css" />

</head>

<body>

  <h1>Box Model</h1>
  <p>Every element on the page has its own box, which can be styled using CSS.</p>
  <p>From the inside out:</p>
  <ol>
    <li class='lime-items'>content</li>
    <li class='lime-items'>padding</li>
    <li class='lime-items'>border</li>
    <li class='lime-items'>margin</li>
  </ol>

<h2>Background</h2>
<p>Keep in mind that a <code>background</code> will cover the content and the padding.</p>

<h2>Together</h2>
<ol>
  <li class='pink-items'>Give the <code>h1</code> a red background, some padding, and a black border.</li>
  <li class='pink-items'>Give every <code>p</code> a blue background, white text, some padding, and a black border.</li>
  <li class='pink-items'>Give every <code>code</code> element a white background, black text, a little padding, and a thin border.</li>
</ol>

<h2>Now You Try</h2>
<ul>
  <li>Try adding styles for the <code>h2</code>s, <code>ol</code>s, and <code>li</code>s on this page.</li>
  <li>Look into the syntax for <code>margin</code> and try adding more space around elements by using them.</li>
</ul>

<section>
  <article class="">
    <ul>
      <li class='snow'>Pamela</li>
      <li class='snow'>Sarah</li>
      <li class='snow'>Bill Nye</li>
      <li class='snow'>Addy Osmani</li>
    </ul>
  </article>
</section>
</body>

</html>
```
