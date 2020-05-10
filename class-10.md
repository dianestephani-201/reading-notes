# Class 10
## JavaScript
### Chapter 10: Error Handling & Debugging
- Order of execution: Knowing how scripts are processed helps when searching for the source of an error.
- Every statement in a script can live in 1 of 3 execution statements: Global context, function context, and eval context. **Global context** is cod that is in the script but not in a function. One global context in any given page. **Function context** is code that is being run within a function. Each function has its own function context. **Eval context** is text that is executed like code in an internal function called eval().
- JavaScript processes one line of code at a time. When a statement needs data from another function, it stacks the new function on top of the current task.  
- Each time a script enters a new execution context, there are 2 phases of activity: prepare and execute. Variables, functions, and arguments are created to prepare. To execute, values can be assigned to variables, functions can be run, and statements can be executed. 
- JavaScript functions have **lexical scope**, which means that they're linked to the object they're defined within.
- If a statement in JavaScript generates an error, it then throws an **exception**. The interpreter will stop and look for exception-handling code.
- **Error objects** can help find where mistakes are. Browsers have tools to help read error objects.
- **Syntax error:** syntax is not correct, mismatching or unclosed quotes, missing closing bracket, missing comma in array, malformed property name.
- **Reference error:** Variable doesn't exist, variable is undeclared, named function is undefined. 
- **Eval error:** Incorrect use of eval() function. 
- **URIError:** Incorrect use of URI functions, characters are not escaped.
- **Type error:** Value is unexpected data type, incorrect case for document object, incorrect case for write() method, method does not exist, DOM node does not exist.
- **Range error:** Number outside of range, cannot create array with -1 items, number of digits after decimal in toFixed() can only be 0-20, number of digits in toPrecision() can only be 1-21.
- **NaN:** Not an error, but means "not a number."
- Debugging is about eliminating potential causes of an error. Narrow down the area where the problem seems to be, then try to locate the actual line where the error is. 