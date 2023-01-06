## React lifecycle


1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render occurs before componentDidMount.

2. What is the very first thing to happen in the lifecycle of React?

The constructor for a React component is called before it is mounted.

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

Constructor, render, componentDidMount, React Updates, componentWillUnmount.

4. What does componentDidMount do?

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here.
This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

## React State Vs Props


1. What types of things can you pass in the props?

Props are a type of argument you want to pass to a component.

2. What is the big difference between props and state?

The main difference between props and state are that props are passed into a component and state is handled inside of that componenet. Props are updated outside
of the component whereas state is updated inside of the component.

3. When do we re-render our application?

When state is updated it will re-render that section of the application.

4. What are some examples of things that we could store in state?

Things that are going to be only handled within that component that will be changing like a counter, user input, and forms.

## Things I want to know more about

What are some good tutorials to learn more about using props and state?
