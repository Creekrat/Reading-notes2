# Js Objects literals; The DOM

 ## Object Literals
  
  Objects group together as a set of variables and functions to create a model of somthing you would see in the real world. In an object, these variables and functions use new names.

  Literal notation is the easier way and the most common way to create objects. To create objects you would use Dot Notation or square brackets. 

  ## Document Object Model

   The DOM tree is a model of a webpage....

   As a browser loads a page, it will create a model of that page. This model is called a DOM tree.
   The DOM trees have 4 types of nodes:
    - document nodes
    - element nodes
    - attribute nodes
    - text nodes

You can pick element nodes by their ID or Class attributes, by their tag name, or using the CSS syntax...

If a DOM query can return more than one node then is will return a NodeList.

From and element node, you can get and update the content using the properties like textContent and innerHTML or using the DOM manipulation techniques.
An element node can contain multiple text nodes and child elements that are siblings. The DOM implementation is inconsitent in older browsers. (pretty much why JQuery is used) and some browsers offer tools to view the DOM tree.