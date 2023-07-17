# React Context API

## Choosing the State Structure

1. Summarize the five principles for structuring state.

* Group related state
* Avoid contradictions in state
* Avoid redundant state
* Avoid duplication in state
* Avoid deeply nested state

## Passing State Deeply with Context

1. What problem do Contexts aim to solve?\
Having to pass down props every time you want to use them in a distant child element.
2. What is one technique to try before useContext?\
Try passing props down through the parent elements until you reach the child element that needs the props. Or, pass JSX elements as props like this example `<Layout><Posts posts={posts} /></Layout>`
3. What hook complements useContext for complex applications
useReducer is a good tool to pair with useContext.