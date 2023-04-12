# Passing Functions as Props

## Why this topic matters

These topics are important because they are at the heart of data manipulation with React.

## React Docs - lists and keys

1. What does .map() return?<br>
The method `.map()` returns a new array with values that have been modified a certain way from an input array.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?<br>
We enclose the output variable you built up through maps in curly braces {}
3. Each list item needs a unique ____.<br>
A unique key identifier.
4. What is the purpose of a key?<br>
It is a way for React to keep track what has changed as they can always be reassorted with the original array.

## The Spread Operator

1. What is the spread operator?<br>
It is used to expand a literal object, usually an array, into its individual components.
2. List 4 things that the spread operator can do.<br>
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.[^1]
3. Give an example of using the spread operator to combine two arrays.<br>
`let arr1 = [1,2,3];`<br>
`let arr2 = [4,5,6];`<br>
`let arrComb = [...arr1, ...arr2];`<br>
4. Give an example of using the spread operator to add a new item to an array.<br>
`let arr1 = [1,2,3];`<br>
`let item1 = [4,5,6];`<br>
`let arrComb = [...arr1, item1];`<br>
5. Give an example of using the spread operator to combine two objects into one.<br>
`let obj1 = {count1: 3};`<br>
`let obj2 = {count2: 6};`<br>
`let arrComb = {...obj1, ...obj2};`<br>

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?<br>
Create an increment function.
2. In your own words, what does the increment function do?<br>
An increment function is sort of the middle ground between the dom elements in the render portion and allows the state of the component to be updated.
3. How can you pass a method from a parent component into a child component?<br>
Pass it just like any other props. In the example, they pass it as `this.increment`.
4. How does the child component invoke a method that was passed to it from a parent component?<br>
Then child invokes it as `this.props.increment`

## References

[^1]: [https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab]

## Things I want to know more about

Shallow vs Deep copying
