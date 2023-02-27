# Task

Each of you clone  this repository aonto your computer using Githib Desktop.

Set up a new branch on your local repo. 

Switch to that branch and add some new code.


When you are happy with it publish the branch.

Make a pull request to merge it into the main branch.

#Questions for today:

##What type of http request do I need to make  to add a new resource via a API?

To add a new resource via an API, you need to use the HTTP POST request method.

When you make a POST request, the client sends data to the server to create a new resource. The server then processes the data and creates the resource on the server-side.

Typically, you will need to specify the URL of the endpoint where the resource should be created, and include the data for the new resource in the body of the request. The server may respond with a success status code and the newly created resource, or an error status code if there was a problem with the request.

Here is an example of a POST request to create a new user resource using JSON format in the request body:

POST /api/users HTTP/1.1
Host: example.com
Content-Type: application/json

{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "password123"
}

In this example, the request is sent to the /api/users endpoint on the example.com server, with the data for the new user included in the request body as JSON. The server would then process the request and create the new user resource.

##CSS, if we want to align using flex-box  in the middle on the horizontal axis what are the flex properties I need to use? 3 answers needed...

##JS, what is a  function parameter?

##JS, what is an event listener?

##What do we mean by the DOM?
