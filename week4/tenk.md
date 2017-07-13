## 10,000 Ft View

This application dynamically creates a shopping list using `ul` and `li` tags. Try to read it in english and then figure the programming out. This is just another language like french or mandarin.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Javascript Intro</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/7.0.0/normalize.css">
    <link rel="stylesheet" href="styles/main.css">
    <meta name="viewport" content="width=device-width, initial-scale=1">
  </head>
  <body>

    <ul id='list'>
    </ul>
  </body>
  <script>
    var shoppingList = [
      'milk', 'bananas', 'orange juice', 'waffles', 'toast', 'bacon'
    ];
    var listElement = document.getElementById('list');
    // log variables
    console.log(shoppingList);
    console.log(listElement);
    // for each item in shoppingList
    shoppingList.forEach(function(item) {
      // console log item
      console.log(item);
      // create an li element
      var li = document.createElement('li');
      // set the innerHTML <p>Innerhtml is here</p>
      li.innerHTML = item;
      li.className = 'cssClass';
      li.background = 'blue';
      console.log(li);
      // append the li to the ul
      listElement.append(li);
    });



  </script>
</html>
```