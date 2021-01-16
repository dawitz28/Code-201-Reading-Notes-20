**TABLES (HTML)**
**What's a Table?**
- The <table> element adds tables to a webpage
- Tables are drawn out row by row
- Longer tables can be split up using: thead, tbody, and tfoot
- A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.
- Grids allow us to understand complex data by referencing information on two axes.
- Each block in the grid is referred to as a table cell. In HTML a table is written out row by row.
##basic Table structure##
- table The table element is used to create a table. The contents of the table are written out row by row.

- tr You indicate the start of each row using the opening tr tag. (The tr stands for table row.)
- It is followed by one or more td elements (one for each cell in that row).
- At the end of the row you use a closing tr tag.
- td - Each cell of a table is represented using a td element. (The td stands for table data.)
- At the end of each cell you use a closing td tag.
- The th element is used just like the td element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.)
- Even if a cell has no content, you should still use a td or th element to represent the presence of an empty cell otherwise the table will not render correctly. (The first cell in the first row of this example shows an empty cell.)
- Using th elements for headings helps people who use screen readers, improves the ability for search engines to index your pages, and also enables you to control the appearance of tables better when you start to use CSS.
- You can use the scope attribute on the th element to indicate whether it is a heading for a column or a row. It can take the values: row to indicate a heading for a row or col to indicate a heading for a column.
##Functions, Methods, and Objects (JS)##
- CREATING OBJECTS USING CONSTRUCTOR SYNTAX
**FUNCTIONS & METHODS**
- Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements) 

- Functions consist of a series of statements that have been grouped together because they perform a specific task.
- A method is the same as a function, except methods are created inside (and are part of) an object. 
**OBJECTS**
In Chapter 1 you saw that programmers use objects to create models of the world using data, and that objects are made up of properties and methods. In this section, you learn how to create your own objects using JavaScript
**BUILT-IN OBJECTS**
- The browser comes with a set of objects that act like a toolkit for creating interactive web pages. This section introduces you to a number of built-in objects, which you will then see used throughout the rest of the book. 
- Once it has been created, three properties and a method are then assigned to the object. (If the object already had any of these properties, this would overwrite the values in those properties.) To access a property of this object, you can use dot notation, just as you can with any object.

- The new keyword and the object constructor create a blank object. You can then add properties and methods to the object.
- 	Create a new object using a combination of the new keyword and the Object () constructor function. ("Object ()" used to create functions)
- 	Utilizing the blank object, you can add properties and methods to it using dot notation. Each statement that adds a property or method should end. 
- To update value of properties, use dot notation. They work on objects created using literal or constructor notation. To delete a property, use the delete keyword.
- This keyword! Commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates
- Arrays are a special type of object. They hold a related set key/value pairs, but the key for each value is its index number
Arrays and objects are combinable and can create complex data structures: arrays can store a series of objects. Objects can also hold arrays
- The Math object has properties and methods for mathematical constants and functions

