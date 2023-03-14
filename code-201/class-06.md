# Problem Domain, Objects, and the DOM

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?<br>
An object is like a cabinet with a bunch of little drawers. You can put anything in these drawers. You can also really easily organize and find the items you have stored.
2. What are some advantages to creating object literals?<br>
It is easier to organize information this way. They can be used to store anything and be called later on. They can be used to even call different function within the object, which are called methods. 
3. How do objects differ from arrays?<br>
They both are a container for other variables, and they both can house each other. Some differences so are they way you access the data within them. In an array you use the index of the value you want, while in a an object you use the dot notation or the bracket notation. Objects can also be used to store functions in the form of methods, while arrays cannot.
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.<br>
If you need to access the property by a variable, lets say an input from a user, then you might need to access the property using the bracket notification because it uses a string.
5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?<br>
`const dog = {`<br> 
`name: 'Spot',`<br>
`age: 2,`<br>
`color: 'white with black spots',`<br>
`humanAge: function (){`<br>
`console.log('${this.name} is ${this.age*7} in human years');`<br>
`}`<br>
`}`<br>
`this` is a call to properties that are part of `this` object and can be used within other properties or methods.

## Introduction To The DOM

1. What is the DOM?<br>
DOM drives the dynamic expression of the HTML. This is a built in API allows us to dynamically change what is seen through a web browser.
2. Briefly describe the relationship between the DOM and JavaScript.<br>
DOM is the set of functions that are pert of JavaScript that allow for the control/printing of HTML elements using JavaScript.

