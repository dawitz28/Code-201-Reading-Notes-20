**Links (HTML / CSS)**
## Writing Links
- Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. You specify which page you want to link to using the href attribute.
- Absolute URLs 
- URL stands for Uniform Resource Locator. Every web page has its own URL. This is the web address that you would type into a browser if you wanted to visit that specific page.
- An absolute URL starts with the domain name for that site, and can be followed by the path to a specific page. If no page is specified, the site will display the homepage.
- Relative URLs
- When linking to other pages within the same site, you can use relative URLs. These are like a shorthand version of absolute URLs because you do not need to specify the domain name
- Mailto:
- To create a link that starts up the user's email program and addresses an email to a specified email address, you use the <a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.
> <a href="mailto:jon@example.org">Email Jon</a>
## LAYOUT (HTML / CSS)
- Normal flow (Position: Static)
- In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be: position: static;
I have not specified a width property for the heading element, so you can see how it stretches the width of the entire browser window by default.
- The paragraphs are restricted to 450 pixels wide. This shows how the elements in normal flow start on a new line even if they do not take up the full width of the browser window.
- Relative Positioning (Position : relative)
- Relative positioning moves an element in relation to where it would have been in normal flow. For example, you can move it 10 pixels lower than it would have been in normal flow or 20% to the right. You can indicate that an element should be relatively positioned using the position property with a value of relative. You then use the offset properties (top or bottom and left or right) to indicate how far to move the element from where it would have been in normal flow.
- To move the box up or down, you can use either the top or bottom properties.
- To move the box horizontally, you can use either the left or right properties.
- The values of the box offset properties are usually given in pixels, percentages or ems.
- Absolute Positioning: Positions the element in relation to its containing element. Absolute elements move as the user scrolls.
- When moving an element that may overlap. The z-index controls which shows on top. 
- Examples in handwritten notebook for visual references
- Screen Sizes: Different users will use different devices so content needs to be designed to fit multiple screen sizes.
- Screen Resolution: Exactly that
- Page Sizes: Standard page size is 960px across because that is viewable on most screens. Height is harder to guess but 570px-600px is when the user will have to scroll.
- Fixed Width Layouts: Fixed with layouts do not move as a user changes their window size. You have more control over the page but may have large gaps and small content if the users screen size or resolution is higher.
- Liquid Layouts: These layouts stretch and squish as the user changes the window size. This is good for larger or smaller viewing devices as the content will stretch or shrink to the size. You lose some layout control and things might not appear as you intend.
# FUNCTION, METHODS & OBJECTS (JS)
- WHAT IS A FUNCTION?
- Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).
- ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS
- Expressions produce a value. They can be used where values are expected. If a function is placed where a browser expects to see an expression, (e.g., as an argument to a function), then it gets treated as an expression.
- FUNCTION DECLARATION
- A function declaration creates a function that you can call later in your code.
- In order to call the function later in your code, you must give it a name, so these are known as named functions. Below, a function called area() is declared, which can then 
- FUNCTION EXPRESSION
- If you put a function where the interpreter would expect to see an expression, then it is treated as an expression, and it is known as a function expression. In function expressions, the name is usually omitted. A function with no name is called an anonymous function. Below, the function is stored in a variable called area. It can be 
# Pair Programming
- Pair programming is the practice of two developers sharing a single workstation to interactively work on a task together.
- The Driver is the one typing
- The Navigator guides the driver with words but never touches the keyboard
- The fundamental skills to learning any a new language are listening, speaking, reading and writing. Paired programming serves to help with all of these.
- 6 Reasons for Pair Programming
- Greater efficiency
- It is a common misconception that pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making.
- Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone. It is harder to procrastinate or get off track when someone else is relying on you to complete the work
- Learning from fellow students
- Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of. If one developer has a unique approach to a specific problem, pair programming exposes the other developer to a new solution.
- Social skills
- Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. This can become more difficult when two programmers have different personalities.
- Job interview readiness
- A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen. They will carry out exercises together, such as code challenges, building a project or feature, or debugging an existing code base. By doing so, companies can get a better feel for how an applicant will fit into the team and their collaboration style.
- Work environment readiness
- Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product. Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.

