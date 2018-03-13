## Project Name:  Seminole Movie Connection Application using TMDB API

### Course Title:
LIS 2360:  Web Application Development

### Assignment Date:  
March 11, 2018

### Student Name:  
Jiri Stanc

### Project Description:
The purpose of this assignment is to build an AJAX/JSON based movie database application. The data for the application are retrieved from movie database (TMDb) using API.

### View Project:
https://jirist.github.io/lesson8_ajax/

### Lessons Learned in the Assignment:
1. #### AJAX (Asynchronous JavaScript and XML)

AJAX is a programming approach using existing technologies to allow parts of DOM of a webpage to be selectively updated without having to reload the entire page. The idea is to make a webpage more responsive and interactive; the data are exchanged with the server behind the scene, without impacting the display of the rest of the webpage (normally, a webpage must be reloaded to view new information). AJAX server requests are asynchronous and independent of each other. That means, when a browser makes an AJAX request, the browser does not wait for the response by stopping the webpage functionality. Instead, AJAX will process returning responses and refresh parts of a webpage that are already loaded into a browser. As I mentioned earlier, AJAX is a set of technologies, based on open standards; HTML and CSS to mark up and style the data, JavaScript to process server responses and dynamically deliver these to the user, and XML or JSON to transfer data from server to browser (JSON is becoming more popular due to its advantage of being part of JavaScript). The core concept of AJAX is XMLHttpRequest JavaScript object (also called XHR). The XMLHttpRequest object is used by JavaScript to establish independent Http connection between the client and server.

2. #### JSON (JavaScript Object Notation)

An alternative to XML, JavaScript Object Notation is a lightweight, text-based, language-independent minimal data interchange format used to transmit data between a server and web application. Based upon JavaScript syntax (but distinct from it), the core concept making up JSON are keys and values, or key/value pair. The key is a string, while value must be a string, number, boolean expression, array or an object. The syntax for the key/value pair is a key in quotation marks followed by a colon followed by a value. The key/value pairs are comma separated. To access the data, JSON needs to be converted to a native JavaScript object with JSON.parse() method. JSON is not limited to AJAX, it can be used whenever an application needs to exchange or store structured information.

3. #### API (Application Programming Interface)

Operating as a gate, API is a set of instructions allowing two applications to talk to each other. Developers work with APIs to create applications, so companies can share selected information. In other words, companies do release API so that developers can create applications powered by that service; the API defines the method for a developer to request the service from that application. In simple terms, APIs make it possible for organizations to release their data or functionality for reuse in new applications. There are two fundamental elements that create an API; a technical specification establishing the process of exchange of information between two applications and interface publishing that specification. The syntax for making requests are described in the documentation of the application being called.
