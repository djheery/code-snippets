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
    <div>FileName</div>
  )
}

export default FileName;
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
      <h1>File Name</h1>
    </div>
  )
}

export default FileName;
```
