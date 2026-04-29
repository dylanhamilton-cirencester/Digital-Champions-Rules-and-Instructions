# Postman Application

Postman is a tool used by developers to test APIs. It has a great user interface to help understand making HTTP requests and send them as well as features to add the requests to your code.

# How to use Postman

Postman is simple to learn and easy to use. Here is an example for a simple GET request to an API.

![Postman](imgs\Postman_Annotated.png)

**URL** - The URL is the endpoint to which you make the call to the API

**Method Select** - The Method select is where you can pick what method the HTTP request will be sent as

**Parameters** - Here you can add parameters to your request i.e. item_id. In a POST request you can send data in different formats in the body section of the request e.g. JSON or Form data

**Send Request** - The send button will send your request to the endpoint provided

**Response** - After sending the request you will get a response back. If the request was successful you'll get a 200 - OK response with some data (if the endpoint supplies it), otherwise you will get an error code i.e. 404 - Not Found or 502 Bad Gateway

**Code Generator** - A great feature about Postman is it can generate commands/ code to help you make these requests in a terminal or in your application. You can use this feature to get the ball rolling with integrating any relevant API endpoints into your application

This is just a simple example for GET requests only. You will have to figure out how to do other types of requests yourself.