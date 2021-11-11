1. Where is the most appropriate place to nest a script tag in an HTML file?

a. Nested inside the head section, at the very bottom.
b. Nested inside the body tag, at the very bottom.
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
---
3.In CSS, what is the difference between "em"s and "rem"s?

---

4.What is the most specific CSS selector for the following HTML snippet?

<section class="main>   
    <div class="container></div>
</section>

a. div {}
b. section > div {}
c. .main > .container {}
d. .container {}

---

5. In one sentence, describe at least one way to center items in a div, using flexbox.

---

6. Which is the correct hierarchy of the Bootstrap container system?

a. <div class="container">

<div class="row col"></div>
</div>

.container>.row.col

b. <div class="container">

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

c. logs the value of the current array index to the developer console

---

8. Briefly describe the different behaviors when using var, let, and const to declare variables in JavaScript.

---

9. This code snippet demonstrates ES6 syntax in JavaScript. What would the variable "results" equal?

let multiplyArr = (arr, num) => arr.map(index => index \* num);
let results = multiplyArr([1, 2, 3], 2);
console.log(results);

a. [1,2,3]
b. [2,4,6]
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

a. "ZZZZZZZZZZ"
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
d. Please select an option you can afford.

---

12. What is the Document Object Model?

a. programming interface for HTML Documents
b. CSS framework
c. JavaScript framework for building applications
d. VS Code extension

---

13. Briefly describe what this code bloack does.

window.addEventListener("DOMContentLoaded", function() {
let div = document.createElement("div");
div.className = "container";
document.body.appenChild(div);
});

---

14. Briefly describe what this code block does.

$('.demo').click(function () {
$(this).remove();
});

---

15. Describe the concept of hoisting in JavaScript. Specifically how it applies when using var, let, and const, also in functions.

---

16. Why does this function use the "return" instead of console.logging?

function square(x) {
return x * y;
}

---

17. In two or three sentences, describe the concept of scope in JavaScript

---

18. What is the correct use of the bind method in this code snippet?

function sayHello(name, age) {
console.log(
'Hello ${name}, my name is ${this.name} and I am ${age} years old');
}

const greeter = sayHello.bind({ name: 'John' });

a. Binding the context of "this" to the object passed to the bind method.
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

---

20. In one or two sentences, define Object Oriented Programming

---

21. There will be 3 to 5 questions here that you will code yourself and paste the answers here. Please practice basic JavaScript (level 7 and 8) on codewars.com so you are prepared to solve these problems. You are welcome to ask for help in the co-working space when working on codewars problems!
