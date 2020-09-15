# Local Storage

Persistant local storage is one of the areas where native client applications have held an advantage over web applications. The operating system provides and abstraction layer for storing and recieveing application data like preferences or runtime state for native applications. According to the platform convention those values can be stored in the registry, INI files, XML files, or other places. You can embed your own database, invent your own file format, or any other solutions if your client app needs local storage beyond key/value pairs.

Before, web apps didn't used to have these luxuries and this is when Cookies were brought to light in the early web history. They could be used for local storage, yet only for small amounts and it had it's downsides:

 - With every HTTP request, your web application is slowed down due to needlessly transmitting the same data over and over and over again with Cookies.
 - Data can be sent unencrypted over the internet due to Cookies in the HTTP request
 - Cookies only are limited to about 4KB of data that is enough to slow down your app, but it's not very useful.

What we strive for is:

 - lots of storage space on the client that goes on after a page refreshes and isn't going to be transmitted to the server.

Before HTML5 there was userData. This allowed web pages to store up to 64 KB of data per domain, in hierarchical XML-based structure. In 2002 Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of "flash cookies" this is also known as Local Shared Objects and this briefly allows Flash objects to store up to 100KB of data per domain. There was an early prototype of a Flash-to-JavaScript bridge called AMASS (AJAX Massive Storage System) invented by Brad Neuberg, yet it was limited by some of Flash's design quirks. Brad rewrote AMASS and changed it into the Dojo Toolkit under the moniker dojox.storage. each domain is given 100KB of storage *"for free"* and beyond that it will prompt the user for each order of magnitude increase in data storage(rip off...).

After obtaining permission from the user only once, an open source browser plugin called, Gears, can atore unlimited amounts of data per domain in SQL database tables. Gears was created by Google in 2007 and it provided additional capabilities in browsers.

Each one of the "solutions" has a pattern:
 - they are specific to a single browser or reliant on a thrid party
 - they expose radically different interfaces
 - they have different storage limitations
 - they present different user experiences

So HTML5 provized a solution to the problem:
 - To provide a standardized API that can be implemented natively and consistently in multiple browsers and it didn't have to rely on third party plugins..



 # HTML5 Storage

 This is just a way to store named key/value pairs locally, within a clients web browser. The data persists even after a user navigates away form the site (much like cookies). This data is never transmitted to the remote web server like the cookies though, but there are ways to do it manually. 

 The latest versions of any web browser now supports HTML5 storage like:
  - IE
  - Firefox
  - Safari
  - Chrome
  - Opera
  - Iphone
  - Android
  - exc..


You can access HTML5 Storage through the JavaScript in the localStorage object on the global window object.HTML5 is based on named key/value pairs and you can store data based on a named key, then retrieve the data with the same key.If you want to keep track of when the storage area has changed you can use a storage event like:
 - setItem()
 - removeItem()
 - clear()

There are some limitations in current browsers like "5 megabytes" is how much storage space each origin is given bydefault and "QUOTA_EXCEEDED_ERR" is what is thrown at you if you exceed the storage quota of 5 megabytes. With HTML5storage you can save a game on screen while previously if you exited a browser window with the game you would loseall progress. The HTML5 storage save progress locally within a browser itself.

[<==Back](README.md)

