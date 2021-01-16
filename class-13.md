## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS ##
- persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

- Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:
- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful
## What we really want is ##
- a lot of storage space
- on the client
- that persists beyond a page refresh
- and isn’t transmitted to the server

## A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5 ##
- In the beginning there was only Internet Explorer out of some of the things Microsoft invented one of those things was called DHTML behaviors and one of these behavior was called user data. userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (Trusted domains, such as intranet sites, can store 10 times that amount.

- In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment, the feature is properly known as Local Shared Objects. Briefly, it allows Flash objects to store up to 100 KB of data per domain. In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Brad Neuberg developed an early prototype of a Flash-to-JavaScript bridge called AMASS (AJAX Massive Storage System. In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers. Gears provides an API to an embedded SQL database based on SQLite. After obtaining permission from the user once, Gears can store unlimited amounts of data per domain in SQL database tables. 
INTRODUCING HTML5 ons like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.
## TRACKING CHANGES TO THE HTML5 STORAGE AREA ##

- If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
- The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener (although that will finally be added in IE 9).
## STORAGE ##

- “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.”
## USING HTML5 STORAGE ##
- HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use function. 

git 





 

