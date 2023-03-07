# Class 02 - Basics of HTML, CSS & JS

## Reading questions and answers

### Introduction to HTML

1. Why is it important to use semantic elements in our HTML?<br \>
Semantic elements have tags that are descriptive of what their purpose is within the HTML document. It is important to use correct semantic element to achieve desired purposes of your page to make the document readable and accessible.
2. How many levels of headings are there in HTML?<br \>
There are 6 levels of headings. You should refrain from using more than three if possible as content that is too nested could be confusing to read.
3. What are some uses for the `<sup>` and `<sub>` elements?<br \>
The `<sup>` element is a superscript element and it can be used to generate, for example, the little numbers of an exponential expression or write the 'th' of a date.<br \>
The `<sub>` element is a subscript element and it can be used to generate, for example, the little numbers of in a chemical equation.

4. When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?<br \>
`title` is the attribute to accompany `<abbr>` when a full expansion of the term is desired.

### Learn CSS

1. What are ways we can apply CSS to our HTML?<br \>
    * Externally stylesheet - this form of CSS code is stored in its own file and linked to your HTML document through a `<link>` element that is usually nested in the `<head>` element.
    * Internal stylesheet - the `<style>` element, also nested in the `<head>` element, can be used to directly have CSS code within the HTML document at a level that can be applied to the entire document.
    * Inline style - the reading labeled this form of CSS as the opposite of a best practice. This is CSS used in the specific line of the target element. It is added like an attribute of an element.

2. Why should we avoid using inline styles?<br \>
Using inline styling makes it very challenging read your code or modify your code at a later time. Inline styles will increase the size of your HTML document as this type of style has to be applied specifically to the element you want to target. For this reason, if you with to change the style of part of your website later, you will spend wasted time making changes to each individual, styled element.

3. Review the block of code below and answer the following questions:
    `h2 {`
     `color: black;`
     `padding: 5px;`
   `}`
    1. What is representing the selector?<br \>
        `h2`
    2. Which components are the CSS declarations?<br \>
        `color: black;`
        `padding: 5px;`
    3. Which components are considered properties?<br \>
        `color` and `padding`

### Learn JS

1. What data type is a sequence of text enclosed in single quote marks?<br \>
2. List 4 types of JavaScript operators.<br \>
3. Describe a real world Problem you could solve with a Function.<br \>

### Making Decisions In Your Code – Conditionals

1. An if statement checks a __ and if it evaluates to ___, then the code block will execute.<br \>
2. What is the use of an `else if`?<br \>
3. List 3 different types of comparison operators.<br \>
4. What is the difference between the logical operator `&&` and `||`?<br \>

## Things I want to know more about
