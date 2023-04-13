# React and Forms

## Why this topic matters

Forms matter because they are a corner stone to web's functionality as it collects and retrieves complex user inputs.
The ternary operator is important to understand as proper use of these is important; over use them and you might run into trouble, but use them at the right time and can greatly simply the code.

## React Docs - Forms

1. What is a ‘Controlled Component’?<br>
It is the method of combining the `setSate()` with the HTML form elements to one focal point so provide a "single source of truth"
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?<br>
We *should we update the state with their responses as soon as they enter them*. This is part of creating a 'single source of truth' which is what we want so we can control components as needed with each input, not when the form in submitted.
3. How do we target what the user is entering if we have an event handler on an input field?<br>
We pass the `event` parameter into the event handler function. With in that function, you can access `event.target`.

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?<br>
Ternary operators are good for picking over two things based on if a condition is truthy or falsy.
2. Rewrite the following statement using a ternary statement:<br>
`if(x===y){`<br>
`  console.log(true);`<br>
`} else {`<br>
`  console.log(false);`<br>
`}`<br><br>
`x === y ? console.log(true) : console.log(false);`

## Things I want to know more about

How does `.bind()` work and how `this` associates the function?
