# Class 01 Fundimentals of a Website

It is crucial to understand the fundamentals of what you are working on. It is important get comfortable with the topics in the readings as these will lay the base for everything we learn in this course.

## Reading questions and answers

## Getting Started

1. **Describe how HTML, CSS, and JS files are “parsed” in the browser.** <br>
HTML is read first. It will start from top and go line by line. As it encounters external links and references, the browser will fetch those additional files. The browswer will, unless told otherwise, will save the the CSS construct, and JavaScript will compile and execute.

2. **How can you find images to add to a Website?**<br>
When looking for images to add to your website, make sure you are not infrenging upon any copyrights. Use the *Creative Common license* in google to reduce your chance of any violoation. Still, it is your responsibility to make sure your not violating any laws.

3. **How do you create a String vs a Number in JavaScript?**<br>
String can be made by encolsing text in single or double quotations.<br>
Numbers are kept as a number data type when they're not encapsulated by quotations.

4. **What is a Variable and why are they important in JavaScript?**<br>
Variables are a form of code that holds data. Variables in JavaScript can be dynamic and created by `let`, or constant and unchangable by making the variable with `const`.

5. **Compose a short poem describing how HTTP sends data between computers.**

>From client to server, data flows<br>
>Through HTTP's network hose<br>
>Requests sent and responses received<br>
>Information exchanged, connections achieved <br>

>A language of the web, HTTP speaks<br>
>Sending data across digital creeks<br>
>In packets, bits, and bytes it travels<br>
>As if on wings, it nimbly unravels<br>

>With URLs as its guiding star<br>
>HTTP takes data oh so far<br>
>From one computer to another it goes<br>
>Like a message in a bottle, it flows<br>

>So next time you surf the interweb<br>
>Think of HTTP and its threaded web<br>
>Sending data here and there<br>
>Making the internet a world to share.<br>

*This poem was created by* [**ChatGPT Feb 13 Version**](https://chat.openai.com/chat) *by feeding it the prompt "Compose a short poem describing how HTTP sends data between computers".*

I do not have verbal creativity and spent more time than necessary trying to make the just two lines of poem. So to answer the question in my own, non-poetic words:

When you load a website in your browser, your browser requests the website code from the servers. The servers parces portions of the HTML and sends it to your browser to read. As your broweser reads it and requires additional information, additional requests are sent and information is receieved. Your browswer continues to download these chuncks of data until the full website is generated.

### Metadata in HTML

1. **What is an HTML attribute?** <br>
An HTML attribute is a piece of code that adds additional information to an HTML element, changing how the element behaves.

2. **Describe the Anatomy of an HTMl element.**<br>
HTML element is composed of an opening and closing tag which surround the content of the element. An attribute, if required, is added to the opening tag.<br>
Not all elements will have a closing tag, such as `<img>`

3. **What is the Difference between `<article>` and `<section>` element tags?**<br>
An article element should house content and/or other elemets that, when seemed as a unit, can stand on its own. A section element tag should be used to group like items together. Sections can be conmposed of theveral other articles and vice versa.

4. **What Elements does a “typical” website include?**<br>
`<main>`, `<body>`, `<article>`, `<section>`, `<aside>`, `<header>`, `<nav>`, and `<footer>`

5. **How does metadata influence Search Engine Optimization?**<br>
Meta data is usually placed within the head element. With the following meta script, the content can be searched by search engines.<br>
`<meta name="description" content="My website is about...." />`<br>
Meaningful and descriptive content will increase likelihood your website is found when searched.

6. **How is the `<meta>` HTML tag used when specifying metadata?** <br> 
The `<meta>` HTML tag can be given a verity of attributes which will change its purpose. A few purposes of this tag can be 1. giving the website specifics on additional scripts (such as CSS and JS scripts), 2. provide the character that will code the website, 3. house the author and description information of the website, and 4. adding paths for proprietary creations made specific for a website.

### How to start to design a Website

1. **What is the first step to designing a Website?**<br>
The first step of designing a website is to have a vision of what you want to accomplish. You might know all of the technicalities on how to write the code, if you do not have vision of what you are trying to achieve, you will not create anything useful. 

2. **What is the most important question to answer when designing a Website?**<br>
What exactly do I want to accomplish?

### Semantics

1. **Why should you use an `<h1>` element over a `<span>` element to display a top level heading?**<br>
While multiple elements can be used interchangeably and achieve the same visual result in the page, using elements for their intended purpose will make your code more readable to others, as well make your website accessible for accessibility applications such as screen readers.

2. **What are the benefits of using semantic tags in our HTML?**<br>
It makes the code more readable to others, and you later for when revisiting the code. Additionally, as noted above, websites need to be build so they are accessible to others. Using the write elements will make your website accessible for accessibility applications such as screen readers. Proper use of semantic tags will also increase your page's search rankings.

### What is JavaScript

* **Describe 2 things that require JavaScript in the Browser?**<br>
JavaScripts can do many things in the Browser, but two described in the reading are:<br>

 > 1. Store information within variable which can be used in later parts of the code.
 > 2. Can execute code based on certain events in the website.

* **How can you add JavaScript to an HTML document?**<br>
You can add JavaScript to your HTML documents by three means:

> 1. Internal reference - You can use the tag `<script> </script>` which encapsulate JS code right within the `<head>` tag of the HTML file.
> 2. External reference - JS code will be stored in .js files. These files are tied to the HTLM code much like an CSS  file can be attached to an HTML file through a source.
> 3. Inline JavaScript handles - this JS code is actually within the HTML file, and not the head like an internal reference.

## Things I want to know more about

* How can you reach a websites directly via their IP addresses?

