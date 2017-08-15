# The Simplest HTML page

## Concepts

The tool we will be using is a web browser.

**web browser**

A web browser, when given a valid HTML document, *renders* the HTML page.

**HTML document**

Based on the fact that the simplest web network requires at a minimum one client (browser) and one server, 
see if you can answer these questions:

1. Where is this HTML document created?
2. How is this HTML document created?
3. Who creates it?

These are actually very difficult questions, and it is very important that you know 
how to answer these, because this is what you will be doing in your real job.

_answers_:

1. In the server
2. HTML pages can be created 

    a. in advance.  These are called Static pages
    
    b. at request time. These are called dynamic pages and are typically associated with the term *web application*
    
3. Based on the type, HTML pages are created by 

    a. static: a frontend developer and a graphics designer
    
    b. dynamic: a frontend developer, a graphics designer, and a backend developer
    
## **Problem or Goal**

We want to render an HTML page that contains no data, to determine the minimum required of an HTML document.

## Available tools

The local filesystem.

This is not the ideal solution, but this is typical of how something can be created in *development* before it
can be deployed in production.

We will not be using a server because we are not ready to setup a server.  One way to "mock" a server is just to create the
HTML document in the local filesystem where the browser is located.  Browsers can "request" a resource (file) from
the filesystem.

_Example of a minimum HTML document_

Here is a reference of a minimal HTML document: https://www.sitepoint.com/a-minimal-html-document-html5-edition/

Actually, the example has a few elements that are not necessary for our task

## A Simple Solution

Using the above reference one can create an HTML document that will render in the browser with no errors and no content.

**identifier**:       The name of the file

**value**:          The contents of the file

**representation or type**: HTML rendering by the browser


## Task and Implementation

Create a file named "simple.html" and save it in your filesystem.  Implement the solution by using your 
favorite text editor and type or paste all the necessary elements.  

If you get an error, see if by removing the element causing the error will fix it.

## Test 
 
Using the browser, **identify** the HTML file to open the file and render it in the browser.  You must see nothing 
in the browser.  Use the Developer tools console in Chrome (Ctrl + Shift + J) to check for any other errors.  Remove the offending element.

You can also use this website to validate the form of your HTML page:
[https://validator.w3.org/#validate_by_input]([https://validator.w3.org/#validate_by_input])
    
## My Solution

my solution is in file [simple.html](https://github.com/jgarc172/web-concepts/blob/master/lessons/01_HTML/simple.html)

## Review

From the perspective of the HTML-renderer, there was no *data* to display because the <body> element was empty.  
But from a higher perspective, that of the browser, we still needed to provide a reference to the HTML file (identifier).  
So let's review some of these concepts:

**identifiers**:  

    file:///C:/data/training/html/simple.html
    this is the identifier of  a file when given to the browser, then evaluated the HTML content and rendered the <body> element
    
    or
    
    https://github.com/jgarc172/web-concepts/blob/master/lessons/01_HTML/simple.html
    this is the identifier of the same file, it contains HTML data but it is not rendered by 
    an HTML renderer.  The contents of the data are rendered (interpreted) as text.
                
**values**:   
    
    <body></body>
    
    or

    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="utf-8">
        <title>Simple HTML</title>
      </head>
      <body>
    
      </body>
    </html>
    
**Representations or types**:   HTML, text


