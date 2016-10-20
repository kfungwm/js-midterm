Instructions:

- Add your answers inline to the markdown file.
- Use your own words.
- Come up with an answer from memory. Write it down, even if the answer is "I don't know."
- Then, we will go over the answers in class. Write down your revised answer below your original answer.

---
### Part 1: Control Flow - 15 minutes

1. Draw a diagram of an if statement. Name each of the components and how they work together.

var done = false;
var counter = 0;

while (!done) {
  console.log("not done");
  if (counter >= 5) { //if
    done = true;
  }

  counter++;
}

2. Draw a diagram of a for loop. Describe each of its components. Indicate the order in which they are executed / evaluated.

var myArray = (1, 2, 3) {
  for (var i = 0; i < myArray.length; i++);

}
console.log(i);




3. Functions
 - 3a. Draw a diagram of a function. Describe each of its components and what each component does. Specify which of them are optional.

var doingTest = function() { // giving the function name
  console.log('I am doing a test'); // what you want to print it out
}
result = doingTest(); // to get the result what you want to print.


 - 3b. Draw a diagram of a function being called, showing the instruction execution order.

 var doingTest = function() { // giving the function name
   console.log('I am doing a test'); // what you want to print it out
 }
 result = doingTest(); // to get the result what you want to print.
 console.log(result); // show all the result
---
### Part 2: Data Types - 10 minutes

4. Primitive Data Types
 - 4a. Give an example of an empty string and a non-empty string.
 empty string = ""
 non-empty string = "string"

 - 4b. Give an example of a boolean.
 true false

 true || true  false && true

 - 4c. Give an example of a Number.
 1,2,3,5

5. Arrays
 - 5a. Give an example of an empty array.
 var myArray = [];

 - 5b. Give an example of an array with three elements in it.
var myArray = [1, 2, 3];

 - 5c. How do you add another element to this array?
var myArray = [1, 2, 3];

myArray = [3, 5, 6];

 - 5d. How do you get the length of this array?
var myArray = [1, 2, 3];

myArray = [myArray.length];

 - 5e. Show how to iterate through the array using a loop.
var myArray = [1, 2, 3];

for (var i = 0; i < myArray.length; i++) {
  console.log(myArray[i]);
}


6. Objects
 - 6e. Give an example of an empty object.
 var myObjects = {

 };

 - 6b. Give an example of an object with three keys and three values.
 var myObjects = {
   name: "Kevin",
   surname: "Fung",
   age: 28
 };

 - 6c. Give an example of an object with two keys and two functions as values.
 var myObjects = {
   name: "Kevin",
   surname: "Fung"
 };

 function newObjects(myObjects) {
   console.log(myObjects.name + myObjects.surname);
 }

 newObjects();

 - 6d. Describe one way of adding a key to an object.
  var myObjects = {
    key1: value1,
    key2: value2
  };
  myObjects.key3;

 - 6e. Describe the other way of adding a key to an object.
 var myObjects = {
   key1: value1,
   key2: value2
 };
 myObjects.key3 = "value3";

 - 6f. Explain the difference between these two ways, and when it is appropriate to use each way.
 I don't know

 - 6g. Describe how to iterate though an object using a loop.

after the object put the loop in to the { for (var i = 0; i < myObjects; i++){

  }}


---
### Part 3: Algorithms - 20 minutes

7. What is an algorithm?
  I dont' know

8. For the following problem, first write down how exactly to solve the problem in English. Once you are able to describe it in English, translate it into code.

```js
// Given an array of values, write a function that finds the index of where the value is located, and if nothing is found, returns -1.
// Do not use the indexOf function.
// example: for ['apple', 'orange', 'pineapple']
	// 'orange' returns '1'
	// 'durian' returns '-1'
```

9. Again, for the following problem, first write down how exactly to solve the problem in English. Once you are able to describe it in English, translate it into code.

```js
// Write a function that finds all the indexes of where the value is located and returns them in an array, and if nothing is found, returns -1
// example: ['apple', 'orange', 'orange', 'pineapple']
	// 'orange' returns [1,2]
```
