# Class 03
## HTML
### Chapter 3: Lists
- 3 types of HTML lists: ordered, unordered, definition. ALl 3 use 'li' as the 'list item' element for each item.
- Ordered lists are numbered.
- Unordered lists are bulleted. These notes appear in an unordered list.
- Definition lists are a list of terms with their definitions indented on the next line.
- A second list can appear inside an 'li' element to create a sub- or nested list.


### Chapter 13: Boxes
- CSS treats every HTML element as if it were inside its own box.
- Boxes default to a size that is just big enough to hold their contents. You can choose to set your own height and width properties.
- If pages automatically shrink or expand to fit the user's screen, you can set a min/max width or height to choose the smallest and largest box sizes for the page, respectively. 
- If the content within a box is larger than the box itself, the overflow property tells the browser what to do with it: you can hide it, or add scroll bars.
- Border, margin, and padding can be adjusted to control the appearance of a box. The border separates the edge of one box from another. The margins can create a gapk between the borders of 2 adjacent boxes. Padding is the space between the border of the box and the content within it.
- Boxes can be hidden using the visibility property. They will be hidden from users, but will still leave a space where the element would've been.


## JavaScript
### Chapter 4: Decisions & Loops
- If else statements are for setting conditions. If X occurs, Y will happen. Else, Z will happen.
- A switch statement indicates that there are multiple different cases for a variable, and the code should run if the variable matches a case. In terms of creating a game with JavaScript prompts, a switch statement can be used to communicate a different message to the user depending on which level they're at.
- Type coercion is when JavaScript converts data on its own to try and complete an operation, rather than reporting an error message. 
- JavaScript uses weak typing, because the data type for a value can change. Other languages require you to specify what each data type will be. This is called strong typing.
- It's better to use strict equals operators to ensure that value and data types match up. This avoids unexpected values and errors in your code.
- Type coercion means that every value in JS can be treated as if it were true or false. 
- Falsy values include: false, 0, '', 10/'score' (not a number), and variables with no value assigned.
- Truthy values include: true, 1, strings with content, number calculations, 'true' written as a string, '0' written as a string, and 'false' written as a string.
- Loops check a condition. If the result is true, the code will run. The loop will keep checking, therefore will keep running so long as the result is true.
- 3 types of loops: for, while, do while.
