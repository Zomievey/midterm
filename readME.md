1. Where is the most appropriate place to nest a script tag in an HTML file?

a. Nested inside the head section, at the very bottom.
--->>b. Nested inside the body tag, at the very bottom.
c. Nested inside the body tag, at the very top.
d. It doesn't matter where the script tag is placed.

---

2.Briefly describe which of these options is more appropriate for constructing a navbar?

<body>
    <header>
        <nav>This is the nav element></nav>
    </header>
</body>     
OR   
<body>
    <div>
        <nav>This is the nav element></nav>
    </div>
</body>

## Answer: the first option is correct because it used the correct <nav> tag used to create a navbar.

3.In CSS, what is the difference between "em"s and "rem"s?

## Answer: ems are font sizes in relation to the parent, so if you you had a parent of 1em (16px) and a child 2em, the font size of would be 32px inside of the nested element, they also compound as you nest.

## rem is sizes fonts by the root em ( html element), so the font size will be consistent throughout .

## also, ems and rems can be used in padding and margin as well and will base off the parent font size or the root font size and can be used to scale and space elements properly

4.What is the most specific CSS selector for the following HTML snippet?

<section class="main>   
    <div class="container></div>
</section>

a. div {}
b. section > div {}
---->c. .main > .container {}
d. .container {}

---

5. In one sentence, describe at least one way to center items in a div, using flexbox.
   div {
   display: flex;
   align-items: center;
   justify-content: center
   }

---

6. Which is the correct hierarchy of the Bootstrap container system?

a. <div class="container">

<div class="row col"></div>
</div>

.container>.row.col

---->b. <div class="container">

<div class="row'>
<div class="col-6"></div>
<div class="col-6"></div>
</div>
</div>

.container>.row>.col

c. <div class="container">

<div class="col">
<div class="row"></div>
</div>
</div>

.container>.col>.row

---

7. What does this for loop do?

For (let i=0; i < array.length; i++) {
console.log(array[i]);
}

a. logs the array to the developer console each time the loop runs

b. logs the string "hello world" to the console

---->c. logs the value of the current array index to the developer console

---

8. Briefly describe the different behaviors when using var, let, and const to declare variables in JavaScript.

## Answer: 1) var: hoisted (always declared at top of scope, global if none) - function scope 2) let: block scope - not re-declarable 3) const: block scope - not re-assignable - not re-declarable ; helps the JS engines compiler to decide on what to optimize.

9. This code snippet demonstrates ES6 syntax in JavaScript. What would the variable "results" equal?

let multiplyArr = (arr, num) => arr.map(index => index \* num);
let results = multiplyArr([1, 2, 3], 2);
console.log(results);

a. [1,2,3]
--->b. [2,4,6]
c. undefined
d. "results"

---

10. What would be the value of the sleep variable after the do/while loops has run?

let i = 0;
let amount = 10;
let sleep = '';

do {
sleep +- 'Z';
} while (i++ <amount);

---->a. "ZZZZZZZZZZ"
b. ""
c. 10
d. 0

---

11. In this code block, if userChoice was equal to "pizza" and userWallet equaled 100, what would be the output?

if (userChoice === 'pizza' && userWallet >= 150) {
console.log('Successfully ordered pizza!');
} else if (userChoice === 'hamburger' && userWallet >= 250) { console.log('Successfully ordered a hamburger!');
} else if (userChoice === 'taco' && userWallet >= 200) {
console.log('Successfully ordered a taco!');
} else {
console.log('Please select an option you can afford');
}

a. Successfully ordered pizza!
b. Successfully ordered a hamburger!
c. Successfully ordered a taco!
---->d. Please select an option you can afford.

---

12. What is the Document Object Model?

--->a. programming interface for HTML Documents
b. CSS framework
c. JavaScript framework for building applications
d. VS Code extension

---

13. Briefly describe what this code block does.

window.addEventListener("DOMContentLoaded", function() {
let div = document.createElement("div");
div.className = "container";
document.body.appenChild(div);
});

## Answer: when the page loads, it creates a div with the class name "container" and appends it to the body

14. Briefly describe what this code block does.

$('.demo').click(function () {
$(this).remove();
});

## Answer: Select something with the class of demo, and adds a click event listener to it, and when the element is clicked it removes the element

---

15. Describe the concept of hoisting in JavaScript. Specifically how it applies when using var, let, and const, also in functions.

## Answer: A variable can be used before it been declared with Var, Arrow functions don't get hoisted, Let and Const do not get hoisted

---

16. Why does this function use the "return" instead of console.logging?

function square(x) {
return x \* y;
}

## Answer: Return takes the value and returns it to the place where the function was called, console.log only logs it to the debugging terminal

---

17. In two or three sentences, describe the concept of scope in JavaScript

## Answer: The context of the is local and global, and determines by the code block {}

---

18. What is the correct use of the bind method in this code snippet?

function sayHello(name, age) {
console.log(
'Hello ${name}, my name is ${this.name} and I am ${age} years old');
}

const greeter = sayHello.bind({ name: 'John' });

---->a. Binding the context of "this" to the object passed to the bind method.
b. Edits the name variable passed to the original sayHello function.
c. Creating an object called name and adding a property called name with a value of "John".

---

19. Which scope will the "name" variable be available at?

function makeFunc() {
let name = 'Covalence';

    function displayName() {
        alert(name);
    }

    return displayName;

}

let myFunc = makeFunc();

myFunc();

## Answer: The name variable will be available at the block scope of the function makeFunc

20. In one or two sentences, define Object Oriented Programming:

## Answer: style of programming characterized by the identification of classes of objects, closely linked with the methods in which they are associated.

21. Describe inheritance in Object Oriented Programming?

## Answer: extending one class off of another, and can pass properties from the parent class to the child class.

22. There will be 3 to 5 questions here that you will code yourself and paste the answers here. Please practice basic JavaScript (level 7 and 8) on codewars.com so you are prepared to solve these problems. You are welcome to ask for help in the co-working space when working on codewars problems!
