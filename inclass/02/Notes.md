# Lesson 3 Java Script Intro + Version Control
let creates a variable that can change later
let score =10;
score = 15;
const creates a variable that cannot be reassigned
const pi = 3.14

# Assignment and Compound Assignment

# basic
let x = 5;

# Compound

x+=2; // x = x + 2
x -= 1; //x = x -1
x *=3; // x = x *3
x /= 2; // x = x / 2

# Concatenation
let name = "Joshua";
console.log("Hello, " + name + "!");

# Template Literals
console.log('Hello, ${name}!');

# JavaScript Can perform normal math:
let total = 10 + 5 * 2;

# To format decimals

let price = 3.4567;
console.log(price.toFixed(2)); // "3.46"

# converting strings to numbers

user input can come in as strings and must be converted

Converts to a whole number
parseInt()

parseInt("42"); // 42

Converts to a decimal
parseFloat()

parseFloat("3.14"); // 3.
14

if not javascript will teat the values as text

# Using typeof

typeof 42; // "number"
typeof "hello"; // "string"
typeof true; // "boolean"
typeof Nan; // "number" 

# Key differences: Strings vs Numbers

Strings combine using concatenation:
"2" + "3"  -> "23"
2 + 3 -> 5

# Version Control (Git + Hub)

Git tracks changes to code
-stores your code online
Commit changes with messages describing what was done
push commits to github repo
pull updates when working on multiple machines
forking workbook
cloning it
editing VS code
Committing and pushing notes




