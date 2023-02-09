# Reading

## React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?

A component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

2. What does it mean to build a ‘static’ version of your application?

The easiest way is to build a version that takes your data model and renders the UI but has no interactivity. It’s best to decouple these processes because building a static version requires a lot of typing and no thinking, and adding interactivity requires a lot of thinking and not a lot of typing.

3. Once you have a static application, what do you need to add?

Once you have a static version of the application add in state for interactivity.

4. What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live?

- Identify every component that renders something based on that state.
- Find a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
 
## Higher-Order Functions

1. What is a “higher-order function”?

Functions that operate on other functions, either by taking them as arguments or by returning them.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

First it checks if n is > than m and if so it checks if m is => then return true if not return false.

3. Explain how either map or reduce operates, with regards to higher-order functions.

Map and reduce both are methods that can be ran on another function and returns a new value.


## Things I want to know more about

Are there any exercises to develop a better understanding of where state should live?
