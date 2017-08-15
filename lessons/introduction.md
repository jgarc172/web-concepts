# Introduction

The approach to these lessons is very different from what you were taught in school, but the lessons assume, and expect, you to apply what you already learned in school.

In other words, the lessons are a good opportunity to review what you already know, to apply all the tools that you already know.  You will realize that there is nothing new in these lessons.  All you will be doing is to apply the knowlege you've gained in your college--and to unleash your creativity and start creating new things that you didn't think you can do.

Part of the approach to teaching and reviewing any concept is to remove unnecessary details.  Words that you will see throughout the lessons will be **simplest**, **minimum**, **necessary**, etc. The simplest examples and problems will allow us to remove unnecessary complexity. 

The lessons will contain 

1. Explanation of a simple concept
2. a description of a problem
3. a solution to the problem
4. a task for you to implement the solution in *software*
5. a test to verify your implementation

# Identifiers, Values, and Representations (interpretation)

In Compuer Science (Actually in all of social life) we need to identify and compare information and the type of such information.  What you learned about memory addresses and memory values is very important in every aspect of your programming activities.  Remember these concepts: 

* identifiers (addresses, names), 
* values (content--simple values to large collections of values), 
* type (interpretation of the content), 
* transfer (copying a value from one location to another).  

Good questions to ask:

* How does my program locate or identify information (value/data)?
* How does my program identify one value in my problem set?
* How does my program identify and distinguish many similar values in my problem set?
* How does my program interpret the type of these values?

# The Simplest Web

The web is based on a network of computer processes, each with its own memory address.  These network nodes communicate by **transferring** information, *data/values*.  That is, values are copied from one location to the other.

The Web was designed with the REST network-architectural style.  HTTP is the first implementation of REST

# The Simplest Network

one network client and one network server.

     Client  -------->  Server

* Only the server needs to be **identified**
* The data in the server needs to be **identified**
* The data is **transferred** by copying the data from the Server to the Client
* **Representation** or type of the data needs to be negotiated (HTML, JSON)
* Interpretation of the data depends on the location of the data

# The Simplest Web Client

* Uses the DNS protocol to **identify** the server using a host name
* Uses the TCP protocol to **connect** to the server
* Uses the HTTP protocol to **identify** and request the **transfer** of data
* Receives the contents of the data and gives it to a specific **interpreter** that can understand the data

# A Necessary Web Client

One that can interpret HTML formatted data (most common Representation).  This is the typical Web Browser.  The web browser uses plugins to interpret other types of data embedded in the HTML page like images, video, sound, etc.

A Browser can request for other types of data representations, like JSON, but your application must know how to interpret the data in the JSON message.

# The simplest server

* Uses the DNS protocol to register its **identifier** as a host name associated to an ip address
* Uses the TCP protocol to accept **connections** from clients
* Uses the HTTP protocol to receive requests, **identify** the data requested, and **return/transfer** the data (response)
* Gives the contents of the request to a specific **handler/interpreter** that can understand the request type and produce the data requested.

# A Necessary Web Server

One that can serve HTML formatted data (most common Representation).  This is the typical Web Server.  The web server uses handlers that can interpret the request and produce the HTML page.

# Lesson 1: HTML documents

In Lesson 1, you will be asked to apply your knowledge to implement, in software, a solution to a problem given to you and related to HTML.
