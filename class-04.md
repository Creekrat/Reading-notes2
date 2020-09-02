## HTML links, CSS layouts, and Javacript functions

**HTML and CSS**

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

These are shorthand ways to tell the browser where a page is
