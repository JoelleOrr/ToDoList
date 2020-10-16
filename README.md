This is a simple application that creates a RESTful Express API.  It will give users the ability to CREATE, READ, UPDATE, and DELETE items from a To Do list.

<!-- www.example.com/ -->

In order to view all of the To Do items in this application, make an HTTP GET request to /api/items

To create a new To Do item in this application, make an HTTP POST request to /api/items .. it should look like this:

```
{
    "id": 3;
    "item": "the name of the thing we're including";
    "completed": false
}

```



