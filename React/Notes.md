# **React**

## Overall knowledge

**SPA (Single page Applications)**

- Website with only one page
- dynamically updates the page as the user interacts with it withought reloading the page multiple times
- heavily relies DOM maninpulation (often used with libraries)

**DOM (Document Object Model)**

- Turns raw html -> tree of objects
- bridge between the code and what you see on the screen

**What is React**

- One of the most popular JS libraries, made by Facebook (meta)
- React uses a virtual DOM rather then manipulation (js)
- A tree of componets that are put together
- **Componets**
  - Class or function that returns html code (JSX)
- **JSX** - JS+XML, very similar to JS but with some syntax diffrences

  ```jsx
  function profile({ name }) {
    return (
      <div>
        <h1> Hello, My name is: {name} </h1>
      </div>
    );
  }
  ```

  **Routing**

- How you can have multiple pages in a single template/framework
- Keeps UI in sync w URL

**Props**

- When you need to pass data down from one componet to another (very similar to a function paramater)

**Componet Life Cycle**

- **Mounting**
  - when its first being added to the DOM
- **Update**
  - when it gets modified and needs to be updated
- **Unmounting** - when its being removed from DOM

**State**

- allows components to store, manage, and track data that can change over time
- acts as a componet's memory

**Hooks**

- only apply to functional componets
- Add state and other features without using class based componets
- Functions that allow us to manage state
- Most common Hooks
  ```jsx
  useState(); //--> set and update state
  useEffect(); // --> Perform side effects in lifecycle
  ```

## Actual Coding

**Files**

- ".ts" used for tranditional TypeScript files
- ".tsx" used for TypeScript+React
