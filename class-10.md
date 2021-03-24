# Debugging and Error Handling

JavaScript can be **hard** to learn and everyone makes
mistakes when writing it.

## ORDER OF EXECUTION
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run.
 (it runs **sequentially**).

### EXECUTION CONTEXT

Every statement in a script lives in one of three
execution contexts:

1. GLOBAL CONTEXT
Code that is in the script, but not in a function.
There is only one global context in any page.
2. FUNCTION CONTEXT
Code that is being run within a function.
Each function has its own function context.
3. EVAL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function
called eval {) .

### VARIABLE SCOPE

The first two execution contexts correspond with the
notion of scope:

1. GLOBAL SCOPE
If a variable is declared outside a function, it can
be used anywhere because it has global scope.
If you do not use the var keyword when creating
a variable, it is placed in global scope.
2. FUNCTION-LEVEL SCOPE
When a variable is declared within a function,
it can only be used within that function. This is
because it has function-level scope.

In the interpreter, each execution context has its own variables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's variables object.


### UNDERSTANDING ERRORS

If a JavaScript statement generates an *error*, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.

If you are *anticipating* that something in your code
may cause an error, you can use a set of statements
to handle the error.
This is important because if the error is not handled,
the script will just stop processing and the user will
not know why. So **exception-handling** code should
inform users when there is a problem.

**ERROR OBJECTS**

Error objects can help you find where your mistakes are
and browsers have tools to help you read them.

![errors](https://slideplayer.com/13236669/79/images/slide_1.jpg)

