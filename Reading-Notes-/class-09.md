Form structure
<form> - Form controls live inside a <form> element. This element should always carry the action attribute and will usually have a method and id attribute too.
Action - Every <form> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.
Method - Forms can be sent using one of two methods: get or post.
Id - the value is used to identify the form distinctly from other elements on the page (and is often used by scripts — such as those that check you have entered information into fields that require values).
Text input
<input> - The <input> element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.
type="text" - When the type attribute has a value of text, it creates a single- line text input.
Name - When users enter information into a form, the server needs to know which form control each piece of data was entered into. (For example, in a login form, the server needs to know what has been entered as the username and what has been given as the password.) Therefore, each form control requires a name attribute. The value of this attribute identifies the form control and is sent along with the information they enter to the server.
Maxlength - You can use the maxlength attribute to limit the number of characters a user may enter into the text field. Its value is the number of characters they may enter. For example, if you were asking for a year, the maxlength attribute could have a value of 4.
Size - The size attribute should not be used on new forms. It was used in older forms to indicate the width of the text input (measured by the number of characters that would be seen).
Password input
<input type="password" - When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. They are hidden in this way so that if someone is looking over the user's shoulder, they cannot see sensitive data such as passwords.
Name - The name attribute indicates the name of the password input, which is sent to the server with the password the user enters.
size, maxlength - It can also carry the size and maxlength attributes like the the single-line text input. Although the password is hidden on the screen, this does not mean that the data in a password control is sent securely to the server. You should never use these for sending sensitive data such as credit card numbers. For full security, the server needs to be set up to communicate with users' browsers using Secure Sockets Layer (SSL). The topic of SSL is beyond the scope of this book, however there are links to learn more about it on the accompanying website.
LISTS, TABLES AND FORMS
Bullet point styles (list-style-type)
The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker).
It can be used on rules that apply to the
For an unordered list you can use the following values:
o	none
o	disc
o	circle
o	square
For an ordered (numbered) list you can use the following values:
o	decimal : 1 2 3
o	decimal-leading-zero: 01 02 03
o	lower-alpha : a b c
o	upper-alpha: A B C
o	lower-roman: i. ii. iii.
o	upper-roman: I II III
(list-style-image)
You can specify an image to act as a bullet point using the list-style-image property.
The value starts with the letters url and is followed by a pair of parentheses. Inside the parentheses, the path to the image is given inside double quotes.
This property can be used on rules that apply to the <ul> and <li> elements.
The example on this page also shows the use of the margin property to increase the vertical gap between each item in the list.
EVENTS (JS)
TRADITIONAL DOM EVENT HANDLERS
All modern browsers understand this way of creating an event handler, but you can only attach one function to each event handler.
Here is the syntax to bind an event to an element using an event handler, and to indicate which function should execute when that event fires:
Below, the event handler is on the last line (after the function has been defined and the DOM element node(s) selected).
When a function is called, the parentheses that follow its name tell the JavaScript interpreter to "run this code now."
We don't want the code to run until the event fires, so the parentheses are omitted from the event handler on the last line.
USING DOM EVENT HANDLERS
In this example, the event handler appears on the last line of the JavaScript. Before the DOM event handler, two things are put in place:
-	If you use a named function when the event fires on your chosen DOM node, write that function first. (You could also use an anonymous function.)
-	The DOM element node is stored in a variable. 
