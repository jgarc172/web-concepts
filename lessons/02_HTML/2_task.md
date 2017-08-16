## **Problem or Goal**

We want to render an HTML page that contains data.

## Available tools

We'll use the local filesystem to create the HTML document.
We'll use simple examples of data, for example, two simple paragraphs of text:

    This is paragraph 1
    
    This is paragraph 2


## A Simple Solution

One can create an HTML document that contains data in the `<body>` element.  The two paragraphs of text are enclosed each in a `<p>` element.


		HTML doc with data ------>  Browser ----> rendered data in HTML
				

**identifier**:       The name of the file

**value**:          The contents of the `<body>` with `<p>` elements

**representation or type**: HTML rendering by the browser


## Task and Implementation

Create a file named "simpleWithData.html" and save it in your filesystem.  Implement the solution by using your 
favorite text editor and create a valid HTML document with the following two text segments rendered as paragraphs.  

    This is paragraph 1
    
    This is paragraph 2


## Test 
 
Using the browser, **identify** the HTML file to open the file and render it in the browser.  You must see the two paragrapsh 
in the browser.  Use the Developer tools console in Chrome (Ctrl + Shift + J) to check for any  errors.  

You can also use this website to validate the form of your HTML page:
[https://validator.w3.org/#validate_by_input]([https://validator.w3.org/#validate_by_input])
    
## My Solution

my solution is in file [simpleWithData.html](https://github.com/jgarc172/web-concepts/blob/master/lessons/02_HTML/simpleWithData.html)

## Review

The identified HTML file is equivalent to the contents of the file.

**identifiers**:  

    file:///C:/data/training/html/simpleWithData.html
    
    this is the identifier of a file when given to the browser.
    
    or
    
    https://github.com/jgarc172/web-concepts/blob/master/lessons/01_HTML/simpleWithData.html
    
    this is the identifier of the same file from a remote server given to the browser. It contains HTML data but it is not rendered by an HTML renderer.  The contents of the data are rendered (interpreted) as text.
                
**values**:   
    
    The contents of the `<body>` with `<p>` elements
    
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
