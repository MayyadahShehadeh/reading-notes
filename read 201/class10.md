# JS Debugging
## - ORDER OF EXECUTION
To find the source of an error, it helps to know how scripts are processed. he order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

## - EXECUT.ION CONTEXTS
The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

## - UNDERSTANDING SCOPE
In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object.

## - UNDERSTANDING ERRORS
If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.

## - BREAKPOINTS
You can pause the execution of a script on any line using breakpoints. Then you can check the va lues stored in variables at that point in time.
-----------------
&copy; **Source:** 

[javascript and jquery interactiv Book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F01TTSXQT5M/javascript_and_jquery_interactive_jon_du.pdf?c=1618418988-21b29523d81fd117)