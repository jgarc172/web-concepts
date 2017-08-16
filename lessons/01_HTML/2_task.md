## **Problem or Goal**

We want to render an HTML page that contains no data, to determine the minimum required of an HTML document.

## Available tools

Since HTML pages are created in the server and we are not ready to setup a server.  We'll use the local filesystem.

This is not the ideal solution, but this is typical of how something can be created in *development* before it
can be deployed in production.

One way to "mock" a server is just to create the HTML document in the local filesystem where the browser is located.  Browsers can "request" a resource (file) from the filesystem.

_Example of a minimum HTML document_:

Here is a reference of a minimal HTML document: https://www.sitepoint.com/a-minimal-html-document-html5-edition/

Actually, the example has a few elements that are not necessary for our task

## A Simple Solution

Using the above reference one can create an HTML document that will render in the browser with no errors and no content.


				HTML doc ------>  Browser ----> rendered HTML
				

**identifier**:       The name of the file

**value**:          The contents of the file

**representation or type**: HTML rendering by the browser


## Task and Implementation

Create a file named "simple.html" and save it in your filesystem.  Implement the solution by using your 
favorite text editor and type or paste all the necessary elements.  

If you get an error in the browser or validation tool, see if by removing the element causing the error will fix it.

## Test 
 
Using the browser, **identify** the HTML file to open the file and render it in the browser.  You must see nothing 
in the browser.  Use the Developer tools console in Chrome (Ctrl + Shift + J) to check for any other errors.  Remove the offending element.

You can also use this website to validate the form of your HTML page:
[https://validator.w3.org/#validate_by_input]([https://validator.w3.org/#validate_by_input])
    

