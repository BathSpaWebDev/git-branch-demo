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

Here are three CSS flexbox properties you can use to horizontally center align elements using flexbox:

display: flex: This property specifies that the container should use a flexbox layout.

justify-content: center: This property centers the child elements horizontally along the main axis of the container.

align-items: center: This property centers the child elements vertically along the cross axis of the container.

Here's an example of how you can use these properties to center align child elements horizontally:

.container {
  display: flex;
  justify-content: center;
  align-items: center;
}

In this example, the .container element will be a flex container with the child elements centered horizontally and vertically.

Note that there are other flexbox properties you can use to achieve different alignment and layout effects depending on your needs, such as flex-direction, flex-wrap, and align-content.

##JS, what is a  function parameter?

In JavaScript, a function parameter is a value that is passed to a function as an input when the function is called. It is a variable that holds the value of the argument passed to the function.

Function parameters are defined in the function's declaration, within the parentheses after the function name. A function can have zero or more parameters, and each parameter is separated by a comma.

Here is an example of a function declaration with two parameters:

function greet(name, greeting) {
  console.log(`${greeting}, ${name}!`);
}

In this example, the greet function has two parameters: name and greeting. When the function is called with arguments, the values of those arguments are assigned to the corresponding parameters.

For example, if we call the greet function like this:

greet('Alice', 'Hello');

The name parameter would have the value 'Alice', and the greeting parameter would have the value 'Hello'. The function would then log the message "Hello, Alice!" to the console.

##JS, what is an event listener?

In JavaScript, an event listener is a function that waits for a specific event to occur on an element and then performs an action in response to that event.

Event listeners are used to listen for various types of events, such as mouse clicks, key presses, form submissions, and more. When an event occurs on an element, the event listener detects it and executes the function assigned to it.

Here is an example of how to add an event listener to an element in JavaScript:
const button = document.querySelector('button');

button.addEventListener('click', function() {
  console.log('Button clicked!');
});

In this example, we select a button element using document.querySelector(), and then add an event listener to it using the addEventListener() method. We pass two arguments to addEventListener(): the name of the event to listen for ('click'), and the function to execute when the event occurs.

When the button is clicked, the function passed to addEventListener() will execute and log the message "Button clicked!" to the console.

Note that there are many types of events that can be listened for using event listeners, and you can add multiple event listeners to the same element for different types of events. Additionally, event listeners can be removed using the removeEventListener() method.


##What do we mean by the DOM?
