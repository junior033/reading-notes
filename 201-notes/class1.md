## Reading 01

- Compose a short poem describing how HTTP sends data between computers.
  The browser goes to look for the address and sends an HTTPS request asking for the website, if approved it is then displayed on your client.

- Describe how HTML, CSS, and JS files are “parsed” in the browser.
  The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any
  <script>-element references to scripts. As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, 
  and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript. The browser generates an in-memory DOM tree from 
  the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript. As the browser builds the DOM tree 
  and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted on the screen, and the user sees the page 
  content and can begin to interact with it.
  
- How can you find images to add to a Website?
  When you find the image you want, click on the image to get an enlarged view of it.
  Right-click the image (Ctrl + click on a Mac), choose Save Image As…, and choose a safe place to save your image. Alternatively, copy the image's web address 
  from your browser's address bar for later use.
  
- How do you create a String vs a Number in JavaScript?
  `let myVariable = 'Bob';` `let myVariable = 10;`
  
- What is a Variable and why are they important in JavaScript?
  A variable is a container for a value, like a number we might use in a sum, or a string that we might use as part of a sentence.

- What is an HTML attribute?
  Attributes contain extra information about the element that won't appear in the content.
  An attribute should have: A space between it and the element name. (For an element with more than one attribute, the attributes 
  should be separated by spaces too.)The attribute name, followed by an equal sign.
  An attribute value, wrapped with opening and closing quote marks.

- Describe the Anatomy of an HTML element.

  The anatomy of our element is:
    The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. 
    This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
    The content: This is the content of the element. In this example, it is the paragraph text.
    The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element 
    ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.
  
- What is the Difference between <article> and <section> element tags?
  The section tag defines sections in a document, such as chapters, headers, footers, or any other sections of the document.
  The article tag specifies independent, self-contained content.


- What Elements does a “typical” website include?
  Header, Nav bar, Main Content, Sidebar, and footer.

- How does metadata influence Search Engine Optimization?
  Specifying a description that includes keywords relating to the content of your page is useful as it has the potential 
  to make your page appear higher in relevant searches performed in search engine

- How is the <meta> HTML tag used when specifying metadata?
  Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document.


- What is the first step to designing a Website?
  Project ideation:
    What exactly do I want to accomplish?
    How will a website help me reach my goals?
    What needs to be done, and in what order, to reach my goals?

- What is the most important question to answer when designing a Website?
  What exactly do I want to accomplish?

- Why should you use an <h1> element over a <span> element to display a top level heading?
  the `<h1>` element is more appropriate to make a top-level heading as it best for titles. Where the span tag is better used when you need to a
  break in some text.
  
- What are the benefits of using semantic tags in our HTML?
  Semantics is important because it gives context to the purpose of the information's intent.

- What is JavaScript?
  JavaScript is a scripting or programming language that allows you to implement complex features on web pages.

- Describe 2 things that require JavaScript in the Browser?
  Interactivity and 2d/3d maps

- How can you add JavaScript to an HTML document?
  You can add JS to your HTML document with the `<script></script>` tag.


## Things I want to know more about
  How popular is JavaScript used on the server side.
