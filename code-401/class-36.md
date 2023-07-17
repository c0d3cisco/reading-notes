# Application State with Redux

## Dan Abramov Redux Tutorials

1. What is the first principle of Redux?
Everything that changes in your application including the data and the UI state is contained in a single object called the state tree.
2. what is a store and what do we use our reducers for within that store?\
A store is an object that holds the application's Redux method. It holds its state and associated methods to change and render the state.
3. Name three Redux store methods given to us by createStore and describe their use.
>* `getState()` - returns the current state of the store
>* `dispatch()` - dispatches an action to the reducer
>* `subscribe()` - adds a change listener to the store
4. Explain to a non-technical recruiter what combineReducers() does and why it is useful.\
`combineReducers()` is a helper function that combines multiple reducers into one reducer. It is useful because it allows you to split your reducer logic into separate functions that handle different parts of the state tree.
