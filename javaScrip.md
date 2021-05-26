# JavaScript
In JavaScript, everything is an object. JavaScript is the world's most popular programming language. it is most recognized as the scripting language for Web pages.

-------

## History of JavaScript

The company Netscape Navigator was developed in 1995 and it was the first browser in the market. but at that time Microsoft and Apple were also in the race. Netscape Navigator was a paid software then also it was very popular because people can view websites on that. lots of companies buying this browser and started their own websites. day by day Netscape was getting very much popularity. Microsoft noticed that Netscape Navigator becoming a very big company. Microsoft wanted to buy Netscape but denied it. Microsoft stole the IP of Netscape and they invented the Internet Explorer browser and gave it for free. People start using this free browser and Due to this Netscape navigator getting down within one to two years because it was paid software.  Then Netscape came to the inventor of the Java Sun microsystem because Java was a very powerful language for the backend but Java was missing the frontend part. Netscape Navigator and Sun Microsystem came together and the form aligns in that java will be a backend and live script will be scripted language for the frontend. They together wanted to fight the microsystem. Because of very high competition with the microsystem the Netscape developer, Brandon was given a task to create a new programming language within three weeks. He did some research and created a language called Mocha. He made lots of mistakes while creating it because he had less time. Then this language was launch on the Netscape browser. But when the browser is installed In the system then all the drawbacks are also installed in systems that are using Netscape.
To avoid mistakes and to make popularity live script and mocha change their name to JavaScript. and the language JavaScript was introduced. Then JavaScript language was standardized and available for everyone. They gave it to ECMA. Due to the name, java is own by sun microsystem ECMA can't use the name JavaScript so they adopted a name called ECMA Script. In 2002-2003 all big companies like google and yahoo started contributing to the JavaScript standards and community. Yahoo was the biggest contributor to JavaScript standardization. JavaScript becomes the most powerful language.   

--------------

## JavaScript Variables

* In JavaScript, variables are container which holds the data.
JavaScript is a dynamic type variable.
* In JavaScript variables are defined using var keyword.
* In JavaScript, you don’t have to compile variables you have to declare them and run them that’s the reason it is called dynamic.
* Following are the types of variables in JavaScript 

#### 1. Local Variable: 
a variable declared inside the function is called a local variable. It is accessible within the function only.
 
#### 2. Global variable: 
A variable declared outside the function is called a global variable. A JavaScript global variable is accessible from any function.

--------

## JavaScript Datatypes 

#### 1. Primitive datatype : 
once you defined it you can’t change it.
It’s a call by value 
 

| Datatype           | Description
|------------------------ |-------------
|`Strings`|holds a sequence of character.|
|`Number`| Represents a numerical value.|
|`Boolean` |It will give true or false values. |
|`Null` |holds null value.|
|`Undefined` |show undefined value.|
|`Symbol`| holds unique value.|


#### 2. Non Premitive datatypes:
It’s a call by reference.


| Datatype           | Description
|--------------------|-------------
|`Object` | In JavaScript objects can hold anything. It is denoted by {} curly braces. In JS everything is an object |
|`Array`|donated by [] square bracket. It is a collection of similar data types.  |
 
 -------------------------------------

## Difference between Var, Let, Const

| `Var`                    | `Let`           | `Const`
|--------------------|-------------------|----------------------
| It can be redeclared.|As per ES6 standard Let can not be redeclared.|As per ES6 standard Let can not be redeclared.|
|It can be re-initialized.|It can be re-initialized.|can't be re-initialized.|
| It has functional scope.|It has Lexical Scope.| It has Lexical scope.|
| It is used in Es5. |It is used in ES6.|It is used in ES6.|
| Var get hoisted. | Let does not get hoisted.|Const does not get hoisted.|


---------------------------------

## JavaScript Operators
Operators are used to perform operations on operands. following operators are used in JavaScript.

#### 1. Arithmetic Operators
| Operators         | Description |
|--------------------|------------- |
|+ |It is used to performs Addition. |
|-	 |It is used to performs Subtraction. |
|*	 | It is used to performs Multiplication. |
|/	 |It is used to performs Division. |
|%	 |Modulus. |
|++	 |It is used to performs Increment. |
|--  |It is used to performs Decrement. |

#### 2. Logical Operators

| Operators          | Description |
|--------------------|------------- |
|&& (Logical AND)    | If both the operands are true, then the condition becomes true.         |	
| Logical OR     |If any one operand are true, then the condition becomes true.|
|! (Logical NOT)     | It Reverses the state of operand. If a condition is true, then the Logical NOT operator will make it false.|


#### 3. Ternary Operator 

| Operators          | Description |
|--------------------|------------- |
|? : (Condition)|If Condition is true? Then it returns value A  : Otherwise value B|

---------------------


## Operations on Primitive and Non-Primitive 

#### Arithmetic opearations on primitive

```shell
undefined + undefined // NAN

Undefined + null // NAN

Undefined + number // NAN

Undefined + String // concat string

null + null // 0

```
-------------------------

```shell 
Var X = “70”;                
Var Y = “10”;
X + Y 

Output: “7010” 
```
-----------------
```shell 
Var X = 10;                
Var Y = 20;
X * Y 

Output: 20
```
-----------------

```shell 
Var num1 = true;      // true converted into one          
Var num2 = 200;
num1 + num 

Output : 200
```
--------------------------

```shell
Var num1 = null;      // JavaScript converts null value into false.        
Var num2 = 200;
num1 + num2 

Output : 200
```
-----------------------

```shell
Var X = undefined;
Var Y = 100;
X + Y ;

Output : NAN 
```
----------------------------
```shell
var X = 10 , Y = 20;
X && Y;   // both values are true.it ptrints last value

Output: 20
```
------------------------------
```shell
var X = 0, Y = 10;
X && Y;         //first condition is false so it will not check further.

Output : 0
```
---------------------
```shell
var num = 10; 
! num ;           // negation

output : false
```
--------------------------------
```shell
var num = 10; 
!! num ;       // typecaasting 

output: true
```
--------------------------
```shell 
if (10 && 20 && 30 && 50)
{
    console.log("Snehal");
}

output : Snehal

```
--------------------------------------------
#### Operations on Non primitive

```shell 
[] + [] 

Output :  " "

```
----------------------------
```shell 
[10] + [2,4,5] 

Output :  "10,2,4,5"

```
-----------------------------
```shell
" " + " "

Output : " "
```
------------------
```shell
if([] && 10)
{
    console.log("Snehal");

}
else 
{
    console.log("Raut");
}

Output : Snehal 
```
--------------------------
```shell 
if([] && " ")  
{
    console.log("Snehal");

}
else 
{
    console.log("Raut");
}

Output : Raut 
```
------------------------
## Functional Scope

It always starts with function. In JavaScript entire application itself is a functional scope and it has another functional scope inside. whenever we define JavaScript function the variables defined inside functions it will get hoisted at the top. The functional scope has its own global and local scope.

```shell
num = 200;          //variable declaration get hoisted
console.log(num) ;
var num = 100;

output : 200
```
------------

## Lexical Scope
The lexical scope has both local and global scope. It is always part of the functional scope. In lexical scope, a variable defined outside a function can be accessible inside another function defined after variable declaration. 

```shell
Function start()
    {
        Var X = ”Hello”;
        Var Y = “India”;
        Function stop()
            {
                Console.log(X);
                Console.log(Y);
            }
        Start()
    }
        Stop()
    }   


Output: Hello
        India 

```

------------------

## Call by Value and Call by Reference 

#### Call by value 
 Primitive types are call by value. variables become the same by copying the value to two different locations. Changes in one object variable don’t affect the other object variable.

 Example of call by value is Xerox, Photocopy.
 
 ```shell
        Var X = 200;
         Var Y=X;
         Console.log(Y)

Output: 200
```

#### Call by Reference 

 Non Primitive types are call by reference. It calls the variable by its reference. original and copied variables are created in the same memory location. Changes in one object variable affect the other object variable.

example of call by reference is a Google doc or sheet, when we send it to another we just share a link that is a reference of the document. 

```shell

Var X = { Role : 'Software Developer' };
    var Y;
    Y = X;
  
    c.Role = 'Project Manager';
    console.log(X);
    console.log(Y);


output: Project Manager
	    Project Manager

```
-----------------------

## Function 

In JavaScript function plays the main role. Functions are called the First-class citizen because it has all privileges. It has local and global scope. The function can assign to a variable. It can returns another function. It is defined by function keyword. In Es5 functions behave exactly like variable behavior.


#### Syntax
``` shell
Function function_name()   // define function
    {
        // executable code
    }
function_name();    // call function
```

---------------

Whenever you are declared the same function in ES5 it overrides it.
```shell
Function start()
    {
        Console.log(“ print start function”);
    }
Function start()
    {
        Console.log(“ print start function again ”);    // It returns last a value just like var
    }
Start();

Output : print start function again
```

---------------------

Function can be called before it has been declared 
```shell
Start();
Function start()
    {
        Console.log(“ print start function”);
    }

Output: print start function 
```
------------------

## Function declaration and Function assignment

#### Function declaration

The Function with function keyword and function name called the function declaration. In a function declaration, you can call a function before declare it. All the functions which have function declaration get hoisted. 

```shell
Start();
Function start()
    {
        console.log(“ Snehal Raut”);
    }

Output: Snehal Raut
```

#### Function assignment

In function assignment, you can’t call a function before the declaration. Function assignment does not get hoisted. In function, the assignment function does not have a name. It is called an anonymous function.


```shell
Var start = function()
    {
        console.log(“Hello India”);
    }
Start();

Output: Hello India

```
------------

## Higher order function 

Any function which take function as a parameter and/or returns a function is called Higher order function. It is used to make code more flexible, readable and configurable.

```shell
var start = function()
{
    var name = function(info)
    {
        var loc = function (location)
        {
           returns location;
        }  

       returns loc;
    }
    returns name;
}
var name = start();
var person = name("Snehal");
var country = person("India");

console.log(country);
var result = start();
console.log (result);


Output: Snehal
        India
```


---------------
## Pure function

It is a function when you pass value it will always return the same value. It does not change the input value.

```shell
Function addition (X,Y)
    {
        return X + Y;
    }
    Var first = 50;
    Var second = 10;
    Const result = add(first, second);
    Console.log(result, first, second);

Output: 60 50 10
```
-----------------
## Immediately Invoked Function Expression (IIFE)

IIFE is used to execute functions immediately. It is a self-executing function expression(SELF). We use a semicolon (;) before write function to save code. This function can call only once.

```shell
(function()
{
console.log(“Good Morning”);
}
) 
();
Output: Good Mornig

```
--------------------

## Closure

The closure is nothing but you can access the private variables in class or object. In JavaScript, you can able to access a private variable by the closure.

```shell
var start = function()
{
    let variable = "Hello";
    var stop = function()
    {
        console.log(variable)

    }
    return stop;
}
 var person = start()
 person();

 output: Hello
```
-----------------

## Arrow Function 

Arrow Function can not get hoisted. It is always a function assignment. It can not be function declaration.

```shell
Var name = ()  =>
{
Console.log(“Snehal”);
}
Name();

Output: Snehal 

```
-----------------------------


## Built in contractor / Prototype

In JavaScript function can be converted into a prototype.  In JavaScript constructor is a is used to initialize and create an object. this keyword refers to the object

```shell
Function info(name,location)
{
this.name = name;
this.location = location;
}
Var value1 = new info(“Snehal”,”India”);
Var value2 = new info(“Kavita”,”America”);
Console.log(value1);


Output: info{name: snehal , location: India }
```
-----------------------------
## Built in methods for Array,Object and String

* `push()`  It adds the items at the end of an array.

* `pop()`  It removes the item at the end of an array.

* `unshift()`  It adds an item at the beginning of an array.

* `shift()`  It removes the item from the beginning of an array.

* `concat()`  It is used to concat two an array into a single.

* `forEach()`  It is used for ,looping the function. It is the most heavily used method. It gives us the flexibility to reading the code .without writing for loop we can achieve code by this method.

* `map()` It is used for transforming the function. It is a very heavily used method.

* `filter()`  It is used to filter out the values.

* `indexOf()` It is used to find out an item in an array and returns its position.

* `includes()`  It is the same as indexOf but it returns true or false.

* `join()`  It is used to converting one data type to another datatype.

* `slice()`  It is used to slice the array. That is, it splits the array.

* `isArray()`  It is used to identify whether it is an array or object. It returns true or false.

* `keys()`  It is used to show all the present keys.

* `freeze()`  It creates the static data. Once you freeze the data it will not change.

* `toString()`  It is used to converts an object into a string.

* `toUpperCase()`  It is used to converts string into upper case.

* `toLowerCase()`  It is used to converts string into Lower case.

* `split(“ ”)`  It split the string by space.

* `replace()`  It is used to replace one string with another and It returns a new string.

* `trim()`  It removes space in string.

* `setTimeout( )`  It is used to delay code execution.

* `setInterval( )`  It is exactly works as a setTimeout but setInterval 
runs continuously.

* `parseInt()` It is used to convert string into number.



























