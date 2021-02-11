# Class 6 Reading
# Object Literals

This is a declarative syntax using the name of the class that you want to create, followed by a list of initializers and definitions for this specific instance

When declaring an object literal, the instance variables may be separated by commas or whitespace, as well as the semi-colon.

 _Object literals_ enable us to write code that supports lots of features yet still provide a relatively straightforward process for implementers of our code. No need to invoke constructors directly or maintain the correct order of arguments passed to functions. Object literals are also useful for unobtrusive event handling; they can hold the data that would otherwise be passed in function calls from HTML event handler attributes.


 # DOCUMENT OBJECT MODEL


The Document Object Model (DOM) is a cross-platform and language-independent interface that treats an XML or HTML document as a tree structure wherein each node is an object representing a part of the document. The DOM represents a document with a logical tree. Each branch of the tree ends in a node, and each node contains objects.


 ![image](https://i.ytimg.com/vi/RbQGn6vBlys/maxresdefault.jpg)


 The Document Object Model (DOM) is a cross-platform and language-independent interface that treats an XML or HTML document as a tree structure wherein each node is an object representing a part of the document. The DOM represents a document with a logical tree. Each branch of the tree ends in a node, and each node contains objects.

 When a web page is loaded, the browser creates a Document Object Model of the page, which is an object oriented representation of an HTML document that acts as an interface between JavaScript and the document itself. This allows the creation of dynamic web pages,[9] because within a page JavaScript can:

    - add, change, and remove any of the HTML  elements and attributes

    - change any of the CSS styles
    - react to all the existing events
    - create new events

 
 DOM trees have four types of nodes:
     
     1- document nodes
     2- element nodes 
     3- attribute nodes
     4- text nodes.

 * You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.

 * Whenever a DOM query can return more than one
node, it will always return a Nadelist.

 * From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.

 * An element node can contain multiple text nodes and child elements that are siblings of each other.

 * In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).

 * Browsers offer tools for viewing the DOM tree. 
