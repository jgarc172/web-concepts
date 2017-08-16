## My Solution

my solution is in file [simple.html](https://github.com/jgarc172/web-concepts/blob/master/lessons/01_HTML/simple.html)
and it contains an empty `<body>` element:

        <body></body>

## Review

From the perspective of the HTML-renderer, there was no *data* to display because the <body> element was empty.  
But from a higher perspective, that of the browser, we still needed to provide a reference to the HTML file (identifier).  
So let's review some of these concepts:

**identifiers**:  

    file:///C:/data/training/html/simple.html
    
    this is the identifier of a file when given to the browser
    
    or
    
    https://github.com/jgarc172/web-concepts/blob/master/lessons/01_HTML/simple.html
    
    this is the identifier of the same file but located in the github server.
    It contains HTML data but it is not rendered by an HTML renderer.  
    The contents of the data are rendered (interpreted) as text.
                
**values**:   
    
    an empty value inside the body element: <body></body>
    
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
    
**Representations or types**:   

    HTML, text

**transfer**:

    The contents of the file simple.html, the <body> element, was copied to the browser's window
