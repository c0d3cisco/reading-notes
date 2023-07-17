# Redux - Additional Topics

## [Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

1. What concerns are addressed by Redux Toolkit?\
The main concerns of Redux that are addressed by Redux Toolkit are the completed configuration of the store, adding several packages to get meaning out of redux, and it requires too much boilerplate code.
2. What does `configureStore()` do?\
It is a wrapper for the createStore() function that adds defaults to the store that make it easier to develop.
3. How would I use createSlice()?\
It is a way to simplify the creation of reducers and actions. Its takes the name of the slicer, the initial state, and an object of reducer functions.

## [MobX](https://mobx.js.org/getting-started.html)

1. What is Mobx?\
MobX is a state management that is simple and scalable that allows React components to be reactive as the state changes.
2. How does MobX make it “impossible” to produce an inconsistent state?\
It does this by ensuring that what is being displayed and the current state are always in sync.
3. How would we build a reactive user interface?\
By using the `observer` function to wrap the component that needs to be reactive. This will make the component reactive to any changes in the state.
