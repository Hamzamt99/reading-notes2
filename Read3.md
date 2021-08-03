# HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML lists: allow web developers to group a set of related items in lists.

Example
An unordered HTML list:

Item
Item
Item
Item
An ordered HTML list:

First item
Second item
Third item
Fourth item
|An unordered HTML list| An ordered HTML list
|-----|-----
|Item|First item
|Item| second Item
|Item| Third Item
|Item| fourth Item

An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.
The list items will be marked with bullets (small black circles) by default:

### Example:
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
  
 ## CSS Flow Layout
Normal Flow, or Flow Layout, is the way that Block and Inline elements are displayed on a page before any changes are made to their layout.
  The flow is essentially a set of things that are all working together and know about each other in your layout. Once something is taken out of flow it works independently.

In normal flow, inline elements display in the inline direction, that is in the direction words are displayed in a sentence according to the Writing Mode of the document.
  Block elements display one after the other, as paragraphs do in the Writing Mode of that document.
  In English therefore, inline elements display one after the other, starting on the left, and block elements start at the top and move down the page.
  
  ## Js Control flow :
  
Control flow is in computer science the order that the instructions or statements or functions are executed.
  In javascript, we read the code starting from the first line till the last line unless of course in the code there is some instructions or statements that changes that control flow
  
## In CSS, the term "box model" is used when talking about design and layout.
  
![Css](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRfeVT7goMkFJP4OAbLMcX50JFZp2iL_PvTpA&usqp=CAU)

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.
  
## Explanation of the different parts:

+ Content - The content of the box, where text and images appear
+ Padding - Clears an area around the content. The padding is transparent
+ Border - A border that goes around the padding and content
+ Margin - Clears an area outside the border. The margin is transparent
