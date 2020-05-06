# Class 09
## HTML
### Chapter 7: Forms
- Text input: for a single line of text, such as an email address or name.
- Password: a single line text input box that masks the entered characters.
- Text area: for longer areas of text such as messages and comments.
- Radio buttons: when a user must select one of a number of options.
- Checkboxes: when a user can select and unselect one or more options.
- Drop-down boxes: when a user must pick one of a number of options from a list.
- Submit button: to submit data from your form to another web page.
- Image button: an image used as a submit button.
- File upload: allows users to upload files to a website.
- The name of the form and its entered values are sent to the server. The server processes the information using a programming language (PHP, C#, VB.net, Java). It can also store the information in a database. Then the server creates a new page to send back to the browser based on the information received.
- The server uses form controls to know which piece of inputted data corresponds with which form element. 
- \<form action="URL" method="get OR post"> begins a form element. Every form requires an action attribute.
- Get: Values are entered at the end of the URL specified in the action attribute. Ideal for short forms or retrieving data from the web server.
- Post: Values are sent in what are known as HTTP headers. Ideal for allowing users to upload a file, long forms, forms that contain sensitive data, and forms that add information to/delete information from a database.
- Input: text, set a maxlength to limit the number of characters, radio button, checkbox, file input box, submit button, image button, button & hidden controls.
- \<label> to label form controls: wrap around both the text description and the form input. "For" states which form control the label belongs to.
- \<fieldset> groups related controls together. Helpful for longer forms.
- \<legend> contains a caption that helps identify the purpose of that group of form controls.
- Form validation: gives users messages if the form has not been filled in correctly. Validating helps reduce the amount of work the server has to do and enables users to see if there are problems within the form faster than if validation were performed on the server.
- Type="date" assigns the type attribute a value of "date." Can also be used for email, URL, etc.
- Type="search" creates a single line text box for search inquiries.

### Chapter 14: Lists, Tables, & Forms:
- Bullet point styles: none, disc, circle, square.
- Ordered list: decimal, decimal-leading-zero, lower-alpha, upper-alpha, lower-roman, upper-roman.
- Images for bullets: CSS "list-style-image: url("url");
- Table properties: width (sets the width of a table), padding (sets the space between the border of each table cell and its content), text-transform (covnerts the content of the table headers to uppercase) letter-spacing/font-size (adds additional styling to the content of the table headers), border-top/bottom (sets borders), text-align, background-color, :hover (highlights a table row when a user's mouse goes over it). 

## JavaScript
### Chapter 6: Events
- UI events: load, unload, error, resize, scroll.
- Keyboard events: keydown, keyup, keypress.
- Mouse events: click, dblclick, mousedown, mouseup, mousemove, mouseover, mouseout.
- Focus events: focus/focusin, blur/focusout.
- Form events: input, change, submit, reset, cut, copy, paste, select.
- Mutation events: DOMSubtreeModified, DOMNodeInserted, DOMNodeRemoved, DOMNodeInsertedIntoDocument,
DOMNodeRemovedFromDocument.
- How events trigger JS code: **Event handling:** Select the element node(s) you want the script to respond to. Indicate which event on the selected nodes will trigger the response. State the code you want to run when the event occurs. 
- Event handling is used to provide feedback to users filling in a form: select element, specify event, call code.
- 