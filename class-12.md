# Class 12 Reading
# Charts

![image](https://www.wysiwygwebbuilder.com/images/ChartJS_large.jpg)

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

# How to draw the charts of all kindes some of chart types :

    - bar chart
    - line chart
    - pie chart

it's an element used to draw graphics via javascript, it's just a container and must have an id, it has two attribute width , height .

The element has a method called \<getContext()>, used to obtain the rendering context and its drawing functions. I learned how to draw rectangles, triangles, lines, arcs and curves only supports two primitive shapes: rectangles and paths (lists of points connected by lines)

## There are three functions that draw rectangles on the canvas:

   - fillRect(x, y, width, height) Draws a filled rectangle.

   - strokeRect(x, y, width, height) Draws a rectangular outline.

   - clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent.

For drawing straight lines, use the \<lineTo()> method. To draw arcs or circles, we use the \<arc()> or \<arcTo()> methods


# EJS Partials (Embedded JavaScript) 
Mainly to reuse the same HTML across multiple views.

It makes large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file and include it wherever you need it.

# How to create those partials
## Example

For same navigation bar and footer appear in both the home and post view. This makes them perfect candidates for partials!

Under the views/partials/ directory create a file called navbar. 
ejs which will contain only the HTML for the navigation bar at the top of the home and post pages

footer.ejs in that same directory

Now that we have our partials defined, we can use them in our home.ejs and post.ejs templates!

Notes

In EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by <% %> delimiters

The <%- %> tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include() statement since you don’t want EJS to escape your HTML characters like ‘<’, ‘>’