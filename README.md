# DocumentForJavascript

//Javascript tutorial basics and knowhow
//By Skitty

//facts

//javascript is the most popular programming language.
//javascript is really useful for building websites and applications.
//javascript is one of the most powerfull programming languages and easiest to learn.
//javascript is the only client side language
//javascript is an interpreted language

//basics

//A JavaScript function is a block of code designed to perform a particular task. 
//A JavaScript function is executed when "something" invokes it (calls it).
//Example
function addTwoNumbers(x, y) {
    return x + y;
}
//That is a basic javascript function
//function is the keyword that starts declaring a function.
//addTwoNumbers is the function’s name, which is customizable — just like variable names.
//(x, y) are parameters, variable names for the inputs a function will accept.
//return is the keyword that exits the function and shares an optional value outside.
//Once a function is defined, you can use it by referencing its name with parentheses () right after.
//Note that a function doesn’t have to have parameters.
//Example
function greetThePlanet() {
    return "Hello world!";
}

greetThePlanet();

OUTPUT:
"Hello world!"
//If a function _does_ have parameters, you’ll need to provide values inside the parentheses when using the function.
//Example
function square(number) {
       return number * number;
}
​
square(16);

OUTPUT:
256

//Strings are values made up of text and can contain letters, numbers, symbols, punctuation, and even emoji.
//Strings are contained within a pair of either single quotation marks '' or double quotation marks "".
//Example
'This is a string. 👏';
"This is the 2nd string. 💁";
//Enclosing quotation marks
//Let’s say you’re trying to use quotation marks inside a string. You’ll need to use opposite quotation marks inside and outside. That means strings containing single quotes need to use double quotes and strings containing double quotes need to use single quotes.
//Example
"It's six o'clock.";
'Remember to say "please" and "thank you."';
//Alternatively, you can use a backslash \ to escape the quotation marks. This lets JavaScript know in advance that you want to use a special character.
//Here’s what that looks like reusing the examples above:
//Example
'It\'s six o\'clock.';
"Remember to say \"please\" and \"thank you.\"";
//Properties and methods
//Strings have their own built-in variables and functions, also known as properties and methods. Here are some of the most common ones.

//length
//A string’s length property keeps track of how many characters it has.
//Example
"caterpillar".length;

OUTPUT:
11
toLowerCase

//A string’s toLowerCase method returns a copy of the string with its letters converted to lowercase. Numbers, symbols, and other characters are not affected.
//Example
"THE KIDS".toLowerCase();
OUTPUT
"the kids"
toUpperCase
//A string’s toUpperCase method returns a copy of the string with its letters converted to capitals. Numbers, symbols, and other characters are not affected.
//Example
"I wish I were big.".toUpperCase();

OUTPUT:
"I WISH I WERE BIG."
trim
//A string’s trim method returns a copy of the string with beginning and ending whitespace characters removed.
//Example
"   but keep the middle spaces   ".trim();

OUTPUT:
"but keep the middle spaces"
//Booleans are values that can be only one of two things: true or false.
//Anything “on” or “off,” “yes” or “no,” or temporary is a usually good fit for a boolean. It’s useful to store booleans in variables to keep track of their values and change them over time.
//Example
var kitchenLights = false;
kitchenLights = true;
kitchenLights;

OUTPUT:
true

//Booleans are essential for conditionals to work.
//Numbers are values that can be used in mathematical operations. You don’t need any special syntax for numbers — just write them straight into JavaScript.
//Example
12345;

//Decimals and fractions
//JavaScript doesn’t distinguish between whole numbers and decimals, so you can use them together without having to convert from one to the other.
//Example
10 + 3.14159;

OUTPUT:
13.14159

//Fractions don’t exist in JavaScript, but you can rewrite them as division problems using the division operator /. Note that the resulting number is always converted to decimals — just like with a calculator.
//Example
1 / 3;

OUTPUT:
0.3333333333333333

//Improper fractions use the division operator in the same way.
//Example
11 / 10;

OUTPUT:
1.1

//To use mixed numbers, you need to add the whole number and fraction.
//Example
1 + (4 / 3);

OUTPUT:
2.333333333333333

//Negative numbers
//You can make a number negative by placing the - operator in front.
//Example
-3;

OUTPUT:
-3;

//You can also get a negative number by subtracting a number from a smaller number.
//Example
5 - 7;

OUTPUT:
-2

//knowhow

//When you load into a page on the internet your computer sends a folder of files including atleast 1 html file.
//The html file would include: <html><body><script src="/NameOfFile.js"/></body></html> it wont be like that but going down instead
//To use javascript you would need a script tag which looks like this: <script></script>
//Javascript is the only client side language meaning that it waits to execute code until its on your computer using a program called the browser
//Each browser has its own engine like safari uses an engine called webkit firefox uses gecko and chrome uses v8
//Javascript can change the display change data or fetch more data
//Javascript uses client side frameworks like: React Angular Vue, Svelte.
//Frameworks build ontop of javascript and make reading the client side code alot easier and more maintainable.
//traditionally javascript is an interpreted language meaning which means the code is read line by line instead of going through a compile setup.
//A compile setup is where its converted to the machine

