## Redux - Combined Reducers

### Why choose Redux instead of the Context API for global state?
Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity


### What is the purpose of a reducer?
A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. 

### What does an action contain?
An action is an object that contains two keys and their values. The state update that happens in the reducer is always dependent on the value of action

### Why do we need to copy the state in a reducer?
If the new state is different, the reducer must create new object, and making a copy is a way to describe the unchanged part

----------------------

### Terms: 

**immutable state:**
In object-oriented and functional programming, an immutable object (unchangeable object) is an object whose state cannot be modified after it is created.

**time travel in redux:**
Time travel is the ability to move back and forth among the previous states of an application and view the results in real time. With Redux, given a specific state and a specific action, the next state of the application is always exactly the same

**action creator:**
An action creator is merely a function that returns an action objec.

------------------------

### Using combineReducers
Because this pattern is so common, Redux provides the combineReducers utility to implement that behavior. It is an example of a higher-order reducer, which takes an object full of slice reducer functions, and returns a new reducer function.

### combineReducers(reducers)
As your app grows more complex, you'll want to split your reducing function into separate functions, each managing independent parts of the state.

The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.

