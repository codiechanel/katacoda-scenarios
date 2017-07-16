This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command**

install the request 

`npm i request`{{execute}}


First let's enter node shell

`node`{{execute}}

Let's make a request

`var request = require('request');
request('http://www.google.com', function (error, response, body) {
  console.log('error:', error); // Print the error if one occurred 
  console.log('statusCode:', response && response.statusCode); // Print the response status code if a response was received 
  console.log('body:', body); // Print the HTML for the Google homepage. 
});`{{execute}}
