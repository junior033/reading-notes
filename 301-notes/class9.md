# Reading

## Functional Programming Concepts

1. What is functional programming?

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

2. What is a pure function and how do we know if something is a pure function?

It returns the same result if given the same arguments (it is also referred as deterministic) and it does not cause any observable side effects

3. What are the benefits of a pure function?

Because they don't modify the global state, they are faster than regular functions. They also use less memory, which is important for applications with large data sets. Finally, pure functions are simple and easy to understand

4. What is immutability?

Unchanging over time or unable to be changed. When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

5. What is Referential transparency?

Basically, if a function consistently yields the same result for the same input, it is referentially transparent. pure functions + immutable data = referential transparency

# Videos

## Node JS Tutorial for Beginners #6 - Modules and require()

1. What is a module?

Modules have different functionalities within the applications. IE. utility module that we can call upon when necessary.

2. What does the word ‘require’ do?

When you need to use some functionality somewhere else in the application we use the node.JS 'require' function.

3. How do we bring another module into the file the we are working in?

We use the `require(./filename); ` function to import into the file we are working in and set it to a variable for use within the file.

4. What do we have to do to make a module available?

In order for a module to be available we must export the function. ` module.exports = functionName; `

## Things I want to know more about

What are some good practice techniques for functional program.
