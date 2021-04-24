# React

**What is React?**

* React is a JavaScript library for building user interfaces.

* React is used to build single page applications.

* React allows us to create reusable UI components.

**How does React Work?**

* React creates a *VIRTUAL DOM* in memory, where it does all the necessary manipulating, before making the changes in the browser DOM.

* React finds out what changes have been made, and changes only what needs to be changed.

## React JSX

**What is JSX?**

* JSX stands for JavaScript XML.

* JSX allows us to write HTML in React.

* JSX makes it easier to write and add HTML in React.

**JSX** allows us to write HTML elements in JavaScript and place them in the DOM without any createElement()  or appendChild() methods.

**JSX** converts HTML tags into react elements.

## Rendering Elements

React renders HTML to the web page by using a function called ReactDOM.render().

The ReactDOM.render() function takes two *arguments*, HTML code and an HTML element.

The purpose of the function is to *display* the specified HTML code inside the specified HTML element.

## React Components

All React components must act like pure functions with respect to their props.

*Components* let you split the UI into independent, **reusable** pieces, and think about each piece in isolation.

When creating a React component, the component's name must start with an **upper** case letter.

Components come in two types, Class components and Function components.

* Class components

It requires you to extend from React.Component and create a render function which returns a React element.

* Function components

It is a plain JavaScript function which accepts props as an argument and returns a React element.

## React Props

Props are arguments passed into React components.

Props are passed to components via HTML attributes.
