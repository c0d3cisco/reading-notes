# Forms and JS Events

## HTML Forms -Your first Web Form. How To Structure A Web Form

1. Why are forms so important in web development?<br>
Forms are important in web development as a main way users communicate with the website. This can range from entering usernames, passwords, marks checkbox, press buttons. It allows for capturing information a user may submit.
2. When designing a form, what are some key things to keep in mind when it comes to user experience? <br>
The bigger the form the more confusing it can become, thus the more frustrated the user may grow. The reading recommends to keep simple and only ask what is required.
3. List 5 form elements and explain their importance.<br>
`form` - This is a container element. This is the element that defines the area where additional form related elements will be placed.
`label` - The label field give a title to the input. This can be used to associate the title with the input to increase the accessibility of your website.
`input` - This element is used to record certain types of inputs. This element has the type attribute that allows modification of the type of display for a use to see for entering information (i.e a simple text box, a numerical selection, email verifying text box, a button)
`button` - This element can be used by the user for three main purposes: submit, reset, and button. The submit sends form input data, reset returns all form widgets to their default values, and button can be customized to do practically anything with JavaScript.
`textarea` - this element is used to take text input. A difference between the textarea element and the input element is that the input element is a void element, meaning it does not have a closing tag, while the textarea does have a closing tag. This will impact the way you code the default value of these elements.

## Learn JS - Introduction To Events

1. How would you describe events to a non-technical friend?<br>
An event is an action that can be registered by the browser. Whether it be the click down, the click up, the hover of your mouse, the entering of a key; virtually any action that can be captured is an event.
2. When using the `addEventListener()` method, what 2 arguments will you need to provide?<br>
The two arguments needed for an `addEventListener()` are a string which references the type of event and the other is the function which you want to execute upon the event.
3. Describe the event object. Why is the target within the event object useful?<br>
Event object is a parameter for a function used in the `addEventListener()` which provides additional functions and information. In the example of the reading, the event object is used to target background color of the website - using JavaScript to affect CSS and HTML elements.
4. What is the difference between event bubbling and event capturing?<br>
When you click on a button (or do any event action) in the browser, it is likely you are usually clicking in a nested element. When events are triggered, the actions propagate either from top element in or inner most element out. Event bubbling describes when an action is captured inner most element and it 'fires' the actions out. Event capturing, is the opposite. The event is captured from the outer most element in to the inner most nested element that was selected.

## Things I want to know more about