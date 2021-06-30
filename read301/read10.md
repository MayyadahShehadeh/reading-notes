## JavaScript Call StackWhat is a ‘call’?

### 1. What is a ‘call’?
- a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
### 2. How many ‘calls’ can happen at once?
- JavaScript is single-threaded so it can only do one call at once

### 3. What does LIFO mean?
- When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
### 4. What causes a Stack Overflow?
- This occurs when there is a recursive function, a function that repeats itself without an exit point Notes on error messages

------------------------------------

## JavaScript error messages

### 1. What is a ‘refrence error’?
- This is what you get when you use a variable that hasn't been declared yet

### 2. What is a ‘syntax error’?
- This happens when you try to parse an invalid object using json.parse for example, but means you should use a different syntax

### 3. What is a ‘range error’?
- When you try to give an object some invalid length

### 4. What is a ‘tyep error’?
- That happens when the data type you are trying to access is incompatable with the functionality you are trying to use it for

### 5. What is a breakpoint?
- This allows easier debugging for the line you add it on, it will make your program stop running when it hits that point and you can 'fiddle' with it in the developer console.

### 6. What does the word ‘debugger’ do in your code?
- You need this keyword for adding a breakpoint
