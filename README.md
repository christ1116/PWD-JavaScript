# Js Home #
<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>

# Js Introduction #
<p id="demo">JavaScript can change HTML content.</p>
<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>

# Js Where to #
<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
</script>

# Js Output #
<script>
document.getElementById("demo").innerHTML = "<h2>Hello World</h2>";
</script>

# Js Statement #
<h2>JavaScript Statements</h2>

<p>A <b>JavaScript program</b> is a list of <b>statements</b> to be executed by a computer.</p>

<p id="demo"></p>

<script>
let x, y, z;  // Statement 1
x = 5;        // Statement 2
y = 6;        // Statement 3
z = x + y;    // Statement 4

document.getElementById("demo").innerHTML =
"The value of z is " + z + ".";  
</script>

# Js Syntax #
// How to create variables:
var x;
let y;

// How to use variables:
x = 5;
y = 6;
let z = x + y;

# Js Comments #
<h1 id="myH"></h1>
<p id="myP"></p>

<script>
// Change heading:
document.getElementById("myH").innerHTML = "JavaScript Comments";
// Change paragraph:
document.getElementById("myP").innerHTML = "My first paragraph.";
</script>

# Js Variables #
<h1>JavaScript Variables</h1>

<p>In this example, x, y, and z are undeclared.</p>
<p>They are automatically declared when first used.</p>

<p id="demo"></p>

<script>
x = 5;
y = 6;
z = x + y;
document.getElementById("demo").innerHTML =
"The value of z is: " + z;
</script>

# Js Let #
<h2>Redeclaring a Variable Using let</h2>

<p id="demo"></p>

<script>
let  x = 10;
// Here x is 10

{  
  let x = 2;
  // Here x is 2
}

// Here x is 10
document.getElementById("demo").innerHTML = x;
</script>

# Js Const #
<h2>JavaScript const</h2>

<p id="demo"></p>

<script>
try {
  const PI = 3.141592653589793;
  PI = 3.14;
}
catch (err) {
  document.getElementById("demo").innerHTML = err;
}
</script>

# Js Operators # 
<h1>JavaScript Operators</h1>
<h2>The = Operator</h2>

<p id="demo"></p>

<script>
let x = 10;
document.getElementById("demo").innerHTML = x;
</script>

# Js Arithmetics #
<h2>JavaScript Arithmetic</h2>
<p>A typical arithmetic operation takes two numbers and produces a new number.</p>

<p id="demo"></p>

<script>
let x = 100 + 50;
document.getElementById("demo").innerHTML = x;
</script>

# Js Data Type #
// Numbers:
let length = 16;
let weight = 7.5;

// Strings:
let color = "Yellow";
let lastName = "Johnson";

// Booleans
let x = true;
let y = false;

// Object:
const person = {firstName:"John", lastName:"Doe"};

// Array object:
const cars = ["Saab", "Volvo", "BMW"];

// Date object:
const date = new Date("2022-03-25");

# Js Functions #
<h1>JavaScript Functions</h1>

<p>Call a function which performs a calculation and returns the result:</p>

<p id="demo"></p>

<script>
function myFunction(p1, p2) {
  return p1 * p2;
}

let result = myFunction(4, 3);
document.getElementById("demo").innerHTML = result;
</script>

# Js Objects # 
<h1>JavaScript Variables</h1>
<h2>Creating a Variable</h2>
<p id="demo"></p>

<script>
// Create and a Variable:
let car = "Fiat";
document.getElementById("demo").innerHTML = "Car: " +  car;
</script>

# Js Object Properties #
<h1>JavaScript Object Properties</h1>
<h2>Access a Property with .</h2>

<p id="demo"></p>

<script>
const person = {
  firstname: "John",
  lastname: "Doe",
  age: 50,
  eyecolor: "blue"
};

document.getElementById("demo").innerHTML = person.firstname + " is " + person.age + " years old.";
</script>

# Js Object Methods #
<h1>JavaScript Objects</h1>
<h2>Object Methods</h2>
<p>A method is a function definition stored as a property value.</p>

<p id="demo"></p>

<script>
const person = {
  firstName: "John",
  lastName: "Doe",
  id: 5566,
  fullName: function() {
    return this.firstName + " " + this.lastName;
  }
};

document.getElementById("demo").innerHTML = person.fullName();
</script>

# Js Object Display #
<h1>JavaScript Objects</h1>
<p>Displaying a JavaScript object will output [object Object]:</p>

<p id="demo"></p>

<script>
// Create an Object
const person = {
  name: "John",
  age: 30,
  city: "New York"
};

// Display Object
document.getElementById("demo").innerHTML = person;
</script>

# Js Object Constructors #
<h1>JavaScript Object Constructors</h1>

<p id="demo"></p>

<script>
// Constructor Function for Person objects
function Person(first, last, age, eye) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eye;
}

// Create a Person object
const myFather = new Person("John", "Doe", 50, "blue");

// Display age
document.getElementById("demo").innerHTML =
"My father is " + myFather.age + "."; 
</script>

# Js Events #
<h1>JavaScript HTML Events</h1>
<h2>The onclick Attribute</h2>

<button onclick="document.getElementById('demo').innerHTML=Date()">The time is?</button>

<p id="demo"></p>

# Js Strings #
<h1>JavaScript Strings</h1>

<p id="demo"></p>

<script>
let text = "John Doe";  // String written inside quotes
document.getElementById("demo").innerHTML = text;
</script>

# Js String Method #
<h1>JavaScript Strings</h1>
<h2>The length Property</h2>

<p>The length of the string is:</p>
<p id="demo"></p>

<script>
let text = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
document.getElementById("demo").innerHTML = text.length;
</script>

# Js String Search #
<h1>JavaScript Strings</h1>
<h2>The indexOf() Method</h2>

<p>The indexOf() method returns the position of the first occurrence of a string in a string.</p>
<p>The position of the first occurrence of "locate" is:</p>
<p id="demo"></p>

<script>
let text = "Please locate where 'locate' occurs!";
let index = text.indexOf("locate");
document.getElementById("demo").innerHTML = index; 
</script>

# Js String Templates #
<h1>JavaScript Template Strings</h1>
<p>Templates use back-ticks (``) to define a string:</p>

<p id="demo"></p>

<p>Templates are not supported in Internet Explorer.</p>

<script>
let text = `Hello world!`;
document.getElementById("demo").innerHTML = text;
</script>


# Js Numbers # 
<h2>JavaScript Numbers</h2>

<p>Numbers can be written with or without decimals:</p>

<p id="demo"></p>

<script>
let x = 3.14;
let y = 3;
document.getElementById("demo").innerHTML = x + "<br>" + y;
</script>

# Js Biglnt #
<h1>JavaScript Numbers</h1>
<h2>Integer Precision</h2>

<p>Integers (numbers without a period or exponent notation) are accurate up to 15 digits:</p>

<p id="demo"></p>

<script>
let x = 999999999999999;
let y = 9999999999999999;
document.getElementById("demo").innerHTML = x + "<br>" + y;
</script>

# Js Number Methods #
<h2>JavaScript Number Methods</h2>

<p>The toString() method converts a number to a string.</p>

<p id="demo"></p>

<script>
let x = 123;
document.getElementById("demo").innerHTML =
  x.toString() + "<br>" +
   (123).toString() + "<br>" +
   (100 + 23).toString();
</script>


# Js Number Properties #
<h1>JavaScript Numbers</h1>
<h2>The EPSILON Property</h2>

<p>The difference between 1 and the smallest floating point number greater than 1, in JavaScript is:</p>
<p id="demo"></p>

<script>
let x = Number.EPSILON;
document.getElementById("demo").innerHTML = x;
</script>

# Js Arrays # 
<h1>JavaScript Arrays</h1>

<p id="demo"></p>

<script>
const cars = ["Saab", "Volvo", "BMW"];
document.getElementById("demo").innerHTML = cars;
</script>

# Js Array Method #
<h1>JavaScript Arrays</h1>
<h2>The length Property</h2>

<p>The length property returns the length of an array:</p>

<p id="demo"></p>

<script>
const fruits = ["Banana", "Orange", "Apple", "Mango"];
let size = fruits.length;
document.getElementById("demo").innerHTML = size;
</script>

# Js Array Search #
<h1>JavaScript Arrays</h1>
<h2>The indexOf() Method</h2>

<p id="demo"></p>

<script>
const fruits = ["Apple", "Orange", "Apple", "Mango"];
let position = fruits.indexOf("Apple") + 1;

document.getElementById("demo").innerHTML = "Apple is found in position " + position;
</script>

# Js Array Sort #
<h1>JavaScript Arrays</h1>
<h2>The sort() Method</h2>

<p>The sort() method sorts an array alphabetically:</p>

<p id="demo1"></p>
<p id="demo2"></p>

<script>
const fruits = ["Banana", "Orange", "Apple", "Mango"];
document.getElementById("demo1").innerHTML = fruits;

fruits.sort();
document.getElementById("demo2").innerHTML = fruits;
</script>

# Js Array Iteration #
<h1>JavaScript Arrays</h1>
<h2>The forEach() Method</h2>

<p>Call a function once for each array element:</p>

<p id="demo"></p>

<script>
const numbers = [45, 4, 9, 16, 25];

let txt = "";
numbers.forEach(myFunction);
document.getElementById("demo").innerHTML = txt;

function myFunction(value, index, array) {
  txt += value + "<br>"; 
}
</script>

# Js Array Const #
<h2>JavaScript const</h2>
<p id="demo"></p>

<script>

const cars = ["Saab", "Volvo", "BMW"];
document.getElementById("demo").innerHTML = cars;

</script>

# Js Dates #
<h1>JavaScript Dates</h1>
<h2>Using new Date()</h2>

<p id="demo"></p>

<script>
const d = new Date("2022-03-25");
document.getElementById("demo").innerHTML = d;
</script>

# Js Date Formats #
<h2>JavaScript ISO Dates</h2>

<p id="demo"></p>

<script>
const d = new Date("2015-03-25");
document.getElementById("demo").innerHTML = d;
</script>

# Js Date Get Methods #
<h1>JavaScript Dates</h1>
<h2>Using new Date()</h2>
<p>Create a new date object with the current date and time:</p>

<p id="demo"></p>

<script>
const d = new Date();
document.getElementById("demo").innerHTML = d;
</script>


# Js Date Set Methods #
<h1>JavaScript Dates</h1>
<h2>The setFullYear() Method</h2>
<p>The setFullYear() method sets the year of a date object.</p>

<p id="demo"></p>

<script>
const d = new Date("January 01, 2025");
d.setFullYear(2020);
document.getElementById("demo").innerHTML = d;
</script>

# Js Math #
<h2>JavaScript Math.PI</h2>

<p>Math.PI returns the ratio of a circle's circumference to its diameter:</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = Math.PI;
</script>

# Js Random # 
<h2>JavaScript Math.random()</h2>

<p>Math.random() returns a random number between 0 (included) and 1 (excluded):</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = Math.random();
</script>

# Js Booleans #
<h1>JavaScript Booleans</h1>
<p>Display the value of Boolean(10 > 9):</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = Boolean(10 > 9);
</script>


# Js Comparisons # 
<h1>JavaScript Comparison</h1>
<h2>The () ? : Ternary Operator</h2>

<p>Input your age and click the button:</p>

<input id="age" value="18" />

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
  let age = document.getElementById("age").value;
  let voteable = (age < 18) ? "Too young":"Old enough";
  document.getElementById("demo").innerHTML = voteable + " to vote.";
}
</script>

# Js if else #
<h2>JavaScript if</h2>

<p>Display "Good day!" if the hour is less than 18:00:</p>

<p id="demo">Good Evening!</p>

<script>
if (new Date().getHours() < 18) {
  document.getElementById("demo").innerHTML = "Good day!";
}
</script>

# Js Switch #
<h2>JavaScript switch</h2>

<p id="demo"></p>

<script>
let day;
switch (new Date().getDay()) {
  case 0:
    day = "Sunday";
    break;
  case 1:
    day = "Monday";
    break;
  case 2:
    day = "Tuesday";
    break;
  case 3:
    day = "Wednesday";
    break;
  case 4:
    day = "Thursday";
    break;
  case 5:
    day = "Friday";
    break;
  case  6:
    day = "Saturday";
}
document.getElementById("demo").innerHTML = "Today is " + day;
</script>

# Js Loop For #
<h2>JavaScript For Loop</h2>

<p id="demo"></p>

<script>
const cars = ["BMW", "Volvo", "Saab", "Ford", "Fiat", "Audi"];

let text = "";
for (let i = 0; i < cars.length; i++) {
  text += cars[i] + "<br>";
}

document.getElementById("demo").innerHTML = text;
</script>

# Js Loop For In #
<h2>JavaScript For In Loop</h2>
<p>The for in statement loops through the properties of an object:</p>

<p id="demo"></p>

<script>
const person = {fname:"John", lname:"Doe", age:25}; 

let txt = "";
for (let x in person) {
  txt += person[x] + " ";
}

document.getElementById("demo").innerHTML = txt;
</script>

# Js Loop For Of #
<h2>JavaScript For Of Loop</h2>
<p>The for of statement loops through the values of any iterable object:</p>

<p id="demo"></p>

<script>
const cars = ["BMW", "Volvo", "Mini"];

let text = "";
for (let x of cars) {
  text += x + "<br>";
}

document.getElementById("demo").innerHTML = text;
</script>

# Js Loop While #
<h2>JavaScript While Loop</h2>

<p id="demo"></p>

<script>
let text = "";
let i = 0;
while (i < 10) {
  text += "<br>The number is " + i;
  i++;
}
document.getElementById("demo").innerHTML = text;
</script>
