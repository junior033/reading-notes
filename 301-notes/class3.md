# Reading

## React Docs - lists and keys

1. What does .map() return?

The map() method returns a new array populated with the results of calling a provided function on every element in the calling array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

```
const listItems = numbers.map((number) =>
  <li>{number}</li>
);
```

3. Each list item needs a unique Key.

4. What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity:

## The Spread Operator

1. What is the spread operator?

Spread operator is a quick syntax for adding items to arrays, combining arrays or objects and spreading an array out into a functions arguments.

2. List 4 things that the spread operator can do.

- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list
- Adding to state in React
- Combining objects
- Converting NodeList to an array

3. Give an example of using the spread operator to combine two arrays.

` const ourArray = [...myArray,...yourArray] `

4. Give an example of using the spread operator to add a new item to an array.

```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
```

5. Give an example of using the spread operator to combine two objects into one.

` const objectThree = {...objectOne, ...objectTwo} `

# Videos

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?

You have to create the function in the parent component.

2. In your own words, what does the increment function do?

The increment function takes in a prop and creates a new array by accessing the state with the map method and finally incrementing count value for each object.

3. How can you pass a method from a parent component into a child component?

You have to pass a reference to the method as a prop to the child component.

4. How does the child component invoke a method that was passed to it from a parent component?

` this.props.increment() `

## Things I want to know more about

Is it good practice to limit the amount of methods passed to a child component?
