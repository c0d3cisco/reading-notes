# Debugging

## What Went Wrong? Troubleshooting JavaScript

1. Name some key differences between a **Syntax Error** and a **Logic Error**.<br>
The main difference between Syntax Error and a Logic Error is source of the error. For the syntax error, the problem will be with the spelling of the code, meaning that this occurs when you type something wrong. An example would be having `if(i = 1){}` as the comparison for the if statement. A logic error is rooted in how the code is running. Resolving this is the harder part as this is the actual issue engineer's run into that makes this line of work challenging. Without Logic Errors, software engineers wouldn't have the reputation they do.
2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.<br>
One error that I keep running into a lot is passing null or undefined value into a function or expression. These are sometimes tricky to find but console logs really have been my friend for this one. I'll start putting a console log above the line where the error occurred so I can see the value of the variable that is null/undefined. Then from there I trace it back until I find where the error is occurring by adding more console logs.
3. How will this topic continue to influence your long term goals?<br>
Knowing the error types in important when loading debugging, which is a pillar of coding. It is inevitable that I will run into thousands of bugs in my career, its just part of the coding process. The best I can do is learn more of what the errors mean so I can use them to find the root of my problems faster and more effectively solve them.

## The JavaScript Debugger

1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?<br>
I would start explaining that code is read by a computer extremely fast. This makes it hard to see what the code is actually doing. If an error is occurring and you just need to pause the processing of the script execution, you can add debugging points which will stop the code and allow you to see the internals of what is being processing at the time the code paused.
2. Define what a breakpoint is.<br>
A debugger breakpoint is a point or points in the code selected by the developer to pause the processing of the code. This allows developers to examine the values that are currently stored in the memory. This is particularly useful when trying to see the inner working of functions/methods that have their own internal variables.
3. What is the Call stack?<br>
The Call stack is a section of the console that allows you to see the line of code that was executed to reach the current line of code. This can be particularly useful when seeing how certain script files are talking to each other as the code of an application gets more and more complex.

## Things I want to know more about
