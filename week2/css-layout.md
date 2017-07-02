## CSS Layout Example

*html*

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Building Some Layouts</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/7.0.0/normalize.css" />
    <link rel="stylesheet" href="styles/main.css">
  </head>
  <body>
    <div id='wrapper'>
    <header>
      <img src="monkey.jpg" alt="This is a photo of a cute monkey">
      <hgroup>
        <h1>Monkey Blog</h1>
        <h2>Holy Crap They're Cute!</h2>
      </hgroup>
    </header>

    <main>
      <section>
        <article class="">
          <hgroup>
            <h3>First Blog Post</h3>
            <h4>OMG I SAW A MONKEY</h4>
          </hgroup>
          <p>Lorem ipsum monkey yay :)
          </p>
        </article>
      </section>
      <aside class="">
        <h5>Things I like</h5>
        <ul>
          <li>cats</li>
          <li>dogs</li>
          <li>I LURVE MONKEYS</li>
        </ul>
      </aside>
    </main>

    <footer>
        Email me for more monkey business.
    </footer>
  </div>
  </body>
</html>
```

*css*
```css
/* here we go */
#wrapper {
  width: 960px;
  background: teal;
  margin: auto;
}

header {
  border: 1px dashed red;
  width: 100%;
  background: pink;
  height: 200px;
}

main {
  margin-top: 25px;
  border: 1px dashed orange;
  background: khaki;
  width: 100%;
}

section {
  border: 1px solid purple;
  background: lavender;
  height: 500px;
  width: 70%;
  position: relative;
  float: left;
}

aside {
  border: 1px solid blue;
  height: 500px;
  width: 20%;
  background: gray;
  position: relative;
  float: right;
}

footer {
  clear: both;
  border: 1px dashed green;
  margin-top: 25px;
  background: olive;
  width: 100%;
}
```