# Readings: Problem Domain, Objects, and the DOM

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?

An object is something that holds information. Depending on that information, it can just store it or actually do things with
information. If you were to make a chair in as an object then you would store the basic information and purpose of the chair.

2. What are some advantages to creating object literals?

When you want to transfer a series of structured, related data items in some manner, for example sending a request to the server 
to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name.

3. How do objects differ from arrays?

Objects represent “things” with characteristics (aka properties), while arrays create and store lists of data in a single variable.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

If an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

The `this` keyword refers to the current object the code is being written inside. It enables you to use the same method definition for every object you create.

```
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

## Introduction To The DOM

1. What is the DOM?
 
The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web. 

2. Briefly describe the relationship between the DOM and JavaScript.

JavaScript uses the DOM to access the document and its elements.  The document as a whole, the head, tables within the document, table headers, 
text within the table cells, and all other elements in a document are parts of the document object
model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript.

## Things I would like to know more about
How many objects can be nested within an object?
