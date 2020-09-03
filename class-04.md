## HTML links, CSS layouts, and Javacript functions

# HTML and CSS

**Links**
 
Links can be used to create links between pages like;
 - Other pages within your web page
 - CSS pages to bring the CSS to the HTML page
 - JavaScript pages to bring the JavaScript to the HTML

Links can also be incorporated into your HTML to link you to articles, other webpages, images, or email links outside of your webpage.

To create a link withing your HTML you need to use an < a > element. This shows up to the user as a text that they can click on to take them to the page. To specify which page the user is going into you need to use the href attribute within the element.

For larger webpages it is always good to organize your code by placing the pages for each different section of the site into a new folder. These are refered to as a Directory.
If you want to link a page within your own sit you must use one of the *relative* links rather than *qualified* URLs.

 **Relative link types**
  - Same Folder: to link files within the same folder
  - Child Folder: use the name of the child folder, followed by a forward slash, then the file name
  - Grandchild Folder: Use the name of the child folder, followed by the forward slash, then use the name of the grandchild folder, followed by *another* forawrd slash, then the file name
  - Parent Folder: use the ../ to indicate the folder above the curent one and then follow with the file name
  - Grandparent Folder: Repeat the ../ to show that you want to go up 2 folders, then follow it with a file name.

These are shorthand ways to tell the browser where a page is in relation to the current page.

To create a link that starts up the user's email and addresses an email to a specified email address you would use the same < a > element, but this time the value of the href attribute starts with mailto: and then you follow up with the email address you want an email to be sent to. To open links into a new window you can use what is called the target attribute on the opening < a > tag and the value of this should be _blank.
linking to a specific part of the same page and linking to a specific part of another page
  - to the same page: You need to identify the points in the page that the link will go to and to do this you need to use the id attribute and the value of this attribute should start with a letter or an underscore and not a number or anyother character.(also no two attributes should have the same value...)
  - to another page: You use the similar technique as before  as long as the page you link to has id attributes that identify spesific parts of a page you can add the same syntax to the end of that link.

**Layout**

The layout is controlling the position of elements, creating size layouts, and designing for different sized screens.

- Positioning the elements
 - CSS treats each HTML element as if it were it's own box. This will either be a block level element or and inline element.
  - Block-level elements: start on a new line
  - Inline elements: flow in between surrounding text

Containing the elements
 - If one block-level element sits inside another block-level element then the outer box is called the containing or *parent* element.

 To control the position of elements CSS has to follow positioning schemes. These *schemes* allow you to control the layout of the page:
  - Normal Flow: every block-level element appears on a new line.
  - Relative Positioning: moves an element from its normal position and shifts it right bottom or left, to the top, of where it would have been placed. 
  - Absolute Positioning: positions the element in relation to its containing element
  - Fixed Positioning: positions the element in relation to the browser window
  - Floating Elements: allows you to take the element out of normal flow and position it to the far left or right of a containing box.

< div > elements are often times used as containing elements to group together sections of page. 
*(note: developers normally keep their pages within 960-1000 pixels wide and they let you know what the site is about within the top 600 pixels)*
Also, the use of a grid can be helpful. They create a more professional design as well as a more flexible one.

You can add multiple CSS files in one page.
 - You can split up the style rules into seperate style sheets by adding a link to one style sheet and adding anothers by using @import.
 - You can also split style sheets by using the link element, but you will be adding link after link after link.




# JavaScript

**Functions, Methods, and Objects**

 A function lets you group a series of statements together to make a specific task. You can reuse the function if different parts of the script repeat the same task (this helps so you don't have to sit and repeat the same task).

 To make a function you have to give it a name and write the statements to achieve the task inside of curly braces. This is what's called *declaring the function* Once you declare it then you can *call the function*(or execute the statements in the curly braces). Functions will somtimes need specific information to preform its task. This is when you give it what's called a *parameter*. The parameter acts like a variable. When you call this function with the parameter you specify the values it uses within the parentheses after its name. These values are called arguments and they can be given as values or variables.

  - Single value out of a function is returning information to the code that called them (like a calculator)
  - Multiple values out of a function is returning multiple values using an array
  - Function Declaration: creates a function that can be used later in the code.
  - Function Expression: putting a function where the interpreter would see an expression and it then becomes an expression (or treated like one)
  - Immediatly Invoked Function Expressions: (the "iffy") they aren't givin a name and they are only executed when an interpreter comes across them.

When to use anonymous functions and IFFEs: 
 - As an argument when a function is called
 - to assign the value of a property to an object
 - In event handlers and listeners...
 - to prevent conflicts between two scripts that may use the same variable names...

Variable scope: once you declare a variable within a function it can only be used within that function.
 - Local Variables: creating a variable inside the function. (can only be used inside that function)
 - Global variables: creating a variable outside of a function. (can be used anywhere inside the script)

Global variables use more memory and the browser has to remember them for as long as the web page that has them is loaded and local variable are only remembered for a short period of time when the function is executed. Each variable that is declared takes memory and the more variables the browser has to use the more momory the script takes to run. (this can make your browser sloooow)
Name collisions can happen, this is when two JavaScript files within one HTML page both have global variables with the same name.


# 6 Reasons for Pair Programming

Pair Programming works by having a Driver and a Navigator.
- Driver: the person who is typing and the only one with their hands on the keyboard
- Navigator: vocally guides the Driver, but doesn't actually type anything on the computer. 

The Navigator will think about the big picture and how things are converted to code and will also look out for any mistakes.
The Driver will handle just the mechanics of it all.

Why pair proggram? Well, there is the *greater efficiency* which allows the programmers to catch mistakes and they can come up with solutions faster than on their own. This also helps when one or both programmers are stuck they can both research to find the solution. even though the work takes longer it is better off this way to improve technical skills, team communication, and even enjoyability of coding in the workplace. Also, when two programmers are working on the same code, it can be more *engaging* and both programmers are more focused than if they were working alone.(can't check social media while someone is working with you). You can also *learn from your partner*. One person may have one way to approach a situation that the other didn't even think of and vise versa. Working together with someone with a different personality can be hard, but at the same time when you can partner with someone for a project this can still help your *social skills*. This also helps when looking for a programming job. When someone wants to hire you, you have to get along with others. Pair programming can get you ready for your *interview* and the *work environment*. Working together os one thing, you can get along with others, but being able to deliver a product is another. Jobs want to see how well an applicant will fit in with a team and how well their collaboration skills can be. anyone who is familiar with pair programming is ready and willing to get that job they dream for and with the ability to work with someone on debugging an existing code base, building a product feature, or just doing an excercise together will get them hired in no time.

[<== Back](README.md)
