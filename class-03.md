- Chapter 3 
-  HTML provides us with three different types of list:
- Ordered lists: are lists where each item in the list is numbered. 
- Unordered lists: are lists that begin with a bullet point rather than characters that indicate order.
- Definition lists: are made up of a set of terms along with the definitions for each of those terms.
- You can also put a second list inside an <li> element to create a sub-list or nested list. 
. Chapter 13. Boxes
- Box Dimensions is controlled by its width and height. 
- By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties.
- The most popular ways to specify the size of a box are to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size.
- When you use percentages, the size of the box is relative to the size of the browser window or, if the box is encased within another box, it is a percentage of the size of the containing box
- When you use ems, the size of the box is based on the size of text within it. Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens.
- limiting width (min-width, max-width)
- ome page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.
- These are very helpful properties to ensure that the content of pages are legible (especially on the smaller screens of handheld devices). For example, you can use the max-width property to ensure that lines of text do not appear too wide within a big browser window and you can use the min-width property to make sure that they do not appear too narrow.
- Limiting height (min-height, max-height)
- In the same way that you might want to limit the width of a box on a page, you may also want to limit the height of it. This is achieved using the min-height and max-height properties.
- If the box is not big enough to hold the content, and the content expands outside the box it can look very messy. To control what happens when there is not enough space for the content of a box, you can use the overflow property. 
- Overflowing content (Overflow)
The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:
- Hidden:- This property simply hides any extra content that does not fit in the box.
- Scroll:- This property adds a scrollbar to the box so that users can scroll to see the missing content.
- The overflow property is particularly handy because some browsers allow users to adjust the size of the text to appear as large or as small as they want. If the text is set too large then the page can become an unreadable. Hiding the overflow on such boxes helps prevent items overlapping on the page.
- Border width (border-width)
- The border-width property is used to control the width of a border. The value of this property can either be given in pixels or using one of the following values:
- •	thin
- •	medium
- •	thick
- (You cannot use percentages with this property.) You can control the individual size of borders using four separate properties:
•	border-top-width
•	border-right-width
•	border-bottom-width
•	border-left-width
- You can also specify different widths for the four border values in one property, like so:border-width: 2px 1px…;

- The values here appear in clockwise order: top, right, bottom, left.
- IF...Else statements

- Here you can see that an if...else statements allows you to provide two sets of code:
1.	one set if the condition evaluates to true
2.	another set if the condition is false
- In this test, there are two possible outcomes: a user can either get a score equal to or greater than the pass mark (which means they pass), or they can score less than the pass mark (which means they fail). One response is required for each eventuality. The response is then written to the page.
- Note that the statements inside an if statement should be followed by a semicolon, but there is no need to place one after the closing curly brace of the code blocks.

- Decisions and Loops
 -Switch Statements. A swtich statement starts with a variable called the switch value. Each case indicates a possible value for this variable.

- The script checks the value of the variable varName. If varName === n1 it does the first thing. If varName does not equal any of the cases the statements in default are run.
- Type Coercion: JavaScript will change a variable type to complete an operation. For example '6' > 4 will evaluate true because the string '6' will automatically be converted to an number.
- Truthy & Falsy Values
- Due to type coercion every value in JavaScript can be treated as if it were true or false. Falsy values can also be treated as 0 and truthy values can be treated as 1.
Because the presence of an object or array can be considered truthy, it is often used to check for the existence of an element within a page.