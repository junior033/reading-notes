# Reading

## React Docs - Forms

1. What is a ‘Controlled Component’?

Controlled Components are those in which form’s data is handled by the component’s state.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

No, because the input value is driven by the state.

3. How do we target what the user is entering if we have an event handler on an input field?

Add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?

Syntatic sugar, it allows us to shorten our if statements into one line of code.

2.  Rewrite the following statement using a ternary statement:
```
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```
` x === y ? console.log(true) : console.log(false); `
