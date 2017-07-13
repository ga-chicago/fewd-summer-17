## Flexbox & Responsive Design

>> CDNJS hosts CSS and Javascript files... https://cdnjs.com/libraries/normalize

#### Meta Viewport Tag

* No more pinch-to-zoom! 
* `<meta name="viewport" content="width=device-width, initial-scale=1">`

#### Grid System

* Try not to use Bootstrap unless it is for prototyping
* Check out Materialize, Material Design Light, Foundation
* I highly recommend Skeleton for newbies - http://getskeleton.com/
* Rows > Columns
* Up to 12 columns in a row...
* This is fairly standardized but not always
* Soon to be a spec
	- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout
	- https://css-tricks.com/snippets/css/complete-guide-grid/

#### Psuedo Classes

- `:nth-child(2)`
- https://css-tricks.com/pseudo-class-selectors/

#### Flexbox Example CSS

```css
body {
  min-height: 100%;
  font: 14px Comic Sans MS;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin: 0 auto;
}

header, footer {
  width: 100%;
  background: navy;
  color: white;
  text-align: center;
  line-height: 20px;
}

main {
  display: flex;
  justify-content: space-around;
}

section {
  text-align: center;
  padding: 25px;
  border-radius: 25px;
  background: pink;
  color: black;
  min-height: 50px;
  width: 250px;
  justify-content: space-around;
}
```

