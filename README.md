# SSW 345 Homework 4 - REST

My submission is in the REST folder.

The github api script is run by using `node index.js` in the `REST` folder.
The server is run by using `node index.js` in the `REST/server` folder.

The REST server functions in a series of steps:
1. POST request is made with body
2. A UID is created
3. In a global in-memory object, a key/value pair is set with the UID as the key and posted data as the value.
4. On GET request, the program simply checks the value for the given key in the global object and then deletes that key/value

###Screencast
https://github.com/aej11a/HW4-345/issues/1