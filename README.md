<!-- # dataquestion -->
Q.1 what is data type in js
Ans.-In JavaScript, a data type is an attribute associated with a value that determines the type of operations that can be performed on it. JavaScript has several built-in data types, which can be categorized into two main categories: primitive data types and reference data types.

Primitive Data Types:

String: Represents a sequence of characters, enclosed within single quotes (''), double quotes ("") or backticks (``).
Number: Represents numeric values, including integers and floating-point numbers. JavaScript does not differentiate between integer and floating-point numbers.
Boolean: Represents a logical value of either true or false.
Undefined: Represents a variable that has been declared but not assigned any value yet.
Null: Represents an intentional absence of any value.
Symbol: Represents a unique identifier, introduced in ECMAScript 6 (ES6).
Reference Data Types:

Object: Represents a collection of key-value pairs. Objects can be arrays, functions, regular expressions, and other objects.
Array: Represents a list-like collection of elements, where each element can be of any data type.
Function: Represents a block of reusable code that can be invoked by its name.
Date: Represents a date and time.
RegExp: Represents a regular expression object for matching text patterns.
Map: Represents a collection of key-value pairs with unique keys.
Set: Represents a collection of unique values.
JavaScript is a dynamically typed language, which means you don't need to specify the data type of a variable explicitly. The data type of a variable is determined dynamically at runtime based on the type of the value assigned to it. This allows for flexibility but can also lead to unexpected behavior if not managed properly.




Q.2 what is js
ans.:- JavaScript (JS) is a high-level, interpreted programming language primarily used for creating interactive web pages and web applications. Developed by Brendan Eich in 1995, JavaScript has since become one of the most widely used programming languages on the web.



Q.3 what is arry
ans.:- It seems like you're asking about an "arry," which might be a typo. Assuming you're referring to an "array," an array is a data structure in programming used to store a collection of elements. In JavaScript, an array is a special type of object that holds a list of items indexed by integer numbers. These items can be of any data type, including numbers, strings, objects, or even other arrays.


Q.4  what is object
ans.:-In JavaScript, an object is a complex data type that allows you to store collections of key-value pairs. It's one of the most important data structures in the language and is used to represent real-world entities and their properties. Objects in JavaScript are instances of the Object class and can be created using object literals {} or the new Object() constructor.


Q.5  compare in primitive and non primitive
ans.:- Primitive Types:

String: Represents a sequence of characters, enclosed within single quotes (''), double quotes ("") or backticks (``).
Number: Represents numeric values, including integers and floating-point numbers.
Boolean: Represents a logical value of either true or false.
Undefined: Represents a variable that has been declared but not assigned any value yet.
Null: Represents an intentional absence of any value.
Symbol: Represents a unique identifier, introduced in ECMAScript 6 (ES6).
Primitive types are immutable, meaning their values cannot be changed. When you manipulate a primitive value, you're actually creating a new value rather than modifying the original one.

Non-Primitive Types (Reference Types):

Object: Represents a collection of key-value pairs. Objects can be arrays, functions, regular expressions, and other objects.
Array: Represents a list-like collection of elements, where each element can be of any data type.
Function: Represents a block of reusable code that can be invoked by its name.
Date: Represents a date and time.
RegExp: Represents a regular expression object for matching text patterns.
Map: Represents a collection of key-value pairs with unique keys.
Set: Represents a collection of unique values.
Non-primitive types are mutable, meaning their values can be changed after creation. When you assign a non-primitive value to a variable or pass it as an argument to a function, you're actually working with a reference to the original value stored in memory. Modifications made to this reference affect the original value directly.

Understanding the distinction between primitive and non-primitive types is important in JavaScript because it affects how values are stored, compared, and manipulated in your code.




Q.6  write all there js key words which are use for variable declaration in js
ans.:- var: var is the original keyword used for variable declaration in JavaScript. It has function scope, meaning variables declared with var are scoped to the nearest function block. However, if var is declared outside of any function, it becomes a global variable. Usage of var has been largely replaced by let and const due to their better scoping behavior.

let: Introduced in ECMAScript 6 (ES6), let allows you to declare variables with block scope. Variables declared with let are limited to the block (enclosed by curly braces {}) in which they are declared, including loops, if statements, and functions.

const: Also introduced in ECMAScript 6 (ES6), const is used to declare constants. The value of a constant cannot be reassigned once it's initialized. However, for objects and arrays declared with const, their properties or elements can be modified, but the variable itself cannot be reassigned.
