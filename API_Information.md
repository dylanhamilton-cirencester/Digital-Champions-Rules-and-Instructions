# API Information

An API (Application Programming Interface) is a set of rules that lets one piece of software talk to another, allowing them to share data or features without needing to know how the other is built.

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

You may use the Postman application during the event, useful information on how to use Postman can be found [here](Postman_Instructions.md).

# Endpoints

You can find documentation for the API at `/docs`