# TEAF Snippets for vscode

This extension contains snippets for TEAF development.

## Supported languaguages
* React
* Typescript

## Snippets
Bellow are listed supported snippets

| Trigger  | Content |
| :------- | ------- |
| `actionCreator→`   | Creates a redux action creator |
| `actionInterface→`   | Creates an interface for redux action |
| `interfaceInstanceOf→`   | Creates a new Interface with support of `instanceof` comparison|
| `rfc→`   | Template for typed react functional component |
| `expall→`   | Export all from package |
| `ims→`   | Import sinon package |
| `imf→`   | Import { `whatever` } from "`some package`" |
| `useState→`   | Creates strongly typed `useState` with default value |
| `useEffect→`   | Creates template for `useEffect` with optional cleanup function |
| `omitContainerProps` | Creates template for connected component props |
## Samples

### Action Creator
 Creates a redux action creator. 
 #### optional placeholders
 * Action Name (required)
 * Payload (optional)
 * Meta (optional)
 * JSDoc (optional)
  
<img src="./docs/actionCreator.gif"/>

### Action Interface
 Creates an interface for redux action
 #### optional placeholders
 * Action Name (required)
 * Extends (optional)
 * Payload (optional)
 * JSDoc (optional)
  
<img src="./docs/actionInterface.gif"/>

### Interface with instanceof 
Creates a new Interface with support of `instanceof` comparison.
 #### Placeholders
 * Action Name (required)
 * Extends (optional)
 * Properties (optional)
 * Methods (optional)
 * Interfaces (optional)
 * Conditions in `instanceof` (optional)
  
<img src="./docs/interfaceInstanceOf.gif"/>

### React Functional Component 
Template for typed react functional component.
 #### Placeholders
 * Component Name (required, name of file is default value)
 * BemClassName (optional)
 * Props (optional, `children` default value)
 * JSDoc (optional)
  
<img src="./docs/rfc.gif"/>

### useState
Creates strongly typed `useState` with default value.

<img src="./docs/useState.gif"/>

### useEffect
Creates template for `useEffect` with optional cleanup function.

 #### Placeholders
 * Dependency Array (optional)
 * Cleanup function (optional)
 * JSDoc (optional)

<img src="./docs/useEffect.gif"/>

### Export all
Creates syntax for export all from package.

<img src="./docs/expall.gif"/>

### Import sinon package
creates import for sinon package.

<img src="./docs/ims.gif"/>

### Import { `whatever` } from "`some package`"

<img src="./docs/imf.gif"/>

### OmitCointerProps
Snippet used when connection presentational component to redux. It creates props for connected component and omits props connected in StateProps or DispatchProps. 

 #### Placeholders
 * Component Name (required, name of file is default value)
 * Own props (optional)
 * JSDoc (optional)

<img src="./docs/omitContainerProps.gif"/>
