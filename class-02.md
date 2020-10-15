#Class 2 notes
 
- Text
- There are two different kind of markups in this chapter that we’ll focus on how to  add markup to the text that appears on our pages.
- Structural markup: The elements used to describe headings and paragraphs.
- Semantic markup: Provides extra information such as emphasis on a character or a  quotation.

- Heading  HTML has six "levels" of headings
 <h1> is used for main headings <h2> is used for  If there are further sections under the subheadings then the <h3> element is used and so on. 

Paragraphs <p>
-	To create a paragraph, surround the words that make up the paragraph with an opening <p> tag and closing </p> tag. 

- Bold
- <b> By enclosing words in the tags <b> and </b> we can make characters appear      bold.

- Italic 
 <i> By enclosing words in the tags <i> and </i> we can make characters appear Italic. 

- <br />
- As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag.
- CSS 
- CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.
- CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration. 
- CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon. 

 - <link> 
-	element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element. It should use three attributes: 
href 
-	This specifies the path to the CSS file (which is often placed in a folder called css or styles). 
- type 
-This attribute specifies the type of document being linked to. The value should be text/css. 
rel 
-	This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file. 


- <style> 
-	You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page. 
The <style> element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/ css. 

- CSS Selectors
-	There are many different types of CSS selector that allow you to target rules to  specific elements in an HTML document. 

-	CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look. 

-	Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like). 

-	Different types of selectors allow you to target your rules at different elements. 

-	Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface. 

-	CSS rules usually appear in a separate document, although they may appear within an HTML page. 

# Chapter 2, 
# JavaScript: Basic JavaScript
# What is JavaScript
- JavaScript is an object orient programming language designed to make web development easier and more attractive. In most cases, JavaScript is used to create responsive, interactive elements for web pages, enhancing the user experience.
- JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false). 
- A script is made up of a series of statements. Each statement is like a step in a recipe. 
- Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value
conditionals statement A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement.
Statements should end with a semicolon. 

- Comments you should always write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. 

- Variable means anything that can vary. JavaScript includes variables which hold the data value and it can be changed anytime. ... A variable must have a unique name. You can assign a value to a variable using equal to (=) operator when you declare it or before using it. Before you can use a variable, you need to announce that you want to use it. This involves creating the variable and giving it a name. Programmers say that you declare the variable. Once you have created a variable, you can tell it what information you would like it to store for you. Programmers say that you assign a value to the variable. Variables are used to temporarily store pieces of information used in the script. 
# Here are six rules you must always follow when giving a variable a name: 
- 1)The name must begin with
a letter, dollar sign ($),or an underscore (_). It must not start with a number. 
- 2)The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name. 
- 3)You cannot use keywords or reserved words. Keywords
are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript. 
- 4)All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases. 
- 5)Use a name that describes the kind of information that the variable stores. For example, firstName might be used to store a person's first name, last Narne for their last name, and age for their age. 
- 6)If your variable name is made
up of more than one word, use a capital letter for the first letter of every word after the first word. For example, firstName rather than firstname (this is referred to as camel case). You can also use an underscore between each word (you cannot use a dash)
- Operators - expressions rely on things called operators; they allow programmers to create a single value from one or more values. 
- Arrays are special types of variables that store more than one piece of related information. 
- Expressions evaluate into a single value. Expressions rely on operators to calculate a value. 


