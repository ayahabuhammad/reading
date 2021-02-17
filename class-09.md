# Class 9 Reading

# Forms


An HTML form is used to collect user input. The user input is most often sent to a server for processing.
The \<form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

![image](https://i.pinimg.com/originals/30/a2/1d/30a21d1daf0ab20a243b5a5291ce6d1d.jpg)


All the different form elements are covered in this chapter: 

## HTML Form Elements:


        - The <input> Element

        - The HTML <input> element is the most used form element.

        - An <input> element can be displayed in many ways, depending on the type attribute.


Here are some examples:
Type	Description
 - <input type="text">	Displays a single-line text input field.

 - <input type="radio">	Displays a radio button (for selecting one of many choices)

 - <input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)

 - <input type="submit">	Displays a submit button (for submitting the form)

 - <input type="button">	Displays a clickable button

# Define an HTML Table

The \<table> tag defines an HTML table.
Each table row is defined with a \<tr> tag. Each table header is defined with a \<th> tag. Each table data/cell is defined with a \<td> tag.
By default, the text in \<th> elements are bold and centered.
By default, the text in \<td> elements are regular and left-aligned.

Example
A simple HTML table:

        <table style="width:100%">
             <tr>
                 <th>Firstname</th>
                     <th>Lastname</th> 
                     <th>Age</th>
                         </tr>
                           <tr>
                              <td>Jill</td>
                                <td>Smith</td> 
                            <td>50</td>
                         </tr>
                       <tr>
                       <td>Eve</td>
                    <td>Jackson</td> 
                  <td>94</td>
             </tr>
      </table>


Example
A simple HTML table:

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td> 
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td> 
    <td>94</td>
  </tr>
</table>

# Event in JavaScript
![image](https://cdn-images-1.medium.com/max/1200/1*-MMBHKy_ZxCrouecRqvsBg.png)

 HTML lists allow web developers to group a set of related items in lists.

Example
An unordered HTML list:

      Item
      Item
      Item
      Item
An ordered HTML list:

     1- First item
     2- Second item
     3- Third item
     4- Fourth item



HTML Description Lists
HTML also supports description lists.

A description list is a Lists
- HTML events are "things" that happen to HTML elements.

-  When JavaScript is used in HTML pages, JavaScript can "react" on these events.

# HTML Events
An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

- An HTML web page has finished loading
- An HTML input field was changed
- An HTML button was clicked

-  Often, when events happen, you may want to do something.

- JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.
With single quotes:


\<element event='some JavaScript'>
With double quotes:

\<element event="some JavaScript">
In the following example, an onclick attribute (with code), is added to a \<button> element:


## Example

     <button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>

<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>

In the example above, the JavaScript code changes the content of the element with id="demo".

In the next example, the code changes the content of its own element (using this.innerHTML):

## Example

       <button onclick="this.innerHTML = Date()">The time is?</button>

 <button onclick="this.innerHTML = Date()">The time is?</button>