# Express, NPM, TDD, CI/CD

## An introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.<br>
Middleware is code in on the server side that processes the data before reaching an endpoint. With the additional code, a developer can use this to authenticate the user, process incoming request just to name a couple. This allows the developer to make the server more flexible for handling and processing requests.
2. Express the most popular **Node web framework**.
3. Express is “unopinionated.” What does that mean?<br>
It means there are less "restrictions" on how to use Express. Opinionated vs Unopinionated referees how many rules there are to operate a particular code. For example, JavaScript is considered opinionated while Reach is considered opinionated.
4. What is a module and why is modularity useful to us as developers?<br>
Modules for Express are like components for React. They can be used to organize the code so it is more maintainable and scalable. Modules also allow a developer to increase their code's readability.

## What is NPM?

1. What version of npm are you running on your machine?<br>
9.6.6
2. What command would you type to install a library/package called ‘jshint’ into your node project?<br>
I would run `npm install -g jshint` to install jshint. The `-g` is used to install this at a global level.

## What is TDD?

1. Explain why tests are important. Please explain as though I were your non technical elder.<br>
When writing computer code, there are so many places wires can crossed and issues can arise. Because code can become so length, it is important to test as you are writing code to ensure you don't go to far down the wrong rabbit hole. Doing small tests along the way ensure you can back track to a point where things were working and focus on that on thing that didn't, rather than focusing on fixing multiple things at the same time.

2. What are three expected benefits of testing<br>
Reductions in defect rates as more resilient code is written through out the development process.<br>
The final phases of the project become less burdensome.<br>
Improved design qualities.
3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.<br>
Individual

> Forgetting to run tests frequently<br>
> Writing too many tests at once

Team

> Poor maintenance of the test suite<br>
> Abandoned test suite

## CI/CD

[What is continuous integration?](https://www.atlassian.com/continuous-delivery/continuous-integration)

1. What are three benefits of Continuous Integration?<br>
There are other benefits, but three big ones are that CI enables scaling as it increases organization of the team, it allows the team to keep up with technology learning curves, and it improve the feedback loop between management and developers to ensure.
2. What is the difference between Continuos Delivery and Continuous Deployment?<br>
Continuous delivery is the next phase of continuous integration and it is used to ensure that the product is at a state where it is continuously ready for the end-user. Continuous deployment on the other hand is the continuous release of the product as new versions are released.
3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background<br>
Continuos integration requires a lot of collaboration between team members that are working on code in different computers. GitHub provides developers a place to store their changes continuously in an easy to use interface where code can be reviewed and then merged if approved. The organization GitHub provides helps teams work towards a working product.  
