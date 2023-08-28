# Text Area In JAVASCRIPT
1. Execution Context
The environment in which JavaScript Code runs is called Execution Context.

Execution context contains all the variables, objects, and functions.

Execution Context is destroyed and recreated whenever we reload an Application.

2. Storage Mechanisms
2.1 Client-Side Data Storage
Client-Side Data Storage is storing the data on the client (user's machine).

Local Storage
Session Storage
Cookies
IndexedDB and many more.
2.2 Server-Side Data Storage
Server-Side Data Storage is storing the data on the server.

3. Local Storage
It allows web applications to store data locally within the user's browser.

It is a Storage Object. Data can be stored in the form of key-value pairs.

Please note that both key and value must be strings. If their type is other than a string, they get converted to strings automatically.

Key	Value
fullName	Rahul Attuluri
gender	Male
city	Delhi
To access and work with Local Storage we have below methods:

setItem()
getItem()
clear()
removeItem()
3.1 The setItem() Method
The setItem() method can be used for storing data in the Local Storage.

Syntax: localStorage.setItem("Key", "Value");

3.2 The getItem() Method
The getItem() method can be used for getting data from the Local Storage.

Syntax: localStorage.getItem("Key");

Try out the setItem() and getItem() methods in the below Code Playground.