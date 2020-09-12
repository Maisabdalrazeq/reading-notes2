
# Welcom To the Read06 page ..

**What is the Object Literal in JavaScript?**

*A JavaScript object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables which can cause problems when combining code.*

*Object literal property values can be of any data type, including array literals, functions, and nested object literals*

Examples ..

`var myObject = {
    sProp: 'some string value',
    numProp: 2,
    bProp: false
};`

`var Swapper = {
    // an array literal
    images: ["smile.gif", "grim.gif", "frown.gif", "bomb.gif"],
    pos: { // nested object literal
        x: 40,
        y: 300
    },
    onSwap: function() { // function
        // code here
    }
};`


**Why and How We Use Object Literals?**

*Several JavaScripts from dyn-web use object literals for setup purposes. Object literals enable us to write code that supports lots of features yet still provide a relatively straightforward process for implementers of our code. No need to invoke constructors directly or maintain the correct order of arguments passed to functions. Object literals are also useful for unobtrusive event handling; they can hold the data that would otherwise be passed in function calls from HTML event handler attributes.*

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSDVYQTP37cmnok9FXQbMR443GpM22zknDwOw&usqp=CAU)


**What is the Document Object Model (DOM)?**

*The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page.*

*A Web page is a document. This document can be either displayed in the browser window or as the HTML source. But it is the same document in both cases. The Document Object Model (DOM) represents that same document so it can be manipulated. The DOM is an object-oriented representation of the web page, which can be modified with a scripting language such as JavaScript.*

Example..

`const paragraphs = document.getElementsByTagName("p");
// paragraphs[0] is the first <p> element
// paragraphs[1] is the second <p> element, etc.
alert(paragraphs[0].nodeName);`

**Dom tree..**

![image](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png)


**Hwo To Working with the DOM Tree?**

***Step 1:*** Access the elemnts .

***Step 2:***  Work with those elemnts.