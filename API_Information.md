# API Information

An API is a set of rules that lets one piece of software talk to another, allowing them to share data or features without needing to know how the other is built.

Here is an example i.e. ordering at a restaurant

| Real life                         | API equivalent                                                                     |
| :-------------------------------- | :--------------------------------------------------------------------------------- |
| You                               | Application 1                                                                      |
| Restaurant Kitchen                | Application 2                                                                      |
| The Menu                          | The API                                                                            |
|                                   |                                                                                    |
| You order something from the menu | You call an API endpoint e.g. /order/mac-and-cheese                                |
| The kitchen makes the food        | Application 2 is told by the API what you want and processes the request           |
|                                   | The API sends a 200 response (OK - the server understood and accepted the request) |
| Your food is served               | Along with the 200 response data is sent e.g. {"food": "served"}                   |


In simple terms: it’s like a menu in a restaurant: You (one system) choose what you want, the kitchen (another system) prepares it and sends it back.

This document will give you the endpoints you will start with and some basic information on how to call the API.

You will be using the Postman application at 

# Endpoints

| Request Method | Endpoint                   | Content Type                      | Content Required   | Description                      |
| :------------- | :------------------------- | :-------------------------------- | :----------------- | :------------------------------- |
| GET            | /task/{task_number}        | N/A                               | N/A                | Get the information for the task |
| POST           | /task/{task_number}/submit | application/json                  | team_token, code   | Submit the answer to the task    |
| GET            | /account/login             | N/A                               | N/A                | Get the login page               |
| POST           | /account/login             | application/x-www-form-urlencoded | username, password | Go to the user page directly     |