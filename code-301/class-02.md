# State and Props

## Why this topic matters

States and proprs are how components in react manipulate and exchange data. The intraconnectivity of these components is crucial to making an application function, therefor this topic is really important.

## React lifecycle

1. Based off the diagram, what happens first, the `render` or the `componentDidMount`?<br>
`render` happens first.
2. What is the very first thing to happen in the lifecycle of React?<br>
constructor occurs first, and it occurs during the mounting phase.
3. Put the following things in the order that they happen: <br>
`constructor`, `render`, `React Updates`, `componentDidMount`, `componentWillUnmount`<br>
4. What does `componentDidMount` do?<br>
It is invoked after a component is mounted and it used to load things using a network request or to initialize the DOM<br>

## React State Vs Props

1. What types of things can you pass in the props?<br>
You pass any information you need to child component. If I understood the video, the state of a component can be passed into a component as props.
2. What is the big difference between props and state?<br>
Props are passed into a component and handled outside of the component, while states are handles within a component. Thus props must be updated outside the component, and states and be updated within the component.  
3. When do we re-render our application?<br>
An application will re-render when the state is updated based on something the user has done.
4. What are some examples of things that we could store in state?<br>
Any information that is being manipulated by the user such as a counter or a form.

## Things I want to know more about
