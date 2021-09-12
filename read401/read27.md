## useState() Hook


### How does React differ from vanilla JS/HTML/CSS?
 data amongst each other. This breaking down of the UI is what gives React an edge over Vanilla JS. ... This is where React comes in with a great feature i.e its own virtual DOM. The virtual DOM is a shortcut to bypass the manual work.

### What is the primary difference between a function component and a class component?
A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React. Component and create a render function which returns a React element. There is no render method used in functional components.

-------------------------

### Terms: 
**Functional Components:**
Functional components are basic JavaScript functions. These are typically arrow functions but can also be created with the regular function keyword. Sometimes referred to as “dumb” or “stateless” components as they simply accept data and display them in some form; that is they are mainly responsible for rendering UI

**Children / Child Components:**
If a component, when used, contains child components or React nodes inside of the component (e.g., <***Parent***><***Child /***><***/Parent***> or <***Parent***><***span***>test<***span***><***/Parent***>) these React node or component instances can be accessed by using this.props.children.

In the code below the Parent component when used, contains two <***div***> React node children, which contains React text nodes. All of the children instances, inside of the component are accessible using this.props.children. In the code below I access these children inside of the Parent componentDidMount lifecycle function.