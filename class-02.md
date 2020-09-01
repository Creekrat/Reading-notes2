## Reading: Basics of HTML,CSS & JS

**Text**
 
 The text on a webpage is made up of HTML tags that the computer can easily understand.
 You can use these tags to create:
 - Headings
 - Paragraphs
 - Bold, Italic, or emphasis in words on a page
 - Structural and semantic markup (or tags themselves)

The tags provide extra meaning and show users the structure for the page.
The types of tags used can be:
 - < h1 > thru < h6 > for the heading. h1 tags are used for the main heading and is only used once and the h2 thru h6 tags are used as subheadings throughout the page.
 - < p > is used for the paragraph on the page. By default, a browser normally shows a new paragraph on a new line, yet line breaks < br > are sometimes necessary for making the paragraph look neat.
 - < b > is used for bold characters
 - < i > is used for italic characters
 - < sup > is used for to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising numbers to a certain power.
 - < sub > contains elements that should be subscript. COmmonly used with the foot notes or chemical formulas such as H2O.

white space is used to make code easier to read. Authors often add extra spaces or start elements on new lines.
When the browser comes across two or more spaces next to eachother, it only displays one space. When it comes across a line break it still treats it as a regular space. These white space collapsing can be used to indent code to make it easier to follow.

If you wanted line breaks inside the paragraph tag you have to use the tag < br > and to create breaks between themes you need to use the tag < hr >.
Content management systems and HTML editors like Dreamweaver usually have two views if the page you are creating:
 - A visual editor: ressemble word processors
 - A code view: shows the code created by the visual code editor so you can manually edit it.

Some text elements that are not intended to affect the structure of webpages, but they do add extra info to the pages. This is known as *Semantic Markup.*
In order to emphasis or show that the text is improtant you need to use these tags:
 - < strong > is used to show that the text is of strong importance.
 - < em > is used to emphasis text and it subtly changes the meaning of the sentence.

There are two tags used for marking up quotations:
 - < blockquote > is used for longer quotes that takes up an entire paragraph. You have to put this tag in between the paragraph tags.
 - < q > is used forshorter quotes that sit within a paragraph. Now this is not used often because browsers are supposed to put quotes around the < q > element and internet explorer does not do this.

Now abbreviations and acronyms are used with this tag: < abbr >
Citations and definations use thes tags:
 - < cite > used for when you reference a piece of work such as a book,film, or research paper. HTML5 cannot be used for a person's name, but it was allowed in HTML4.
 - < dfn > is used for defining instance of a new term.

< address > is used to contain contact details for the author or developer of a page.

In order to make changes to content you have to use these tags:
 - < ins > is used to show content that has been inserted into a document. (would usually have a line under it)
 - < del > is used to show text that has been deleted from a document. (would usually have a line through it)
 - < s > is used to indicate something that is no longer accurate or relevent.

HTML elements are used to desribe the structure of a page they also provide semantic info.

**Introducing CSS**

CSS allows you to create rules that control the way your diplay looks on a webpage. In order to create CSS you can either incorporate it into HTML or you can put it into another link and connect it to your HTML. A CSS rule contains two parts:
 - Selector: indicate which element the rules apply to and if you seperate the elements names with commas you can apply the same rules to more than one element.
 - Declarations: indicate how the elements referred to in the selector should be styled and Declarations are split into two parts and seperated by a colon. They are split into a property and a value. You can specify several properties in one declaration, each seperated by a semi-colon.

You can use either External CSS or Internal CSS to decorate your page.
 - External CSS uses link tags in an HTML document to tell the browser where to find the CSS
 - Internal CSS uses elements within HTML

CSS Selectors allow you to target rules within an HTML document. These rules are made up of selectors and declarations. These are the selectors:
 - Universal selector: applies to all elements
 - Type selector: matches element names
 - Class selector: matches an element whose class attribute has a value that matches the one specified after the period symbol
 - ID selector: matches an element whose id attribute has a value the one specified after the pound or hash symbol
 - Child selector: matches an element that is a direct child of another
 - Descendant selector: matches an element that is a descendant of another specified element
 - Adjacent Sibling selector: matches an element that the next sibling of another
 - General Sibling selector: matches an element that is a sibling of another, although it doesn't have to be the directly preceding element.

CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how the element should look. 

## JavaScript

**Basic instructions for JS**

A script is a series of instructions that a computer can follow one-by-one (DETAIL BY DETAIL!!!)
Each instruction or step is known as a statement and they should all end with a semi-colon. You need to write comments in your JS to explain what your code does. This helps your code to be easier to read and understand and it helps you and others while reading your code.

A script needs to temporarily store bits of info in things called variables. Variables are places to hold information that can vary(or change) each time a script is run.
Each script contains very very *VERY PRECISE* instructions. Arrays are special types of variables that stores one or more pieces of related information.

There are types of scripts:
 - numbers
 - boolean(true or false)
 - strings(text)

Expression rely on operators to calculate a value:
- Assignment- assign a value to a variable
- Arithmetic- perform basic math(duuuuhhh)
- String- you can combine different strings
- Comparison- ((operand+operand)>(operand+operand))combine two values and return true or false
- Logical-( logical and && )combine expressions and return true or false

**Decisions and Loops**

There are often several places in a script where decisions are made to determine which lines of code runs next. You need to use a flowchart to make it easierto plan for that. There are two components to a decision:
 - expressions that are evaluated, return a value
 - a conditional statement says what to do at a given time

 Comparison Operators: Used to compare two operands
 - ===
 - !==
 - ==
 - !=
 - <
 - (  > )
 - <=
 - =>

Local Operators allow you to combine more than one of these comparison operators
If...Else statements let you run one set of code if the condition is is true and the other if it is false.


