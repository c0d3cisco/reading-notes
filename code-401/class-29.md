# Advanced State with Reducers

1. What is the motivation for adding a reducer?\
The reduces the complexity of the code and makes it easier to read and understand as well as making it easier to test.
2. What are actions in the context of a reducer? How are they different than setting state directly?\
Actions are objects that have a type property and a payload property. The type property is a string that describes the action. The payload property is the data that is needed to perform the action. Actions are different than setting state directly because actions are objects that are passed to the reducer and the reducer uses the action to determine what state to return.
3. What common list operation is useReduce named for, and why?\
The common list operation that useReduce is named for is the reduce method because it reduces the array to a single value.
4. When should you switch from useState to useReducer?\
You should switch from useState to useReducer when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one.
