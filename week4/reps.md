## Javascript Reps

We practiced these in class. Try them in your browser's _console_. 


```js
// reps.js

// comments
// declare a variable
var name = 'James';
// var says this is a variable with the name 'name' and a value of 'James'
typeof name
// what am I?

// 3 new variables:
// petName, carMake, faveFood

var petName = 'Magda';
var carMake = 'Mazda';
var faveFood = 'Soylent';

// log all 3 using console.log()
console.log(petName);
console.log(carMake);
console.log(faveFood);

// numerics
var pi = 3.14;
var age = 33;
var faveNumber = 42;

typeof pi;
typeof age;
typeof faveNumber;

// boolean
var isHangry = false;
var isOverTwentyOne = true;
var isCool = true;

typeof isHangry;

// arrays of thing
var friends = ['Lichard', 'Omily', 'Katthew', 'Cecelious'];
var pets = ['Magda', 'Kirby', 'Gus', 'Lucy'];

Array.isArray(friends);
// use this because typeof array === 'object'

// loop through all items in an array
friends.forEach(function(friend) {
  console.log(friend);
});

pets.forEach(function(pet) {
  console.log(pet);
});

// create elements
var list = document.createElement('ul');
var p = document.createElement('p');
var article = document.createElement('article');
var item = document.createElement('li');

console.log(item);

// finally... IF / ELSE
if (isOverTwentyOne) {
  console.log('gimme booze');
} else {
  console.log('womp womp');
}

if (20 > 21) {
  console.log('u can haz beer');
} else {
  console.log('no beer 4 u');
}
```