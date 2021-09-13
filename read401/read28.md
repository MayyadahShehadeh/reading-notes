## useEffect() Hook

### * If we wanted a component to show up on every page, where would we put it and why?

- Inside a <Route />

### * What does routing do with the components that were rendered when a new route is requested
Routing is the ability to move between different parts of an application when a user enters a URL or clicks an element (link, button, icon, image etc) within the application.

### * What does props.children contain?
what this.props.children does is that it is used to display whatever you include between the opening and closing tags when invoking a component.


### * How do useState() and this.setState() differ?
- setState() Class Component
Since state in a class component is already an object, it's business as usual. Use setState to populate the values of the state object.


- useState() Functional Component
When we want to use the useState hook for an object we are going to initialize it to an empty object useState({}).

--------------------------
### useEffect() Hook:

**What does useEffect do?**
By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates. In this effect, we set the document title, but we could also perform data fetching or call some other imperative API.

**Why is useEffect called inside a component?** 
Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don’t need a special API to read it — it’s already in the function scope. Hooks embrace JavaScript closures and avoid introducing React-specific APIs where JavaScript already provides a solution.

**Does useEffect run after every render?**
 Yes! By default, it runs both after the first render and after every update. (We will later talk about how to customize this.) Instead of thinking in terms of “mounting” and “updating”, you might find it easier to think that effects happen “after render”. React guarantees the DOM has been updated by the time it runs the effects.

