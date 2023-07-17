# Context API - Behaviors

## Scaling Up with Reducer and Context

1. How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose)\
	A reducer is extremely helpful when trying to keep event handlers concise. React's useReducer has a state and dispatch function that can be extracted and use to manage complex states for an application. The useContext hook is great solution for passing data to distant descendants as parent elements are wrapped in the context, and anything is passed through these context wrap elements can be accessed by any child element.\
	By using the useContext hook as a place for the useReducer to house its state and dispatch, any wrapped element and all of its children can access the state and dispatch. This is great for scaling as we can avoid prop drilling and keep our code clean and concise. 