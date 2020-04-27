# Read 01
## HTML
### Chapter 1: Structure
- HTML is a language that sets the structure of a web page. 
- Characters between <> brackets are called "elements." Elements contain an "opening tag" and a "closing tag."
- HTML tags indicate that all code appearing between them will be HTML.
- Anything inside the 'body' tag will appear in the main browser window.
- Paragraphs of text appear between 'p' tags.
- 'H' tags display headings of various sizes, depending on the number used. h1, h2, h3, etc. As the number increases, the size of the heading gets smaller.
- Attributes provide more information about elements. p lang="en-us" Paragraph in English /p represents that the contained paragraph is in the English language.

### Chapter 8: Extra Markup
- HTML has evolved since it was first created. In 2000, HTML4 was reworked into XHTML 1.0. The textbook follows the strict rules of XHTML, while also incorporating aspects of HTML5, despite HTML5 not yet being complete.
- Because there are multiple types of HTML, documents should all begin with a !DOC TYPE declaration so the browser knows which version the web page is using.
- Comments can be added to HTML code using !-- --. These comments won't be visible on the web page and can be used to clarify lines of code if you need to come back to it later or have someone else look at it.
- As mentioned in Chapter 1, elements can have attributes describing what they are. ID attributes uniquely identify one element over others on the page, and it's important that no two elements on the same page have the same attribute: otherwise they'll no longer be unique.
- Class attributes can be attached to multiple elements to describe them in the same way.
- Block level elements always appear to start a new line in the browser. h1, p, ul, li are examples of block level elements.
- Elements that continue on the same line as their neighbors are called inline elements, such as a, b, em, and img.
- The div element allows one to group a set of elements together in a single, block-level box. If there are multiple elements needed to create a header (img, ul, li), they can be contained within the div element to keep them all together.
- The span element can: contain a set of text when there aren't any other suitable elements to differentiate it from the surrounding text, or contain a number of inline elements. Span is used to control the appearance of the content of these elements using CSS.
- An iframe can be used to insert a window containing a page into another page. The best example is embedding a Google Map into a page. This element must contain src, height, and width attributes. Further attributes include scrolling, a frameborder, or seamless (an iframe that doesn't have scrollbars).
- The meta element contains information about a page: description, keywords, robots (if search engines should add this page to their results), author, pragma (prevents the browser from caching the page), or the expiration date if the page should no longer be cached after a certain date.

### Chapter 17: HTML5 Layout
- Several elements are specific to the new HTML5: header, nav, article, aside, footer. In previous versions of HTML, these items would've been attributes in the div class.
- The section element is used to group related content together, each section having its own heading. Different sections of a page would be things like news, shopping, food, etc.
- Heading groups do exactly that: they group headings together. This was originally rejected in the development of HTML5 and people preferred to add subheadings to a section, but it's since been brought back.
- The figure element can contain any content that is referenced from the main flow of an article: images, video, graphs, diagrams, etc. This element should also contain a figcaption element to provide a text caption of the contained content.
- An entire block can be turned into a link if it's contained inside an "a" element.

### Chapter 18: Process & Design
- One must understand his or her target audience when designing a website. It's important to know what kind of information they'll be looking for and when they're likely to visit the site again.
- Designing a site map allows one to plan the structure of a site. The site map can be written as a sort of "tree" with branches extending out to represent links.
- Creating a wireframe can organize the information that needs to go on each page.
- Visual hierarchy helps visitors understand a message. More important messages will be represented by larger or bolder text or imaging.
- Grouping and similarity can help simplify information, while size, color, and style can differentiate between information.

## Javascript
### Chapter 1: The ABC of Programming
- A script is a series of instructions used to tell the computer what to do.
- Once a goal is set, it's helpful to sketch out the required tasks in a flowchart. 
- Each physical thing in the world is called an object. There can be one or multiple instances of an object. Each object can have its own properties, events, and methods. 
- Scripts use events to trigger different functions. When a specific event happens, it can trigger a specific set of code.
- A task can be represented by a group of instructions, contained within a method. As a programmer it's important to know how to ask the right question and interpret the answer, rather than knowing exactly how a task is achieved.
- Web browsers use window objects and document objects. The window object defines the location of the page within the URL. The document object is the content that appears on the web page. 
- The document object allows one to change what content users see on the page and how they can interact with it.
- The browser receives an HTML page, creates a model of it and stores it in memory (caching?), then shows the page on screen using a rendering engine.
- HTML, CSS, and JavaScript work together in layers to form a webpage. HTML sets the layout, CSS is used to alter colors and appearances, and JavaScript is the final layer that adds interaction to the page: a personalized greeting, a time clock, etc.
