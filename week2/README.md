

# FEWD - Box Model & More CSS

> Screencasts are available here: [Using Github to Create, Fork and Clone a Repository](https://vimeo.com/223378756) & [Quick Intro to CSS Padding, Border, & Margin](https://vimeo.com/223380795).

## Box Model

![](http://www.mandalatv.net/itp/drivebys/css/lib/img/box_model.gif)


- Width = width + padding-left + padding-right + border-left + border-right
- Height = height + padding-top + padding-bottom + border-top + border-bottom

## Basic example

```css
/* this is a css comment */
/* these comments can be read by anyone */

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
