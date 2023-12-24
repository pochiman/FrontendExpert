# Frontend Quiz

Our practice exam to validate your frontend knowledge.

The best way to assess your frontend knowledge.

This quiz is meant to test your frontend knowledge; it's not meant to reflect a real frontend interview.

The quiz is difficult. We recommend going through all of the Crash Courses on FrontendExpert first.

# Question 1 / 50
What would the following code log?

(function(num) {
  (function(num) {
    console.log(num * 2);
  })(5);
})(10);

undefined
20
error
10

# Question 2 / 50
What is returned by the fetch function?

A FormData object
A string
undefined
A Promise object

# Question 3 / 50
The root <html> element has a font size of 16px. A <div> inside of the root has a font size of 1.5rem. A direct child of that div has a font size of 2em. What is the font size of the child in pixels?

48px
32px
16px
24px

# Question 4 / 50
What data structure does the DOM use as the primary representation of the document?

Tree
Linked List
Hash Table
Graph

# Question 5 / 50
Why is let generally preferred over var for declaring variables?

var was deprecated in ES6.
let is function scoped, which is less bug prone than the block scoped var.
let was introduced with a more efficient garbage collector, making it far more performant than var.
let is block scoped, which is less bug prone than the function scoped var.

# Question 6 / 50
What is the purpose of a CSS media query?

To modify the page style based on the features of the user's device, such as screen sizes.
To provide styling information about external media, such as images included in the HTML markup.
To include syntax from CSS preprocessors, such as Sass.
To include external media in the CSS, such as images.

# Question 7 / 50
Consider the following code, what would be the output?

function mystery() {
  let num = 0;
  return { getNum: () => num, increment: () => num++ };
}
const { getNum, increment } = mystery();
const { getNum: getNum2, increment: increment2 } = mystery();
increment();
increment();
increment2();
console.log(getNum(), getNum2());

undefined, undefined
1, 2
3, 3
2, 1

# Question 8 / 50
What is meant by event bubbling?

Events start at the lowest elements before triggering event handlers on their parents.
Events only trigger on the highest relevant element in the DOM to avoid a single event triggering too many handlers.
Events only trigger on the lowest relevant element in the DOM to avoid a single event triggering too many handlers.
Events start at the highest elements before triggering event handlers on the children.

# Question 9 / 50
What is the purpose of a CSS preprocessor?

They convert CSS files into binaries, improving browser performance.
They add extra features to CSS making the code easier to read, write and maintain.
They provide pre-built components that can be used to quickly build high quality designs.
They provide pre-written stylesheets that can be added to webpages to create better default designs.

# Question 10 / 50
Which of the following are benefits of the defer attribute of script tags?

The script will wait for the browser to finish parsing the HTML file before downloading.
The script is loaded in the background rather than blocking the browser.
The script will have access to a constructed DOM without having to wait for a load event.
The script will run once it is done being loaded, rather than waiting for the browser to finish parsing the HTML file.

# Question 11 / 50
Which of the following could appear as fields in an accessibility tree node?

Role
State
Name
Description

# Question 12 / 50
What does the following code log?

const obj = {
  website: 'AlgoExpert',
  logWebsite: () => console.log(this.website)
};
obj.logWebsite();

Undefined
AlgoExpert
Null
Error

# Question 13 / 50
What is the purpose of the [[Prototype]] property of objects?

It contains an array of objects that the object inherits from.
It contains a blueprint for any objects that inherit from the object.
It contains the constructor function for defining the effects of using the new keyword with the object.
It contains a reference to the object that the object inherits from.

# Question 14 / 50
Given the following CSS, what would be the text color of a paragraph with the class "blue" and the id "red"?

* { color: black; }

.blue { color: blue; }

#red { color: red; }

p.blue { color: purple; }

Blue
Red
Purple
Black

# Question 15 / 50
Which of the following would be strictly equal to mysteryProto?

class Mystery {}
const mysteryProto = Object.getPrototypeOf(Mystery);

Function.prototype
Class.prototype
Mystery.prototype
Object.prototype

# Question 16 / 50
Consider the following stacking context hierarchy and z-indexes. What would be the order of the elements on the z-axis from bottom to top?

root
├── Container One: z-index: 1
│   ├── Element A: z-index: 3
│   └── Element B: z-index: 5
└── Container Two: z-index: 2
    ├── Element C: z-index: 6
    └── Element D: z-index: 4

A, B, D, C
A, D, B, C
C, D, B, A
C, B, D, A

# Question 17 / 50
Which of the following are effects of adding type=module to a <script> tag?

The script will be executed in strict mode.
The script will be able to use the import and export keywords.
Top level identifiers are only accessible within the script.
The script will be deferred, similar to adding a defer attribute.

# Question 18 / 50
Given the following CSS, what would be the width of the content of #mystery?

#mystery {
  box-sizing: border-box;
  width: 100px;
  border: 10px solid black;
  padding: 5px;
}

90px
70px
85px
100px

# Question 19 / 50
Which of the following Array functions returns a new array?

splice
sort
reverse
slice

# Question 20 / 50
Which of the following will result in a value of true?

[] == []
'abc' == 'abc'
null == undefined
{} == {}

# Question 21 / 50
Consider the following code, what would be the order of console logs?

for (var i = 0; i < 3; i++) {
  setTimeout(() => console.log(i), 0); 
}

2, 2, 2
1, 2, 3
3, 3, 3
0, 1, 2

# Question 22 / 50
From inside to outside, what is the order of the components to the box model?

content, margin, padding, border
content, padding, border, margin
content, margin, border, padding
padding, content, border, margin

# Question 23 / 50
What is the difference between a pseudo-element and pseudo-class?

A pseudo-class styles a specific part of an element, while a pseudo-element styles an element based on its current state.
Pseudo-classes use :: which gives them a higher specificity than pseudo-elements, which use :.
Pseudo-elements use :: which gives them a higher specificity than pseudo-classes, which use :.
A pseudo-element styles a specific part of an element, while a pseudo-class styles an element based on its current state.

# Question 24 / 50
What is the difference between the div and section tags?

They both group semantically related content, however sections are for navigational landmarks, while divs are for smaller structural groupings.
Sections are a modern replacement for divs with more semantic meaning, and thus should always be used.
There is no difference, they are interchangable.
Sections provide semantic meaning for thematically related content, while divs have no semantic meaning by default.

# Question 25 / 50
What is the difference between the h1 and h2 tags?

H1 represents a primary heading, while h2 is a less important subheading.
H2 represents a primary heading, while h1 is a less important subheading.
H1 will always display with a larger font than h2.
H2 will always display with a larger font than h1.

# Question 26 / 50
Given the following code, what is the value of mystery?

const mystery = new Array(3)
  .fill(2)
  .map((x, y) => x + y)
  .filter(x => x % 2 === 0)

[4]
[3, 4, 5]
[2, 3, 4]
[2, 4]

# Question 27 / 50
What will the following code evaluate to?

const mystery = {
  num: 6,
  x: {
    z: 1,
  },
};
console.log(mystery.num > 5 ? mystery?.x?.y ?? 2 : mystery.x.y);

Error
1
2
6

# Question 28 / 50
What is a JavaScript engine?

A collection of APIs provided by the browser.
A virtual machine for running programs that have been compiled to the JavaScript bytecode.
The environment where JavaScript is run in the browser.
A program that executes JavaScript code, typically in a browser.

# Question 29 / 50
What is the purpose of adding this meta tag to the head of an HTML file?

<meta name="viewport" content="width=device-width, initial-scale=1" />

It defaults the page to being rendered in full screen mode.
It zooms out the page on smaller mobile phones, creating a responsive design automatically.
It prevents a default behavior where mobile phones zoom out the page. This allows for responsive CSS to work as intended.
It removes margins from the document, ensuring the page takes up the full viewport.

# Question 30 / 50
What is the order of logs of the following code?

Promise.resolve(1)
  .then(
    (value) => console.log(value * 2),
    (value) => console.log(value * 3)
  )
  .then(() => { throw new Error('Oh No!'); })
  .catch((error) => 3)
  .finally(() => console.log(4))
  .then(console.log);
console.log(7);

2, 3, 4, 7
2, 4, 3, 7
7, 2, 4, 4
7, 2, 4, 3

# Question 31 / 50
Given the following code, what will be logged to the console?

async function mystery() {
  return 2;
}
console.log(mystery());

2
A pending Promise with a value of 2.
A fulfilled Promise with a value of 2.
undefined

# Question 32 / 50
What is the purpose of an aria-label attribute?

It adds a text label above the element on the page.
It provides a description of the role of a generic element, which increases accessibility for users such as those using a screen reader.
Its value is an ID of a another tag, linking the element to its label.
It provides an invisible label for the element, which increases accessibility for users such as those using a screen reader.

# Question 33 / 50
What data structure does the event loop use to keep track of callbacks waiting to be executed?

Stack
Tree
Queue
Heap

# Question 34 / 50
What are the three states of promises?

not started, incomplete, complete
asynchronous, synchronous, undefined
success, failure, error
pending, fulfilled, rejected

# Question 35 / 50
What will be the value of mysteryTwo given the code below?

const arr = [2, 3, 4];
const [mysteryOne, ...rest] = arr;
const mysteryTwo = [...rest, ...arr, mysteryOne];

[3, 4, 2, 3, 4, 2]
[3, 2, 3, 3, 2]
[3, 4, 2, 2, 2]
[3, 4, 2, 2]

# Question 36 / 50
What would be the returned value of this code?

element.offsetHeight - element.clientHeight;

0
The combined height of any border and padding.
The combined height of any border and scrollbar.
NaN

# Question 37 / 50
What is the primary difference between an inline-block and an inline element?

There is no difference, inline-block is simply an alias for inline.
Inline-block elements can have their width and heights changed, while inline elements always have the width and height of their content.
Inline-block can only be used for images, while inline can be used on any HTML element.
Inline-block elements always start on a new line, while inline elements will be displayed on the same line as the elements before them if there is space.

# Question 38 / 50
What are the primary class types of BEM?

Bases, elements and modifiers
Blocks, elements and modifiers
Bases, elements and modules
Blocks, elements and modules

# Question 39 / 50
Which of the following are benefits of image sprites?

They scale to larger screen sizes with less quality loss than traditional images.
They can decrease total page load times.
They minimize the number of image files the client needs to download.
They make the HTML markup more semantic than traditional images.

# Question 40 / 50
Which of the following would cause an entire JavaScript file to be executed in strict mode?

Using the defer attribute on the <script> tag.
Adding the string "use strict" to the top of the file.
Calling the useStrict() function at the top of the file.
Using the type="module" attribute on the <script> tag.

# Question 41 / 50
How many columns will a CSS grid with the following CSS have?

display: grid;
grid-template-columns: [start] auto repeat(3, 1fr) 30% [end];

4
7
5
3

# Question 42 / 50
Which of the following are properties of a flexbox item?

flex-shrink
flex-basis
align-content
flex-direction

# Question 43 / 50
What is the effect of this line of code?

requestAnimationFrame(myFunction);

It will have no effect since a delay parameter was not passed.
It calls myFunction before the next repaint.
It calls myFunction exactly 60 times per second.
It calls myFunction before each repaint until cancelAnimationFrame(myFunction) is called.

# Question 44 / 50
What is meant by a curried function?

A function converted to use arrow functions and modern JavaScript features.
A function transformed to have its parameters treated as a sequence of function calls that each have a single parameter.
A function that is not reliant on the "this" context it was defined in.
A function with no side effects or parameters.

# Question 45 / 50
What is the purpose of the array reduce function?

It creates a new array by calling a callback function on every element and saving the return value.
It converts the array into a single value by running a callback function on each value of the array, passing the return value of each iteration as an argument to the next iteration.
It reduces the array to a single boolean value based on if every value in the array returns true for a callback function.
It creates a new array that only contains values that return true for a passed callback function.

# Question 46 / 50
What will the following code output?

function* generator() {
  const value = yield 2;
  yield value + 3;
  yield value + 5;
}
const generatorObj = generator();
console.log(generatorObj.next(3).value);
console.log(generatorObj.next(5).value);
console.log(generatorObj.next(7).value);

2, 6, 10
2, 6, 12
2, 8, 12
2, 8, 10

# Question 47 / 50
Which tag is required in every HTML file?

<title>
<heading>
<main>
<h1>

# Question 48 / 50
What will the following code evaluate to?

[2, 1, 4, 3].sort((val1, val2) => {
  return val2 - val1;
});

[2, 1, 4, 3]
[1, 2, 3, 4]
[4, 3, 2, 1]
[3, 4, 1, 2]

# Question 49 / 50
What would the CSS selector article.mystery > section select?

All section tags directly nested within an article of class mystery.
All article tags with a class of mystery and a section child.
All article tags with class mystery directly nested within a section.
All section tags that are siblings of an article with class mystery.

# Question 50 / 50
If an element was set to position: relative with top: 10, where will the element be positioned?

10px from the bottom of the browser window.
10px above where it would have been positioned naturally with position: static.
10px below where it would have been positioned naturally with position: static.
10px from the top of the browser window.
