# Reactjs

## VS Code Reactjs snippets

---

[![Version](https://vsmarketplacebadge.apphb.com/version/elwynco.react-snippets-basic.svg)](https://marketplace.visualstudio.com/items?itemName=elwynco.react-snippets-basic)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/elwynco.react-snippets-basic.svg)](https://marketplace.visualstudio.com/items?itemName=elwynco.react-snippets-basic)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/elwynco.react-snippets-basic.svg)](https://marketplace.visualstudio.com/items?itemName=elwynco.react-snippets-basic)

This extension contains code snippets for ReactJS in JavaScript and TypeScript. It borrows heavily from [this extension](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets) by [xabikos](https://github.com/xabikos/vscode-react).

## Installation

In order to install an extension you need to launch the Command Palette (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones.

## Supported languages (file extensions)

- JavaScript React (.jsx)
- TypeScript React (.tsx)

## Snippets

Below is a list of all available snippets organised by JSX, TSX, and some that work in both and the triggers of each one. The **⇥** means the `TAB` key.

### Both .jsx and .tsx

|  Trigger  | Content                                                          |
| --------: | ---------------------------------------------------------------- |
|  `rimpa→` | Absolute import (import El from '@/El)                           |
|  `rimpr→` | Relative import (import El from './El)                           |
|    `cna→` | Classnames as array                                              |
|    `rus→` | `React.useState` hook                                            |
|    `rue→` | `React.useEffect` hook                                           |
|    `rur→` | `React.useRef` hook                                              |
|   `ruca→` | `React.useCallback` hook                                         |
|    `rum→` | `React.useMemo` hook                                             |
|   `ruco→` | `React.useContext` hook                                          |
|   `rmap→` | `.map` in markup                                                 |
| `danger→` | Dangerously Set Inner HTML prop                                  |

The output of these change based on the filetype (`.jsx` vs `.tsx`)

|  Trigger  | Content                                                          |
| -------:  | ---------------------------------------------------------------- |
|    `rscp` | Stateless component                                              |
|   `rscpc` | Stateless component with className prop                          |


### .tsx

|  Trigger  | Content                                                          |
| -------:  | ---------------------------------------------------------------- |
|    `rtf→` | function prop type                                               |
|    `rtb→` | boolean prop type                                                |
|    `rts→` | string prop type                                                |
|    `rtn→` | number prop type                                                |
|   `rtch→` | children prop type                                               |
|   `rtcn→` | className prop type                                              |


### .jsx

|  Trigger  | Content                                                          |
| -------:  | ---------------------------------------------------------------- |
|   `ptdf→` | Start default prop types                                         |


The following table lists all the snippets that can be used for prop types.
Every snippet regarding prop types begins with `pt` so it's easy to group it all together and explore all the available options.
On top of that each prop type snippets has one equivalent when we need to declare that this property is also required.

For example ```pta``` creates the ```PropTypes.array``` and ```ptar``` creates the ```PropTypes.array.isRequired```

| Trigger  | Content |
| -------: | ------- |
| `pta→`   | `PropTypes.array,` |
| `ptar→`  | `PropTypes.array.isRequired,` |
| `ptb→`   | `PropTypes.bool,` |
| `ptbr→`  | `PropTypes.bool.isRequired,` |
| `ptf→`   | `PropTypes.func,` |
| `ptfr→`  | `PropTypes.func.isRequired,` |
| `ptn→`   | `PropTypes.number,` |
| `ptnr→`  | `PropTypes.number.isRequired,` |
| `pto→`   | `PropTypes.object,` |
| `ptor→`  | `PropTypes.object.isRequired,` |
| `pts→`   | `PropTypes.string,` |
| `ptsr→`  | `PropTypes.string.isRequired,` |
| `ptsm→`  | `PropTypes.symbol,` |
| `ptsmr→` | `PropTypes.symbol.isRequired,` |
| `ptan→`  | `PropTypes.any,` |
| `ptanr→` | `PropTypes.any.isRequired,` |
| `ptnd→`  | `PropTypes.node,` |
| `ptndr→` | `PropTypes.node.isRequired,` |
| `ptel→`  | `PropTypes.element,` |
| `ptelr→` | `PropTypes.element.isRequired,` |
| `pti→`   | `PropTypes.instanceOf(ClassName),` |
| `ptir→`  | `PropTypes.instanceOf(ClassName).isRequired,` |
| `pte→`   | `PropTypes.oneOf(['News', 'Photos']),` |
| `pter→`  | `PropTypes.oneOf(['News', 'Photos']).isRequired,` |
| `ptet→`  | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]),` |
| `ptetr→` | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]).isRequired,` |
| `ptao→`  | `PropTypes.arrayOf(PropTypes.number),` |
| `ptaor→` | `PropTypes.arrayOf(PropTypes.number).isRequired,` |
| `ptoo→`  | `PropTypes.objectOf(PropTypes.number),` |
| `ptoor→` | `PropTypes.objectOf(PropTypes.number).isRequired,` |
| `ptoos→` | `PropTypes.objectOf(PropTypes.shape()),` |
| `ptoosr→`| `PropTypes.objectOf(PropTypes.shape()).isRequired,` |
| `ptsh→`  | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}),` |
| `ptshr→` | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}).isRequired,` |
