# Dynamic web pages with JavaScript #

#### The document object represents an HTML page ####

Using the document object, you can access and change what content users see on the page and respond to how they interact with it.

- Properties: Properties describe characteristics of the current web page (such as the title of the page).
- Methods: Methods perform tasks associated with the document currently loaded in the browser (such as getting information from a specified element or adding new content).
- Events: You can respond to events, such as a user clicking or tapping on an element.

#### How a browser sees a webpage? ####

1. Receive a page as HTML code: Each page on a website can be seen as a separate document . So, the web consists of many sites, each made up of one or more documents.
2. Crate a model of the page and store it in memory: The model shown on the right hand page is a representation of one very basic page. Its structure is reminiscent of a family tree. At the top of the model is a document object, which represents the whole document.
3. Use a rendering engine to show the page on screen: If there is no CSS, the rendering engine will apply default styles to HTML elements. However, the HTML code for this example links to a CSS style sheet, so the browser requests that file and displays the page accordingly.

- All major browsers use a JavaScript interpreter to translate your instructions (in JavaScript) into instructions the computer can follow.

#### How HTML,CSS&JAVASCRIPT fit together ####

Before diving into the JavaScript language, you need to know how it will fit together with the HTML and CSS in your web pages.

Web developers usually talk about three languages that are used to create web pages: HTML, CSS, and JavaScript.

- <html>: CONTENT LAYER .html files
This is where the content of the page lives. The HTML gives the page structure and adds semantics.

- {css} : PRESENTATION LAYER .css files
The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.).

- javascript(): BEHAVIOR LAYER .js files
This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files.

**Progressive Enhancement**
These three layers form the basis of a popular approach to building web pages called progressive enhancement.

- HTML only : Starting with the HTML layer allows you to focus on the most important thing about your site: its content.
Being plain HTML, this layer should work on all kinds of devices, be accessible to all users, and load quite quickly on slow connections.

- HTML+CSS : Adding the CSS rules in a separate file keeps rules regarding how the page looks away from the content itself.
You can use the same style sheet with all of your site, making your sites faster to load and easier
to maintain. Or you can use different style sheets with the same content to create different views of the same data.

- HTML+CSS+JAVASCRIPT : The JavaScript is added last and enhances the usability of the page or the experience of interacting with the site.
Keeping it separate means that the page still works if the user cannot load or run the JavaScript. You can also reuse the code on several pages (making the site faster to load and easier to maintain).

#### Creating a basic javascript ####

JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script. This example adds a greeting into an HTML page. The greeting changes depending on the time of day.

1. Create a folder to put the example in called cOl, then start up your favorite code editor, and enter the text to the right.
A JavaScript fi le is just a text file (like HTML and CSS filesare)butithasa.jsfile extension, so save this file with the name add-content.js

2. GettheCSSandimagesfor this example from the website that accompanies the book: www.javascriptbook. com
To keep the files organized, in the same way that CSS files often live in a folder called styles or css, your JavaScript files can live in a folder called scripts,javascript,orjs. In this case, save your file in a folder called js

3. In your code editor, enter the HTML shown on the left. Save this file with the name add-content.html
The HTML <script> element is usedtoloadtheJavaScriptfile into the page. It has an attribute called src, whose value is the path to the script you created.
This tells the browser to find and load the script file (just like the src attribute on an <img>tag).
  
4. Open the HTML file in your browser. You should see that the JavaScript has added a greeting (in this case, Good Afternoon!) to the page. (These greetings are coming from the JavaScript file; they are not in the HTML file.)

5. Once you have tried the example in your browser, view the source code for the page.
( This option is usually under the View, Tools or Develop menu of the browser.)

6. Once you have tried the example in your browser, view the source code for the page.
( This option is usually under the View, Tools or Develop menu of the browser.)

7. Finally, try opening the HTMLfile, removing the src attribute from the opening <script> tag, and adding the new code shown on the left between the opening <script> tag and the closing </script> tag. The sre attribute is no longer needed because the JavaScript is in the HTML page.
  
8. Open the HTML file in your web browser and the welcome greeting is written into the page.


### Basic Javascript instructions ###

- A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a **statement**.
Statements should end with a semicolon.

- **JAVASCRIPT IS CASE SENSITIVE**
JavaScript is case sensitive so hourNow means something different to HourNow or HOURNOW.

- You should write **comments**  to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.

- A script will have to temporarily store the bits of information it needs to do its job. It can store this data in **variables.**

- 


