# React: `useState()` Hook

## [Thinking in React](https://react.dev/learn/thinking-in-react)

1. Summarize the five steps of thinking in react.

* Step 1: Break the UI into a component hierarchy\
Use the whiteboard process to break the UI into a component hierarchy. This is crucial to building a well-architected app.
* Step 2: Build a static version in React\
Use React components to build a website that does pretty much nothing. It just looks like the website you want to build.
* Step 3: Identify the minimal but complete representation of UI state\
Go through each component and identity which components are stateless, which will get props, or which will have states.
* Step 4: Identify where your state should live\
Identify which component should own what state. Remember, React is all about one-way data flow down the component hierarchy. It may not be immediately clear which component should own what state. This is often the most challenging part for newcomers to understand, so follow these steps to figure it out:
	* For each piece of state in your application:
		* Identify every component that renders something based on that state.
		* Find a common owner component (a single component above all the components that need the state in the hierarchy).
		* Either the common owner or another component higher up in the hierarchy should own the state.
		* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
* Step 5: Add inverse data flow
By passing in callbacks and props to children, you can add inverse data flow to your application. This will allow you to change the state of the parent component from the child component.

## [State: A Component’s Memory](https://react.dev/learn/state-a-components-memory)

1. What is one reason a local variable isn’t sufficient for managing a React component?\
Because the component will not re-render when the variable is updated.
2. What is the argument to the useState hook, and what are the two parts of its return array?\
You have the state variable and the function to update the state variable. The state variable can have any name, but the function to update the state variable should be named `set` followed by the state variable name.
3. How can Component A access state from Component B?\
It all depends on the relation to each other, but assuming A is a parent and B is a child, you can pass the state variable and the function to update the state variable as props to the child component. If they are siblings, you can pass the state variable and the function to update the state variable to the parent component and then pass them as props to the child component.
