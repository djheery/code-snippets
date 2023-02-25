# React Snippets

Below details the snippets in `react-snippets.code-snippets`

## React Functional Component

Create a react functional component for the given file name with a css module import for the file and comments formatted for the better comments extension.

**Prefix**: `rfce`<br />
**Example**:

```
import styles from './FileName.module.css'

// Comments....

const FileName = (props) => {
  return (
    <div>
      FileName Component
    </div>
  )
}

export default FileName;
```

## React Page Component

Create a react page component the file name is not automatically entered thus you will be automatically highlighted over the `PageName` placeholder to replace this text with the name of the page. This is because it is assumed that your page name will be the folder name and the file will be called index.tsx

**Prefix**: `rpge`<br />
**Example**:

```
import styles from './FileName.module.css'

// Comments....

const PageName = (props) => {
  return (
    <div>
      <h1>PageName</h1>
    </div>
  )
}

export default PageName;
```

## React Functional Component with TypeScript

Create a react functional component **with TypeScript** for the given file name with a css module import for the file and comments formatted for the better comments extension.

**Prefix**: `rfct`<br />
**Example**:

```
import styles from './FileName.module.css'

// Comments....

const FileName: React.FC = () => {
  return (
    <div>
      <div>
        File Name Component
      </div>
    </div>
  )
}

export default FileName;
```

## React Page Component with TypeScript

Create a react page component **with TypeScript** the file name is not automatically entered thus you will be automatically highlighted over the `PageName` placeholder to replace this text with the name of the page. This is because it is assumed that your page name will be the folder name and the file will be called index.tsx

**Prefix**: `rpgt`<br />
**Example**:

```
import styles from './index.module.css'

// Comments....

const PageName: React.FC = () => {
  return (
    <div>
      <h1>Page Name</h1>
    </div>
  )
}

export default PageName;
```

## JSX Div Element With ClassName field

Create a jsx div with the `className` field. The `className` field will automatically be highlighted to add the class.

**Prefix**: \_cdiv<br/>
**Example**:

```
/*
  Inside the return statement of a react functional or page component. everything after the return statement is the output of the snippet
*/

return (
  <div className={styles["className"]}>

  </div>
)
```
