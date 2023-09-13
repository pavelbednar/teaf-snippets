# TEAF Snippets for vscode

This extension contains snippets for TEAF development.

## Supported languaguages
* React
* Typescript

## Snippets
Bellow are listed supported snippets

### General snippets
| Trigger  | Content |
| :------- | ------- |
| `interfaceInstanceOf→`   | Creates a new Interface with support of `instanceof` comparison|
| `rfc→`   | Template for typed react functional component |
| `useState→`   | Creates strongly typed `useState` with default value |
| `useEffect→`   | Creates template for `useEffect` with optional cleanup function |

### Redux Actions Snippets
| Trigger  | Content |
| :------- | ------- |
| `actionCreator→`   | Creates a redux action creator |
| `actionInterface→`   | Creates an interface for redux action |

### Import/Export snippets
| Trigger  | Content |
| :------- | ------- |
| `expall→`   | Export all from package |
| `ims→`   | Import sinon package |
| `imf→`   | Import { `whatever` } from "`some package`" |

### Connected Components Snippets
| Trigger  | Content |
| :------- | ------- |
| `omitContainerProps→` | Creates template for connected component props |
| `stateProps→` | Creates StateProps type |
| `dispatchProps→` | Creates DispatchProps type |
| `connect→` | Connects presentational component with props |
| `mapStateToProps→` | Creates `mapStateToProps` variable used when connecting presentational components |
| `createMapStateToProps→` | Creates function `createMapStateToProps` returning `MapStateToProps |
| `mapDispatchToProps→` | Creates `mapDispatchToProps` variable used when connecting presentational components |


# Samples
## General snippets
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

## Redux Actions Snippets
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

## Import/Export snippets
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

## Connected Components Snippets

### stateProps
Creates `StateProps` type picking props from presentational component.
<img src="./docs/stateProps.gif"/>

### dispatchProps
Creates `DispatchProps` type picking props from presentational component.
<img src="./docs/dispatchProps.gif"/>

### connect
Connects presentational component with props.
<img src="./docs/connect.gif"/>

### mapStateToProps
Creates `mapStateToProps` variable used when connecting presentational components.
 #### Placeholders
 * Component Name (required, name of file is default value)
 * Create `StateProps` or skip them (optional)
 * Own component props entering mapStateToProps (optional)

<img src="./docs/mapStateToProps.gif"/>

### createMapStateToProps
Creates function `createMapStateToProps` returning `MapStateToProps.
 #### Placeholders
 * Component Name (required, name of file is default value)
 * Create `StateProps` or skip them (optional)
 * Own component props entering mapStateToProps (optional)

<img src="./docs/createMapStateToProps.gif"/>

### mapDispatchToProps
Creates `mapDispatchToProps` variable used when connecting presentational components.
 #### Placeholders
 * Component Name (required, name of file is default value)
 * Create `DispatchProps` or skip them (optional)
 * Own component props entering mapStateToProps (optional)

<img src="./docs/mapDispatchToProps.gif"/>