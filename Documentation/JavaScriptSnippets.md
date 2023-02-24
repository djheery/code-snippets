# JavaScript Snippets

Below details the snippets in `javascript-snippets.code-snippets`

## Print to Console

Create a simple log statement (As taken from the initial snippets file)

**Prefix**: `log`<br />
**Example**: `console.log('');`

## Javascript Es6 Method

Create an ES6 arrow method with comments formatted for the better comments extension.

**Prefix**: `fconst`<br />
**Example (without comments)**: `const foo = (bar) => {return bar}`

## IIFE App

Create the boiler plate code for an immediatley invokable function (IIFE) for the app file of an MVC widget (Mainly used with squarespace embedded widgets)

**Prefix**: `iife`<br />

**Example**:

```
const SOME_APP = (() => {
  // boilerplate code
  return {
    init: () => {
      loadEventListeners();
    }
  }
})

SOME_APP.init()
```

## IIFE UI

Create the boiler plate code for an immediatley invokable function (IIFE) for the UI file of an MVC widget (Mainly used with squarespace embedded widgets)

**Prefix**: `uiife`<br />

**Example**:

```
const SOME_UI = (() => {
  const selectors = () => {
    btn: document.querySelector('btn');
  }

  return {
    getSelectors: () => {
      return selectors;
    }
  }
})

```

## IIFE State

Create the boiler plate code for an immediatley invokable function (IIFE) for the state file of an MVC widget (Mainly used with squarespace embedded widgets)

**Prefix**: `siife`<br />
**Example**:

```
const SOME_STATE = (() => {
  const state = () => {
    isActive: false;
  }

  return {
    getState: () => {
      return state;
    },
    setState: () => {
      state.isActive = !state.isActive;
    }
  }
})

```

## Return Method in Object

Create a return method when an object of methods is returned

**Prefix**: rmethod<br/>
**Example**

```
 return {
   foo: (bar) => {
     return bar;
   }
 }

```