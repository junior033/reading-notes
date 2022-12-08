# Readings: Forms and JS Events

## HTML Forms

1. Why are forms so important in web development?

You can build any kind of basic form using dedicated form elements and attributes. 

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

A few key things to keep in mind when designing a form is to order the form logically, the columns and rows needed, clear instructions on how to fill
the form out, and highlighting required fields.

3. List 5 form elements and explain their importance.

`<fieldset>` element is a convenient way to create groups of widgets that share the same purpose, for styling and semantic purposes. 

`<legend>` element allows you to provide the `fieldset` element a label.

`<label>` element is the formal way to define a label for an HTML form widget.

`<input>`	To define input control

`<option>` To define an option for the drop-down.


## Learn JS

1. How would you describe events to a non-technical friend?

An event is a action that triggers when something specific happens.

2. When using the addEventListener() method, what 2 arguments will you need to provide?

The two arguments you need to provide an event listener are the name of the even and the function to handle the event.

3. Describe the event object. Why is the target within the event object useful?

The even object is a parameter specified with a name such as event, evt, or e. It is automatically passed to event handlers to provide extra features and information.
The target property of the event object is always a reference to the element the event occurred.

4. What is the difference between event bubbling and event capturing?

Event bubbling describes how the browser handles events targeted at nested elements.
Event capture is like event bubbling but the order is reversed: the event fires first on the least nested element, and then on successively more nested elements, until the target is reached.

## Things I want to know more about

1. Is it possible to do animations or games with EventListeners?
