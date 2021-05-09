# Functions #
** JavaScript provides functions similar to most of the scripting and programming languages.

In JavaScript, a function allows you to define a block of code, give it a name and then execute it as many times as you want.

A JavaScript function can be defined using function keyword. **
# Function Parameters #

**A function can have one or more parameters, which will be supplied by the calling code and can be used inside a function. JavaScript is a dynamic type scripting language, so a function parameter can have value of any data type.**

# The Arguments Object #

**All the functions in JavaScript can use arguments object by default. An arguments object includes value of each parameter.

The arguments object is an array like object. You can access its values using index similar to array. However, it does not support array methods.**

# Function Expression #
**JavaScript allows us to assign a function to a variable and then use that variable as a function. It is called function expression.**

# Nested Functions #

In JavaScript, a function can have one or more inner functions. These nested functions are in the scope of outer function. Inner function can access variables and parameters of outer function. However, outer function cannot access variables defined inside inner functions.

  # Points to Remember :# 

- [x] JavaScript a function allows you to define a block of code, give it a name and then execute it as many times as you want.
- [x] A function can be defined using function keyword and can be executed using () operator.
- [x] A function can include one or more parameters. It is optional to specify function parameter values while executing it.
- [x] JavaScript is a loosely-typed language. A function parameter can hold value of any data type.
You can specify less or more arguments while calling function.
- [x] All the functions can access arguments object by default instead of parameter names.
- [x] A function can return a literal value or another function.
- [x] A function can be assigned to a variable with different name.
- [x] JavaScript allows you to create anonymous functions that must be assigned to a variable.



 # Function Declarations vs. Function Expressions #
 **What is Function Statement/Declarations in JavaScript?**

The function statement declares a function.
A declared function is “saved for later use”, and will be executed later, when it is invoked (called).
Just as Variable Declarations must start with “var”, Function Declarations must begin with “function”.

>e.g.
function bar() {
return 3;
}

function is only declared here .For using it, it must be invoked using function name. e.g bar();

 # What is a Function Expression? #
A JavaScript function can also be defined using an **expression**.

A function expression can be stored in a variable:

>var x = function (a, b) {return a * b};

After a function expression has been stored in a variable, the variable can be used as a function. Functions stored in variables do not need function names. They are always invoked (called) using the variable name.

 # Benefits of Function Expressions #
There are several different ways that function expressions become more useful than function declarations.
As closures
As arguments to other functions
As Immediately Invoked Function Expressions (IIFE)
