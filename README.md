# Data-Collection
Data Collection using APIs




Data Collection
DEMO 1: Data Collection using APIs
Objectives
Learn about APIs
Learn JSON format
Use Google API Books

What is an API?¶
HTML, CSS and javascript create a human-readable webpages.
It is useful to implement applications that can consume the data on these webpages.
You can scrape webpages, but, it’s a tedious task!
So, APIs provide machine-readable data for these software, mainly in the form of JSON responses (we will shortly learn more about JSON files).
Companies such as Google, Twitter, Facebook, and Tumblr provide access to their data for software developers via their APIs
API stands for Application Programming Interfaces, many website provide their data through the API so they can control how and when their data is being used. 
How an API works?
Simply, you send requests to a remote server and the remote server respond by sending the data back to you.
Then, what we need is to:
1) Establish our connection to the server 
2) Send requests
3) Receive responses 
4) Manipulate responses

 Using Requests Library¶

Requests is a simple Python HTTP library. It provides methods for accessing Web resources via HTTP. Requests allows you to send HTTP/1.1 requests, without the need for a lot of work. It is avialble within Anaconda

Lets try something real!
We will use Google Books APIs
https://developers.google.com/books/
You can find the reference and other examples here: https://developers.google.com/books/docs/v1/reference/

Copy and paste the following URL in a browser:
https://www.googleapis.com/books/v1/volumes?q=isbn:1860462979
What can you see?

Google books API send requests to get information about books using their isbn.
While opening the URL in a browser, the browser sends the HTTP request to get the information from the API. The response is what you saw in the browser. 
But what is that format?

Yes! That is a JSON response!
Let us investigate it!

JSON (JavaScript Object Notation) a lightweight data-interchange format. JSON is easy for humans to read and write and is easy for machines to parse and generate.
More info at: http://json.org
Tutorial at: http://www.w3schools.com/json/ 

