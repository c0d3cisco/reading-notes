# Object-Oriented Programming, HTML Tables

## Domain Modeling

1. Explain why we need domain modeling.<br>
Domain modeling is needed to encapsulate a conceptual problem into a tighter structure. From what I understand so far, domain modeling is governed by object-Oriented programming which can have a wide range of capabilities, such as storing any variable type as well as even storing functions.

## HTML Table Basics

1. Why should tables not be used for page layouts?<br>
Because the tables reduce accessibility to your website, it over complicates the code, and they are not automatically responsive to the size of the browser window.
2. List and describe 3 different semantic HTML elements used in an HTML `<table>`.
I would say all of the elements of a table are semantic. `<table>`  is self-explanatory and it is used to start a table element. `<thead>`,`<tbody>`, and `<tfoot>` are the elements of a for the specific sections of the row self described in their name. `<tr>`,`<td>`, and `<th>` stand for table row, table detail, and table head, respectively. The table row will house the table details and table head.

## Introducing Constructors

1. What is a constructor and what are some advantages to using it?<br>
Constructors are functions that can be used to initiate objects, otherwise, objects would have to be written individually if you had a large number of data that written in object format. A constructor can be used to large data sets, formate per the parameters set in the constructor, and generate objects from the data set. With a simple loop, you can run this data and get a lot of the objects created from the one constructor function.
2. How does the term `this` differ when used in an object literal versus when used in a constructor?<br>
`this` is used in the constructor to assign values to the properties of the object. `this` is used in an object literal to call on a property of the object.

## Object Prototypes Using A Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.<br>

> * NOTE: This is a very common front end developer interview question<br>

I work with a software that helps surgeons plan shoulder replacement surgery. Here they can load a patient's data into one surgical case file where they make the modifications needed. So the patient's specific case would be the object and the parameters that make the surgery unique are the properties. Depending if the surgery will be a reverse total vs a total shoulder, the surgeons can load pre determined preferences associated with their selection, this would be inheritance of the case files.

## Things I want to know more about
