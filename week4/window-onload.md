## window.onload

- onload is a _function_ that the window _object_ provides
- only executes (runs) code when every asset on the page has loaded
- safest place to put code if something on the page is to be manipulated (for now)

#### Example

```js
window.onload = function(event) {
  console.log('Hi mom');
}
```