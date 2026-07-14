# What is React?

React is a **JavaScript Library** developed by **Meta (Facebook)** for building **fast, interactive, and reusable User Interfaces (UI)**.

### Why React?

* Easy to build modern websites
* Reusable Components
* Fast Performance
* Easy to maintain
* Large Community Support


# Features of React :- 

## Component-Based Architecture

A React application is divided into small reusable components.

Example:

```text
Website

├── Navbar
├── Hero
├── About
├── Services
├── Contact
└── Footer
```

### Advantages

* Reusable
* Easy to Understand
* Easy to Maintain
* Clean Code


## Virtual DOM

React creates a lightweight copy of the Real DOM called the **Virtual DOM**.

### Working

```
User Action
      ↓
State Changes
      ↓
Virtual DOM Updates
      ↓
React Compares Changes
      ↓
Only Changed Elements Update
      ↓
Real DOM Updates
```

### Benefits

* Faster Rendering
* Better Performance
* Less Browser Work


## JSX

JSX stands for **JavaScript XML**.

It allows us to write HTML inside JavaScript.

Example:

```jsx
function App() {
  return (
    <h1>Hello React</h1>
  );
}
```



## Reusable Components

Write once and use multiple times.

Example:

```jsx
<Card name="Rasul" />
<Card name="Rahul" />
<Card name="Aman" />
```

## One-Way Data Flow

Data always flows from **Parent Component → Child Component** using **Props**.

```
App
 ↓
Card
 ↓
Button
```


## Fast Performance

React is fast because it uses:

* Virtual DOM
* Efficient Rendering
* Component Reusability


# SPA (Single Page Application)

SPA stands for **Single Page Application**.

The website loads **only one HTML page**, and React updates only the required content without reloading the entire page.

### Traditional Website

```
Home
 ↓ Reload
About
 ↓ Reload
Services
 ↓ Reload
Contact
```

### React SPA

```
Home
 ↓
About
 ↓
Services
 ↓
Contact
```

No full-page reload.

### Examples

* Gmail
* Facebook
* Instagram
* WhatsApp Web
* Netflix


# React Architecture

A professional React project is divided into components.

```
src/

├── components/
│   ├── Navbar.jsx
│   ├── Hero.jsx
│   ├── Card.jsx
│   └── Footer.jsx
│
├── pages/
│   ├── Home.jsx
│   ├── About.jsx
│   └── Contact.jsx
│
├── assets/
│
├── App.jsx
├── main.jsx
└── index.css
```

### Flow

```
main.jsx
      ↓
App.jsx
      ↓
Components
      ↓
Browser UI
```


# JSX

JSX lets us write HTML-like syntax inside JavaScript.

Example:

```jsx
function App() {
  return (
    <>
      <h1>Welcome</h1>
      <p>Learning React</p>
    </>
  );
}
```

### JSX Rules

* Return only one parent element.
* Close all tags.
* Use `className` instead of `class`.
* Write JavaScript inside `{}`.


# Dynamic Variables

Dynamic variables display JavaScript values inside JSX.

Example:

```jsx
function App() {

  let name = "Rasul";
  let age = 22;

  return (
    <>
      <h1>{name}</h1>
      <h2>{age}</h2>
    </>
  );
}
```

### Output

```
Rasul
22
```

### What can be written inside `{}`?

* Variables
* Numbers
* Calculations
* Function Calls
* Object Properties
* Ternary Operators




# Interview Questions

### Q1. What is React?

React is a JavaScript library used to build fast and interactive user interfaces using reusable components.



### Q2. What is JSX?

JSX is a syntax extension that allows us to write HTML-like code inside JavaScript.


### Q3. What is SPA?

SPA (Single Page Application) loads a single HTML page and updates content dynamically without refreshing the whole page.


### Q4. Why is React Fast?

React is fast because it uses the Virtual DOM, which updates only the changed parts of the page.


### Q5. What is a Component?

A component is a reusable piece of UI that can be used multiple times.


