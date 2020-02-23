# read 06

# Article:

* I read that when I write code more and more,I can understand the problem which is the most critical piece to the equation more and more.
* It is very difficult to solve a problem before you know the question.  
* It’s like buzzing in on Jeopardy before you hear the clue and shouting out random questions.

# chapter(3 & 5) in JS book :
 
 ## whats the object ?

* *Objects* : group together a set of variables and functions to create a model of a something .

* the variable become known as property
* the function become known as method 

* The most popular to creat an object  is literal notation .
* we can access the properity and the method using dot nottation .

* *The Document Object Model* : specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window
**but** *The DOM is neither part of HTML, nor part of JavaScript*.

* It covers two primary areas:

1-MAKING A MODEL OF THE HTML PAGE|2-ACCESS AND CHANGING THE HTML PAGE|
| ------------- | ------------- |
|We use DOM tree to specify browser structure  | It called Application Programming Interface (API)|
| Accessing and updating the DOM tree involves two steps:|------ |
| 1: Locate the node that represents the element you want to work with. |------|
| 2: Use its text content, child elements, and attributes. |----- |


* Each node is an object with methods and properties and we have 2 nodes :
1- ATTRIBUTE NODES
2- TEXT NODES

* DOM queries may return :
  one element| Nodelist|
| ------------- | ------------- |
| getElementByld('id) | getElementsByClassName('class')|
| querySelector('css selector')| getElementsByTagName('tagName')|
| ------| querySelectorAll ('css selector')|

*  node Value property : retrieve or amend the content of text node .
* The textContent  : allows you to collect or update just the text that is in the containing element (and its children).
*  We use removeAttribute () to remove attribute .
