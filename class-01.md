# Reading Notes
**HTML and CSS**

How do people access the web?

Well people can access it in many ways. People use things like:
 - Browsers- A software used to access websites.
 - Web Servers- These host the websites
 - Devices- You can access websites through many devices like; Computers,Phones,and Tablets.
 - Screen Readers- These are programs that read out the contents of a computer screen to a user. Commonly used by the visual impaired.

Any website is created by using the basics:
 - HTML- The *bones* of a webpage
 - CSS- The *decor* of a webpage
 - JavaScript- The *interactive* parts of a webpage

When you open a webpage the majority of what you see is HTML and CSS. These are the coding languages used to create the visual aspect of a webpage.
HTML and CSS have improved over the years and have updated to HTML5 and CSS3. These versions build off of older languages so learning these previous versions help in developing new ones.

 - When using the web, the web server hosting any site can be anywhere in the world. To find the location of the web server, the web browser will first connect to a Domain Name System server. When you connect to the web you do so by connecting to whats called a Internet Service Provider. You type in the domain name or web address to visit a site.
 - Your computer contacts a network of servers (DNS) and they act like a phone book to tell your computer the IP address associated with the requested domain name. *every device on the web has a unique IP address* (like a telephone number for your computer)
 - The unique number that your DNS server returns to your computer allows the browser to contact the web server that hosts the website you requested. The web server then sends the page you requested back to your web browser.

**Structure**

Web pages use structure to help readers to understand what goes on in a web page.
HTML uses elements to describe the structure of pages. Each element has an opening and closing tag. 
These tags are used to structure the webpage piece by piece:
 - head
 - body
 - header
 - paragraph

*almost like writing a structured essay*

Tags are made by using the left and right angle brackets with a character in between. To close the tags you use the left and right angle brackets and a forward slash:
 - < p > < /p  >
Everything in between these tags is what you see in a web page.

These tags are giving information to the computer.
Now some tags have *attributes*. They provide additonal information about the contents of an element. The attributes are made up of parts like a name and a value that are seperated by an equals sign.

here are the main tags for the structure of a page:
 - Body: everything shown on the page goes inside of the body tags.
 - Head: before the body element you create a head tag. This contains the information about the page and doesn't show up on the webpage itself. This usually contains the title tag.
 - Title: The contents of the title element are either shown in the top of the browser or above where you type your URL of a page.

So to learn HTML you need to know what tags to use, what they do, and where they go.


**Extra Markup**

So before there was HTML5 there were two other versions of HTML. HTML4 (released in 1997) and XHTML1.0 (released in 2000)
There are many simularities between HTML4 and HTML5, but what has changed is presentational elements to control the appearence of a page. Developers are not recommended to use them anymore.

 - HTML4: elements like center, font, and strike were achieved with this language , but have been since been taken out due to the new HTML5 language and these tags can now be achieved through CSS because they are used for the decoration of the page.
 - XHTML 1.0: In 1998, the language XML was published and it's purpose was to allow people to write new markup languages. HTML was the most widely used markup language around, it was decided that HTML 4 should be reformulated to follow the rules of XMl and it was renamed XHTML. People had to start following some new, more strict rules like every element needs a closing tag, attribute names have to be lowercase, all attributes required a value and all values were to be placed in double quotes, deprecated elements should no longer be used,and every element that was opened inside another element should be closed inside that same element.
 - HTML5: People do not have to close all tags and new elements and attributes are introduced. It is more of a laid back.

Because there are different versions of HTML, each webpage should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using. You can also display comments in your HTML that doesn't show up on your web page so you can keep track of what you are doing. The characters you use are this: < !-- -- > 

HTML can use ID attributes to uniquely identify one element from other elements on the page. HTML can also use class attributes to identify several elements as being different from the other elements on the page.

Some elements will always appear to start on a new line in the browser window and those are known as block level elements. Also some elements will always appear to continue on the same line as neighboring elements and those are called inline elements. When you want to group text and elements into a block you use a < Div > tag and when you want to group text and elements in inline you use the < Span > tag. < iframe > tags cut windows into your web page where other web pages can be displayed. The < meta > tag allows you to supply all kinds of information about your web page. Escape characters are used to include special characters in your page.

**HTML5 Layout**

Traditional layout:
 - you can use < div > elements to group together related elements on the page (the elements that form a header, article, footer, or sidebar). People use class or id attributes to indicate the role of a < div > element in the structure of a page.

New HTML5 layout:
 - It introduces a new set of elements that allow you to divide up the parts of the page. The names of the elements indicate the kind of content you find in them. Easier to understand.

HTML5 has tags like header, footer, nav, article, aside, section, hgroup, figures, figcaption, and sometimes div.

 - < header > and < footer > tags are used for the main header or footer that appears at the top or the bottom of every page on the site. a < header > and < footer > can also be used for an individual < article > or < section > within the page.
 - a < nav > tag is used to contain the major navigational blocks on the site.
 - an < article > tag acts as a container for any section of a page that could stand alone and be syndicated.
 - an < aside > tag has two purposes (this depends on whether or not it is inside of an < article > tag). When inside the < article > tag it should include information that is related to the article, but not necessarily to it's overall meaning. When outside of the < article > tag it acts as a container for content that is related to the entire page.
 - a < section > tag groups related content together, and every section would normally have it's own heading.
 - a < hgroup > tag groups together a set of one or more < h1 > through < h6 > tags so they are treated as one single heading.
 - < figure > and < figcaption > tags are used for images on a page and the description of images on a page just in case the image isn't there. The description of the image is mostly used for if the image doesn't show up or  for the vision impaired so it can be read out to them.
 - < div > tags are rarely needed in HTML5 but is still used to group together elements.

Older browsers that don't understand HTML5 elements need to be told which elements are block-level elements. To make HTML5 elements to work in Internet Explorer or older versions of it then extra JavaScript is needed.

**Process and Design**

You need to understand who the target audience is, why they come to your site, what information they want to find or see and will they come back to your site. You need to use site maps to plan the structure of your website and use wireframes to organize the information for each page. Design is all about communication. Using visuals helps your visitors understand what you are trying to tell them. You can use size, color, and style to differentiate between pieces of information and you can use grouping and similarity to simplify the information you have.



**JavaScript**

 - A: *What is script and how do i use it?*
 A script is a set of step by step instructions (*IN DEEP DETAIL!*) that a computer can follow to achieve a goal. Everytime the script runs it may only use a subset of all the instructions. When writing a script break the goal down into a series of tasks and then work out each step needed to complete that task.
 - B: *How do computers fit in with the world around them?*
 Computers create models of the world using data. These models use objects to represent physical things. Programmers can write code that is easy to understand and easy to follow such as; " when this happens run this." To make web pages interactive, you write code that uses the browser's model of the webpage. Objects can have: properties that tell you about that object; methods that perform tasks using the properties of that object; events that happen after they are triggered by an interaction on the computer.
 - C: *How do I write a script for a webpage?*
 You need to keep JavaScript code in it's own file. They are text files and they use the .js extention to tell the difference between your CSS and HTML files. In HTML  you would use the < script > tag to link the JavaScript file to your main page and it helps the browser to load the file. Also, if you look at the source code for your page you can see that the JavaScript will not have changed the HTML, because the script works with the model of the web that the browser created.

JavaScript makes a webpage more interactive. It allows you to make webpages interactive by accessing and modifying content and the markup used in a webpage while it was used in the browser.

[<==Back](README.md)