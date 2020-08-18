# Error Handling and Debugging

Bugs happen, noone is perfect.

When debugging your script it is important to keep the **order of execution in mind** This refers to the order in which the script is executed. 

The Javascript uses the concept of **execution context**. There is one global execution context plus each function creates a new execution context. They correspond to variable scope. 

Execution ontexts - 

Every script exists in one of three execution contexts:

- Global Context
- Function Context
- Eval Context

Global and function context correspond with with the idea of scope:

- Global Scope
- Function Level Scope

## The Stack 

JavaScript is processed on line at a time. When info is needed from a functionit stacks the new funtion on top of the current task. The new task goes on the top of the list. Once it is handeled, the interpreter goes back to the previous task. Each new task creates a new execution context. 

**Hoisting** 

Each Time a a script enters a new execution context it goes through two phases of activity:

- Prepare
- Execute

**Scope**

Each execution Context has its own **variables object**, which holds the variables, functions and parameters. It can also access its parent variables object. 

Functions in JavaScript have **lexical scope** meaning they are linked to the object in which they are defined. 

When a Javascript statement generates an error it throws an **exception** , you can set a set of statements to handle this. If the interpreter cannot find any handling code it will generate an error objecct. 

When this occurs it will give you the type of error that occured and where. It iis useful to use the console at this point. There are seven built in error objects in javascript. 

- error
- syntaxError
- referenceError
- typeError
- rangeError
- URiErro
- evalError

To handle an error you will need to debug it. Which is just tracking down the source of the error and fixing it. **USE THE DEVELOPER TOOLS**


## Debugging Workflow

Debugging is about finding and eliminating possible causes of an error. Narrow down where the problem might be and look for clues. 

A good strategy is to work slowly, breaking the code down and testing it bit by bit. **console.log** is good for this. Just rememember to take it out before going live. There are also three other methods 
- console.info
- console.warn
- console.error

There s also 
- console.group
- console. table
- console.assert

## Breakpoints

These can be used to pause the execution of a script to check the code. 
By setting multiple breakpoints you can browse through the code slowly to better examine it and determine where problems might pop up. Ypu can set a breakpoint to trigger if a certain conditin is met. 
You can create a breakpoint by just using the debugger keyword. 

## Try, catch, finally

first specify the code you are testing, if something happens it is moved to the catch block. if continue, break or return is used it will go directly to finally.

If try code throws an exception catch will use an alternative code. 

Code in the finally block  run whether or not the try block ran. Checks can be nested inside each other. 




