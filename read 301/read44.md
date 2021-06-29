## Forms
 1. **What is a "Controlled Component"?**
An input form element whose value is controlled by React in this way is called a “controlled component”.In HTML, form elements such as , ,xtarea an typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

2. **Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

because you need to write an event handler for every way your data can change and It is used controlled component.

3. **How do we target what the user is entering if we have an event handler on an input field?**

By naming attribute to each element and let the handler function choose what to do based on the value of event.target.name.

## The Conditional (Ternary) Operator Explained
1. **Why would we use a ternary operator?**
beacuse it's shortened way of writing an if-else statement, by writing one line of code with three arguments, the condition, the result upon the true comparison, and the result upon the false comparison.

2. **Rewrite the following statement using a ternary statement:**
if(x===y){ console.log(true); } else { console.log(false); }

ANSWER:

x===y ? console.log(true) : console.log(false)