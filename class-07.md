# Domain Modeling

 This is the process of creating conceptual model in code for a specific problem. A domain model if made well can verify and validate the understanding of a specific problem among various stakeholders. Also, an entity that stores data in properties and encapsulates behaviors in methods is known as an object-oriented model.

 To build your own domain model:

   - When you model a single entity that will have many instances, you need to build a self-contained objects with the same attributes and behaviors.
   - Model the attributes with a constructor function that will define and initialize properties.
   - It will model it's behaviors with small methods that will focus on doing one job very well.
   - Will create instances using the *new* keyword followed by the call to a constructor function.
   - It will store the newly created object in a variable so you can access the properties and methods of it on the outside.
   - Use the *this* variable inside methods so you can access the object's properties and methods on the outdies of it.

   ## Tables

   A table represeants information in a grid format.

   To create a table you must use these tags:
    - < table >: used to create the table within HTML and are written out row by row
    - < tr >: this is used to indicate the start of each row. stands for *table row*
    - < td >: this is used to represent the cell of each table. stands for *table data*
    - < th >: this is used to represent the heading for each column or row. stands for *table heading*

In order to span the columns (or stretch across more than one column) you use the attribute called colspan.
In order to span rows (or stretch down across more than one row) you would use the attribute called rowspan.

To create long tables you have to use three different elements that help distinguish between the first and last rows and the main content. (these elements help those with screen readers):
 - < thead >: heading of the table is placed here
 - < tbody >: the body of the table should sit in this element
 - < tfoot >: the footer belongs in this element




# Functions, Methods, and Objects

Functions allow you to group related statements together that represent a single task.
They also take in perameters(these hold info that is required to do it's job) and return a value.

An object is something that can be used to represent the world around you and still be written in a series of variables and functions.

Web-browsers will use these *objects* to represent the browser window and the document showing on the browser window.

JAvaScript has built in objects such as:
 - Strings
 - Numbers
 - Math
 - Date

These properties help to write scripts with their properties and methods offering functionality.
Also, arrays and objects can be used to create complex data sets.

[<===Back](README.md)
