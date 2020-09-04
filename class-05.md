# HTML images, CSS color and text.

 **Images**

 When you choose images for your webpage you must remember the following things:
 - they must be relevent
 - convey information
 - convey the right mood
 - be instantly recognizable
 - fit the color pallet of your webpage

All images are subject to copyright, and you can get into a lot of trouble for taking photos from other places.
To store your images you need to create a folder specifically for your images for your page,but for a bigger site you might want to use subfolders inside this image folder to carry images with common themes.

To add an image you need to use the < img > element:
 - use src to tell the browser where to find the image by adding the url
 - use alt to give a brief description of the image just in case it doesn't show or for the vision impaired when they use a screen reader
 - use title to provide addition info about the image and browsers normally use this in a tootip when someone hovers over the image.
 - you can adjust the height and width of an image by typing in a pixel amount for either withing the < img > element.

There are three rules to creating images:
 - save them in the right format
 - save images at the right size
 - measure images in pixels.

You can use a number of different tools to edit and save images, but the most popular has to be Adobe Photoshop.

Image formats:
 - jpeg: when you have many different colors in a picture
 - gif or png: when you save pictures with less color or larger areas of the same color

Images you use should be saved as the same width and height that you want them to be on your page.
When you crop an image try not to lose valuable info (tip: try to source images that are the correct shape...)
When you want to size an imageto use on a screen you should always set the dimensions of the image in pixels.
 - pixels are what images are made up of (teeny tiny squares all put together)
 - resolution of a screen is the number of pixels represented on it. 

Vector images are resolution-independent. These are mostly created in Adobe Illustrator as a line drawing; much like logos, illustrations, or diagrams. 

Animated gifs show many frames of an image in a sequence so it can be used to create simple animations..

In order to create tranparency in an image you must do it with one of two formats:
- Transparent Gif: if the transparent part of an image has edges and is completly transparent you can save it as a GIF (with a transparency option selected.)
- Png: if the transparent image has diagonal or rounded edges or just a semi-transparency or a shadow then you need to save it as a png.



**Color**

Color can convey the mood and evoke reactions on a webpage. There are three different types to specify colors in CSS:
 - RGB values
 - hex codes
 - and just the color names themselves..

If you have a hard time choosing a color try using a *color picker* these help you find what color you need for the webpage.

When using a background color you need to make sure that there is enough contrast between any text and the background color or people aren't gonna be able to read your content....

There is a new CSS language called CSS3 and this has created extra values like:
 - RGBA: indicates opacity
 - HSLA: allows you to specify colors with an optional opacity value.

**Text**
(no..not a phone option)
(not unlimited either...)

There are properties to control the font, size, weight, style, and spacing of the text on a page.
You can choose from a number of different fonts, yet you have to install them to be able to incorpoate them into your CSS(bummer). To use a wider range of typefaces there are several options, but you have to have the right licenses to use them...(i know..another smack in the face..).

You can control the space in between lines of text, individual letters, and words by using:
 - line-height
 - letter-spacing
 - word-spacing

You can also align text:
 - to the left
 - to the right
 - center
 - or justified: indicates every line in a paragraph except the last one should take up the full width of the box it is in.
 - or indented


You can also use what's called  pseudo-classes to change the style of an element when someon hovers over or clicks on text, or when they have visited a link:
 - :hover-when someone hovers over an element with their mouse. This can change the look of buttons or links
 - :active-when an element is being activated by a user
 - :focus-any element you can interact with

Attributes for CSS:
 - Existence: matches a specific attribute
 - Equality: matches a specific attribute with a specific value
 - Space: matches a specific attribute whose value appears in a list of words that have been seperated by a space
 - Prefix: matches a specific attribute whose value begins with a string
 - Substring: matches a specific attribute that contains a substring
 - Suffix: matches a specific attribute with a value that ends with a string.

 [<==Back](README.md)
