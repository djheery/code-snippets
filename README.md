# Code Snippets

These are some of my custom code snippets. Below details the different snippets, their purposes and examples.

## JavaScript Snippets

Below details the snippets in `javascript-snippets.code-snippets`

### Print to Console

Create a simple log statement (As taken from the initial snippets file)

**Prefix**: `log`<br />
**Example**: `console.log('');`

### Javascript Es6 Method

Create an ES6 arrow method with comments formatted for the better comments extension.

**Prefix**: `fconst`<br />
**Example (without comments)**: `const foo = (bar) => {return bar}`

### IIFE App

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

### IIFE UI

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

### IIFE State

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

### Return Method

Create a return method when an object of methods is returned

**Prefix** rmethod
**Example**

```
 return {
   foo: (bar) => {
     return bar;
   }
 }

```

## React Snippets

Below details the snippets in `react-snippets.code-snippets`

### React Functional Component

Create a react functional component for the given file name with a css module import for the file and comments formatted for the better comments extension.

**Prefix**: `rfce`<br />
**Example**:

```
import styles from './FileName.module.css'

// Comments....

const FileName = (props) => {
  return (
    <div>FileName</div>
  )
}

export default FileName;
```

### React Functional Component with TypeScript

Create a react functional component **with TypeScript** for the given file name with a css module import for the file and comments formatted for the better comments extension.

**Prefix**: `rfct`<br />
**Example**:

```
import styles from './FileName.module.css'

// Comments....

const FileName: React.FC<{children: React.PropsWithChildren}> = ({children}) => {
  return (
    <div>
      <h1>File Name</h1>
      <div>
        {children}
      </div>
    </div>
  )
}

export default FileName;
```

## TypeScript

Below details the code snippets in `typescript-snippets.code-snippets`

### TypeScript ES6 Method

Create an ES6 arrow method **with TypeScript** and comments formatted for the better comments extension.

**Prefix**: `ftconst`<br />
**Example (without comments)**:

```
// Some comments formatted for better comments

const foo = (bar: string): string {
  return bar;
}
```

## Comment Snippets

All the comment snippets are made to work with the better comments extension

### TODO

Make a todo comment

**Prefix**: `todo`<br />
**Example**:

```
// TODO: Something to do
```

### Question

Make a question comment

**Prefix**: `question`<br />
**Example**:

```
// ? type your question here
```

### Warning

Make a warning comment

**Prefix**: `warning`<br />
**Example**:

```
// ! write your warning here
```

### important

Make an important comment

**Prefix**: `important`<br />
**Example**:

```
// * Something important goes here
```
