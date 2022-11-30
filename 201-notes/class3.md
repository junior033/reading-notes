# Readings: HTML Lists, Control Flow with JS, and the CSS Box Model

## Learn HTML

### Ordered and Unordered lists.

1. When should you use an unordered list in your HTML document?
When grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. 

2. How do you change the bullet style of unordered list items?
The type attribute is used when you want to change the bullet style.

3. When should you use an ordered list vs an unorder list in your HTML document?
Typically, ordered list items display with a preceding marker, such as a number or letter.

4. Describe two ways you can change the numbers on list items provided by an ordered list?
You can use the reversed attribute to list items starting from a high number to the lowest and you can use the start attritube to start the list
at a specific number.

## Learn CSS

### The Box Model.

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
If margin and padding are preparing for a reception. Margin's role is to make sure that each item at the reception stays within their specified area.
Padding's job is to make sure that the items are giving eachother enough space between eachother.

2. List and describe the four parts of an HTML elements box as referred to by the box model.
Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
Padding box: The padding sits around the content as white space; size it using padding and related properties.
Border box: The border box wraps the content and any padding; size it using border and related properties.
Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; 
            
## Learn JS

### Arrays. Operators and Expressions. Conditionals. Loops.

1. What data types can you store inside of an Array?
In an array we can store various data types — strings, numbers, objects, and even other arrays. 

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 `const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`
 
You can access individual items in the array using bracket notation and supplying the item's index.

3. List five shorthand operators for assignment in javascript and describe what they do.
  1. += adds the value of the right operand to a variable and assigns the result to the variable.
  2. -= subtracts the value of the right operand from a variable and assigns the result to the variable.
  3. *= multiplies a variable by the value of the right operand and assigns the result to the variable.
  4. /= divides a variable by the value of the right operand and assigns the result to the variable.
  5. %= divides a variable by the value of the right operand and assigns the remainder to the variable.
  
4. Read the code below and evaluate the last expression and explain what the result would be and why.

```
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
```
The result is 10dog. You cannot add 10 + a boolean but you can add a string to a number to convert it into a string.
 
5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
When checking a users input you would need to add conditional statements to determine what you want the program to do with the input.

6. Give an example of when a Loop is useful in JavaScript.
A loop can be used when depending on the result of an input you will need to execute a block of code that amount of times.
