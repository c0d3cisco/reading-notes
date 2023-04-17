# Putting it all together

## Why this topic matters

This topic is important as the structure to your application is critical. You need to keep the structure readable which is a combination of simplicity, but also, some added complexity with high-level functions to increase the understanding of the code for a developer.

## React Docs - Thinking in React

1. What is the `single responsibility principle` and how does it apply to components?<br>
The concept applied for components, functions, and objects which emphasis each should do/represent one thing.
2. What does it mean to build a ‘static’ version of your application?<br>
It means to build a version that is visually finish, but still needs its functionality added.
3. Once you have a static application, what do you need to add?<br>
Add functionality
4. What are the three questions you can ask to determine if something is state?<br>
Identify which components will use a state, find the closest parent component, and identify where the state should live.
5. How can you identify where state needs to live?<br>
It depends on what the state is and how it interacts with components. Usually it is best to put it in the common parent, but it could also go above the common parent if it makes more sense. If neither option works for some reason, you can always create a component specificity to hold the state.

## Higher-Order Functions

1. What is a “higher-order function”?<br>
A high-order functions are functions that work on other functions. This can be done by returning a function from a function or taking one in as an argument.
2. Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?<br>
Line 2 is returning a function that uses m as a variable and n as content.
3. Explain how either `map` or `reduce` operates, with regards to higher-order functions.<br>
They both work as a function which takes in an array and a function as a parameter. `map` will use the input function to iterate and transform every element of the input array.

## Things I want to know more about
