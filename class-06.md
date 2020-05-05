# Class 06
## Article
- "Programming is easy if you understand the problem domain." 
- Programming can be difficult at times because one doesn't always understand the bigger picture when assigned to modify a small piece.
- Programming can become easier by: making the problem domain easier, or getting better at understanding the problem domain.
- Cut out certain cases and narrow focus to a particular part of the problem.

## JavaScript
### Chapter 3: Object Literals
- If a variable is part of an object, it becomes a property. 
- If a function is part of an object, it's called a method (tasks associated with the object). 
- The name in an object is called a key. An object can't have 2 keys in the same name. Keys are used to access corresponding values (string, number, Boolean, array, etc.) The value of a method is always a function.
- Properties and methods can be accessed using dot notation. var x = object.property/methodname();

### Chapter 5: Document Object Model
- "The Document Object Model specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window."
- The DOM is separate from HTML and JavaScript, and is used for making a model of the HTML page, or accessing and changing the HTML page.
- The DOM is an Application Programming Interface.
- A document node at the top of the DOM model represents an entire page.
- Element nodes describe the structure of an HTML page. 
- Attribute nodes carry attributes.
- Text nodes represent the text within an HTML element.
- One can access the individual elements on a DOM tree for modification.
- DOM queries are the methods that find elements in the DOM tree.
- "When people talk about storing elements in variables, they're really storing the location of the elements within the DOM tree in a variable. The properties and methods of that element node work on the variable."
- Elements can be accessed by ID, CSS selector, class, and tagName. 