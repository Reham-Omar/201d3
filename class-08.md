## Read 8 :

# chapter 15: LAYOUT

* box will  be :
1- a block-level box  *start on a new line*
2- an inline box  *flow in Between surrounding text*

**parent element** :
 * the outer box which contain  one block-level element sits inside another block-level element

 * positioning schemes : allow you to control the layout of a page
 - normal flow : *The paragraphs appear one after the other, vertically down the page*
 **position:static**
 - relative positioning :*The 2nd paragraph has been pushed down and right , otherwise have been in normal flow*
 **position:relative**
 - absolute positioning :*The heading is positioned to the top right, and the paragraphs start at the top of the screen*
 **position:absolute**
 - fixed positioning : **position:fixed**
 
  *we specify it using the **position** property in CSS*

  * We use **box offset** : To indicate where a box should be positioned
  * **z-index property**  : its *overLapping element* allows you to control which box appears on top.

  * float property : allows you to take an element in normal flow and place it as far to the left or right of the containing element .
  
  * The clear property : allows you to say that no element should touch the left or righthand sides of a box.

  * to use multiple columns in your design ,usea <div> element to represent each column
  then set the properity use 1-width  2-float  3- margin 

  * We can include multiple CSS files in one page
  * Pages can be fixed width or liquid (stretchy) layouts.


  
