# React lifecycle

- Depending on the diagram, what happens first, 'display' or 'componentDidMount'?
componentDidMount
- What is the first thing that happens in the React lifecycle?
Mounting
- Put the following things in the order in which they occur: componentDidMount , render , constructor componentWillUnmount , React Updates:
1. constructor 
2. render
3. React Updates
4. componentDidMount 5.componentWillUnmount

- What does componentDidMount do?
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount()
-----------------------------------------------------------

## React State Vs Props
- What types of things can you pass in the props?

We pass props as an argument it can be strings or numbers.

- What is the big difference between props and state?

The big difference is that we can pass props into a component it is handled out side the component but state is handled inside that comopnent.

- When do we re-render our application?

When we change the state inside it.

- What are some examples of things that we could store in state?

input element and checkbox