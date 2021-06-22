## React Docs - lists and keys
1. What does .map() return?
we use the map() function to take an array of numbers and double their values. We assign the new array returned by map() to the variable doubled and log it.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
you can put any valid JavaScript expression inside the curly braces in JSX. For example, 2 + 2, user.firstName, or formatName(user) are all valid JavaScript expressions.

3. Each list item needs a unique **key**.

4. What is the purpose of a key?
Keys help React identify which items have changed, are added, or are removed.

-------------------------------
## The Spread Operator

1. What is the spread operator?
In JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.


2. List 4 things that the spread operator can do.
The … spread operator is useful for many different routine tasks in JavaScript, including the following:

- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list
- Adding to state in React

3. Give an example of using the spread operator to combine two arrays.
const myArray = [🤪,🐻,🎌] const yourArray = [🙂,🤗,🤩] const ourArray = [...myArray,...yourArray] console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

-----------------------------

## How to Pass Functions Between Components
1. In the video, what is the first step that the developer does to pass functions between components?

create the function wherever the state is that we’re going to change.

2. In your own words, what does the increment function do? effect a change in one component state from within another component.

3. How can you pass a method from a parent component into a child component?
Just like any other props by add it to the object, then write it in the child class.