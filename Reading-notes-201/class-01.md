# Read: Class 01

## Getting Started

1. Compose a short poem describing how HTTP sends data between computers.  

    *The browser goes to the DNS*  
    *And asks the server for the site's address.*  
    *The browser sends the server a message in HTTP,*  
    *Asking it to copy the website to a T.*  
    *The server then approves the request with a "200 OK"*  
    *And then sends the site's files in data packets to make the user's day.*  
    *The data packets are assembled into a web page.*  
    *It is displayed to the user, who is such a sage.*  

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.  

    *The browser parses the HTML first and looks for any CSS or JavaScript links within the HTML. It then parses the CSS and JavaScript documents. It then creates a DOM from the HTML and a CSSOM from the CSS, and executes the JavaScript. As this is happening, the website starts to be displayed on the screen for the user to see and interact with.*

3. How can you find images to add to a Website?  
  
    *Go to Google images and click "Tools", "Usage Rights", then "Creative Common Licenses". Then Right click on the image you want and click "Save image as". Name the image and choose where you want to store the image to your local computer. You can drag and drop that image in VS Code whenever you want to use it for a website.*

4. How do you create a String vs a Number in JavaScript?  
    *A string is created when you enclose a value inside single or double quotation marks. A number is created when there are no quotation marks around the value.*

5. What is a Variable and why are they important in JavaScript?  
    *A variable is a container that stores values. They are important in JavaScript because they allow a web page to actually function dynamically*

## Introduction to HTML

1. What is an HTML attribute?  
    *An HTML attribute is a container of extra information that won't display in the content.*

2. Describe the Anatomy of an HTMl element.  
    *An HTML element has an opening and closing tag. Wrapped within the tags is the content. You can also nest elements within other elements.*

3. What is the Difference between `<article>` and `<section>` element tags?  
    *`<article>` is an element that sets apart a group of related content that makes sense on its own. `<section>` is an element that groups together a part of the page that uses one piece of functionality.*

4. What Elements does a “typical” website include?  
    *A "typical" website includes the `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<div>`, `<aside>`, and `<footer>` elements.*

5. How does metadata influence Search Engine Optimization?  
    *Metadata influences Search Engine Optimization by specifying a description that has keywords of the content of a page. The keywords will make the page appear higher in the list when looked up using a search engine.*

6. How is the `<meta>` HTML tag used when specifying metadata?  
    *The `<meta>` HTML tag is used by placing it in the `<head>` of an HTML file.*

## How to start to design a Website

1. What is the first step to designing a Website?  
    *The first step is to complete project ideation. This is answering questions about what goals you have and how you will reach your goals.*

2. What is the most important question to answer when designing a Website?  
    *The most important question to answer when designing a website is "What exactly do I want to accomplish?"*

## Semantics

1. Why should you use an `<h1>` element over a `<span>` element to display a top level heading?  
    *You should use an `<h1>` element over a `<span>` element because the `<h1>` element is semantic, meaning it has a purpose and, therefore, has the benefits of styling that go along with it. It also makes the HTML file a lot more readable.*

2. What are the benefits of using semantic tags in our HTML?  
    *Some benefits are search engines will see the semantic elements as keywords it can use to list the website, screenreaders can read them as signposts to help the visually impaired, finding blocks of meaningful code is easier than sifting through meaningless non-semantic elements, tells the developer the type of data that will be displayed, and semantic naming mirrors proper custom element naming.*

## What is JavaScript?

1. Describe 2 things that require JavaScript in the Browser?  
    *Run commands based on user input and store useful values inside variables.*

2. How can you add JavaScript to an HTML document?  
    *You can add JavaScript to an HTML document by linking a JavaScript file in the `<head>` element using a `<style>` tag, by creating JavaScript inside the `<style>` element which will sit inside the `<head>` element, or by adding the JavaScript functions within any HTML element.*
