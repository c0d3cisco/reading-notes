# HTML Lists, Control Flow with JS, and the CSS Box Model

## Reading questions and answers

### Learn HTML - **Ordered and Unordered lists**

1. When should you use an **unordered list** in your HTML document?<br>
You would use the unordered list when order is not important of your list or there is no numerical sequence to your list; meaning that one bullet does not take prescience over another.
2. How do you change the **bullet style** of unordered list items?<br>
You can change the bullet style with CSS, other wise, the bullet style will automatically be selected by the browswer(agent) based on the nesting level of the list.
3. When should you use an **ordered list** vs an **unordered list** in your HTML document?<br>
You would use the ordered list when order is important of your list or there is a numerical sequence to your list
4. Describe two ways you can change the numbers on **list items** provided by an **ordered list**?<br>
Like unordered lists, you can change the bullet style with CSS, other wise, the bullet style will automatically be selected by the browswer(agent) based on the nesting level of the list.<br>
You can also use attributes such as `start` start counting at a specific number, or `type` to change the numbering type.

### Learn CSS - **The Box Model**

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?<br>
Margin and the Padding were guards of the Box. They are divided by a wall called the Border. Margin is outside the wall guarding against other Boxes, and Padding is inside taking care of the precious Content. They change their attributes as needed to complete the mission.

2. List and describe the four parts of an HTML elements box as referred to by the box model.
    1. Margin - It is the outside layer of the element. Use `margin` to access related properties.
    2. Border - A box that contains the content and padding. Use `border` to change related properties.
    3. Padding - It is the space between the content and the boarder. Use `padding` to change related properties.
    4. Content - Area displayed of what you want to display. This has a number of properties that can be used to affect its display.

### Learn JS - Arrays - **Operators and Expressions. Conditionals. Loops**

1. What `data types` can you store inside of an `Array`?<br>
You can store any type of data type within an Array.
2. Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?<br>
`const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`<br>
Yes, an array of arrays this is a valid JavaScript array. You can access different values stored by saying `people[x][y]` where x and y are index numbers.
3. List five shorthand operators for assignment in javascript and describe what they do.<br>
`x += y`, `x -= y`, `x *= y`, `x /= y`, and `x ^= y`. These shorthand operators for assignments. For these examples, the operator will evaluate a new X as the old X being affected by the operator to the left of the `=` sign by Y. So in the first example, `x = x + y`, and so on. 

4. Read the code below and evaluate the last expression and explain what the result would be and why.<br>
    `let a = 10;`<br>
    `let b = 'dog';`<br>
    `let c = false;`<br>
    <br>
    `// evaluate this`<br>
    `(a + c) + b;`<br>
The final result would be **10dog** as JavaScript will convert `false` to zero, add it to 10, then convert 10 to a string and combine it with dog.
5. Describe a real world example of when a conditional statement should be used in a JavaScript program.<br>
An example of a real world example of a conditional statement would be useful is if an application needs to perform different actions depending on a variable of numerical values.

6. Give an example of when a Loop is useful in JavaScript.<br>
A while loop is an example of a loop. It will keep looping the code it has within it, until the condition associated with the while statement is false.

## Things I want to know more about
