CSC495-project-individual-part
==============================

Our part of the project is to save file from editors, tabbed interface and validation 

1.	JavaScript doesn’t have typed variables. This means there is only one variable type, var which you can assign any primitive(basic) type of variable to it, such as a string, a char, an integer, a float, or a boolean.
2.	Our tabbed interface will have a list supporting it (in JavaScript, lists and arrays are the same thing, so it’s called an array). Each tab will be represented by a JSON object in the list. Each JSON object will contain the users code that they are typing in. The list of tabs will be stored as a javascript array on the client side (user’s computer).
a.	Mike is bringing in a document which will show the whole class what we have decided on for the structure of our JSON objects
3.	Once the user clicks save, we need to call the appropriate route to save the file. All you need to do is make sure the JSON object is valid (client side verification), and then send it to the route. The server side coding (PHP), will be done by someone else. You just need to send them a valid JSON file.



