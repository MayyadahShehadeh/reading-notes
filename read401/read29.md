## Advanced State with Reducers

### 1. How can we ensure that an effect hook runs only once?
The trick is that useEffect takes a second parameter.
The second param is an array of variables that the component will check to make sure changed before re-rendering. You could put whatever bits of props and state you want in here to check against.
Or, put nothing.

### 2. Can useState() update more than one state variable at the same time?
You could combine the loading state and data state into one state object and then you could do one setState call and there will only be one render. Note: Unlike the setState in class components, the setState returned from useState doesn't merge objects with existing state, it replaces the object entirely.

### 3. Is useState() synchronous?
useState and setState both are asynchronous. They do not update the state immediately but have queues that are used to update the state object. This is done to improve the performance of the rendering of React components. Even though they are asynchronous, the useState and setState functions do not return promises.

-----------------------

### Terms:

**State Hook:**
The useState hook is a special function that takes the initial state as an argument and returns an array of two entries. Syntax: The first element is the initial state and the second one is a function that is used for updating the state.

**Component Lifecycle:**
Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM). This is referred to as a component lifecycle. There are different lifecycle methods that React provides at different phases of a component's life.

----------------------------

### useReducer:
An alternative to useState. Accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method. (If you’re familiar with Redux, you already know how this works.)

useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.