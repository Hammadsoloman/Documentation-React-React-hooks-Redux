# Fetch – Axios - Superagent
## By: Hammad Ali 

### XMLHttpRequest: is an API in the form of an object whose methods transfer data between a web browser and a web server. The object is provided by the browser's JavaScript environment.

### fetch() allows you to make network requests similar to XMLHttpRequest (XHR). The main difference is that the Fetch API uses Promises, which enables a simpler and cleaner API, avoiding callback hell and having to remember the complex API of XMLHttpRequest.

•To send data, fetch() uses the body property 
•The data in fetch() is stringified 
•The URL is passed as an argument to fetch().
Also doesn’t support progress events, advanced timeouts, errors with metadata and hooks.


### Axios: This is a Promise-based HTTP library for performing HTTP requests on both Nodejs and Browser.**

#### Props
•	Axios has url in request object.
•	Axios is a stand-alone third party package that can be easily installed. 
•	Axios uses the data property. 
•	Axios performs automatic transforms of JSON data.
•	Axios allows cancelling request and request timeout. 
•	Axios has the ability to intercept HTTP requests.
•	Axios has built-in support for download progress. 
•	Axios has wide browser support.
#### Cons
It also doesn’t retry on failures and works on Node.js with prebuilt promise support. 

### Superagent: is a library for making HTTP AJAX requests.
#### Props
Superagent is very well-known, it provides a fluent interface for making HTTP requests, and numerous plugins already available for many common features.
Also, it retries when there is a failure
#### Cons	
it doesn’t support monitoring upload progress.
It doesn’t support timings, errors with metadata, or hooks.



1)	Why we use superagent rather than axios in fetch data?

     _superagent has built-in retry, axios does not provide retry
2)	Why we use axios rather than superagent in post data?
 _ axios has the ability to monitor POST request progress.






