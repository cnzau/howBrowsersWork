# HOW BROWSERS WORK

## Introduction

### Definition
**What is a Browser?**
A Web Browser or Browser as commonly refered, is a software application installed on a computer for retrieving, presenting, and traversing information resources on the World Wide Web.
An information resource is identified by a Uniform Resource Identifier (URI/URL) and may be a web page, image, video or other piece of content or technology.
Web pages and other resources are interprated by the browser which displays them on the screen.
Some browsers will translate only text while others do support graphics and animation.
Web browsers are not all created equal, and Web pages also will not be displayed the same in different browsers.
The browser operates at the application layer of the Open Systems Interconnection (OSI) model.

The **World Wide Web** is a system of Internet servers that support specially formatted documents. Web browsers are used to make it easy to access the World Wide Web. Browsers are able to display Web pages largely in part to an underlying Web protocol called HyperText Transfer Protocol (HTTP). HTTP defines how messages are formatted and transmitted, and what actions Web servers and browsers should take in response to various commands. It is what allows Web clients and Web servers to communicate with each other. When you enter a Web address (URL) in your browser, this actually sends an HTTP command to the Web server directing it to fetch and transmit the requested Web page and display the information in your browser. All Web servers serving Web sites and pages support the HTTP protocol.

**_Example:_** The URL to reach the definition of browser on Webopedia is: http://www.webopedia.com/browser.html
Once you enter the URL "http://www.webopedia.com/browser.html" into your address line, the browser breaks that Web address down into three distinct parts:

* The Protocol: "http"
* The server name: "www.webopedia.com"
* The file name, which follows the server name: "browser.html"

In order for your browser to actually connect to the Web server to retrieve the information you request, it communicates with a name server to translate the server name into an IP address. Your Web browser is then able to connect to the Web server at the resolved IP address on port 80. Once your browser has connected to the Web server using HTTP, the browser then reads the HyperText Markup Language (HTML), the authoring language used to create documents on the World Wide Web, and the data is then displayed in your Web browser.

## Popular Web Browsers
**_Internet Explorer Web Browser_**

Microsoft's Internet Explorer (IE) is considered the dominant browser though microsoft recently launched a new browser called Microsoft Edge browser. IE and Edge browsers are designed to work on Windows platforms.

**_Chrome_**

Google Chrome browser is developed by google and is based on open source chromium project. It was released in 2008 and is available for Windows, Mac OS X, Linux, Android and iOS operating systems.

**_FireFox Web Browser_**

Firefox browser's code was derived from Mozilla browser.

**_Netscape Browser_**

This was the first commercial Web browser that was once extremely popular. Version 8 is based on code from company spin-off Mozilla, thus borrowwing much of the functionality and format from Firefox.

**_Safari Browser_**

Safari is a Web browser available for the Macintosh and Windows operating systems as well as the iPhone, iPod Touch and iPad. First released in 2003.

#### Others
**_Opera_** developed by opera software the latest version available on the major platforms.

**_Swiftfox_**
Swiftfox is a Web browser for Linux platforms that is based on Mozilla Firefox technology, with builds for both AMD and Intel processors.

**_Konqueror_** runs on Unix-based OS.

**_AOL Explorer_**

**_GreenBrowser_**

**_Lunascape 5_**


## Functions of Browsers
Their main functionality is to present the web resource chosen, by requesting it from the server and displaying it on the browser window.
The resource format is a regularly hypertext markup language (HTML) document, containing PDF, image, flashes or some other type of content in an ordered manner.
The location of the resource is specified by the user using a URI (Uniform Resource Identifier) or URL (Uniform Resource Locator).
The way the browser represents and displays HTML files is specified in the HTML and CSS specifications.
These specifications are managed by the W3C (World Wide Web Consortium) organization, which is the standard organization for the web.
Browsers are not just good at viewing web pages, they can also be used to download and upload files as well.
Browsers can facilitate the file transfer protocol (FTP).
FTPs allow users to upload or download files to web servers using a browser.

## Structure of a Web Browser
A browser is a group of structured codes that performs plenty of tasks to display a webpage on the screen. These codes are separated in to different components according to their tasks performed.

1. **_User Interface_** – It is the space where interaction between users and the browser occurs.Browser user interfaces have a lot in common with each other.
This include : Address bar for inserting a URI, back and forward buttons, bookmarking options, refresh and stop buttons for refreshing or stopping the loading of current file and the home button that takes you to your home page.
2. **_Browser Engine_** – It is a code that communicates the inputs of user interface with the rendering engine.
It is responsible for querying and manipulating the rendering engine according to the inputs from various user interfaces.
3. **_Rendering Engine_** – It is the part responsible for displaying the requested content on the screen.
It first parses the html tags and then using the styles, it builds a render tree and finally a render layout, which displays the content on the screen.
4. **_Networking_** – The fraction of the code written in the browser, responsible to send various network calls.
For example sending the http requests to the server.
5. **_Java Script Interpreter_** – It is the component of the browser written to interpret the java script code presented in a web page.
6. **_UI Backend_** – This draws basic widgets on the browser like combo boxes, windows, etc.
7. **_Data Storage_** – It is small database created on the local drive of the computer where the browser is installed.
This database stores various files like cache, cookies