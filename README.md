[![](https://img.shields.io/badge/Supported%20by-VSCode%20Power%20User%20Course%20%E2%86%92-gray.svg?colorA=655BE1&colorB=4F44D6&style=for-the-badge)](https://a.paddle.com/v2/click/16413/111518?link=1227)
[![Version](https://vsmarketplacebadge.apphb.com/version-short/EQuimper.react-native-react-redux.svg)](https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux)
[![Install](https://vsmarketplacebadge.apphb.com/installs-short/EQuimper.react-native-react-redux.svg)](https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/EQuimper.react-native-react-redux.svg)](https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux)

# No Semicolon ?

For the version without semi-colon look this one https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux-snippets-for-es6-es7-version-standard

## Usage

After install this snippets add this inside your settings

`"editor.snippetSuggestions": "top",`

## Snippets List

| Snippets | Content                              |
| -------: | ------------------------------------ |
| imr      | Import React                         |
| imro     | Import React as Object               |
| imrc     | Import React Component               |
| imrpc    | Import React PureComponent           |
| imrn     | Import React-Native Element          |
| ims      | Import Styled-Components             |
| imsn     | Import Styled-Components Native      |
| impt     | Import PropTypes                     |
| rct      | Redux constant                       |
| crr      | Connect Redux                        |
| sl       | Stateless Component                  |
| slr      | Stateless Component Return           |
| slc      | Stateless Component Function         |
| ccs      | Component Class                      |
| cccs     | Component Class With Constructor     |
| ccsf     | Component Class FlowType             |
| pcs      | PureComponent Class                  |
| pccs     | PureComponent Class With Constructor |
| pcsf     | PureComponent FlowType               |
| ccsr     | Component Class With Redux           |
| edccs    | Export default Component Class       |
| rrd      | Redux Reducer                        |
| rpf      | Redux Pure Function                  |
| rpc      | Redux Pure Function Const            |
| cwm      | ComponentWillMount                   |
| cdm      | ComponentDidMount                    |
| cdu      | ComponentDidUpdate                   |
| scu      | ShouldComponentUpdate                |
| cwu      | ComponentWillUpdate                  |
| cwum     | ComponentWillUnmount                 |
| cwrp     | ComponentWillReceiveProps            |
| cdc      | ComponentDidCatch                    |
| cct      | Create Context                       |
| gds      | getDerivedStateFromProps             |
| rnss     | StyleSheet Style                     |
| ess      | EStyleSheet Style                    |
| ed       | Export default                       |
| edl      | EslintDisableLine                    |
| ednl     | EslintDisableNextLine                |
| styc     | Styled Component                     |
| estyc    | Export Styled Component              |
| edstyc   | Export default Styled Component      |
| cmmb     | Comment Big Block                    |
| log      | Console Log                          |
| cl       | Standard console.log                 |
| tt       | Test                                 |
| tdesc    | Test Describe                        |
| tit      | Test It                              |
| ffm      | FlowFixMe                            |
| rnstory  | React-Native Story                   |
| rstory   | React Story                          |
| rsf      | React Stateless Function             |

---

# imr [Import React]

```js
import React from 'react';
```

---

# imro [Import React as Object]

```js
import * as React from 'react';
```

---

## imrc [Import React Component]

```js
import React, { Component } from 'react';
```

---

## imrpc [Import React PureComponent]

```js
import React, { PureComponent } from 'react';
```

---

## imrn [Import React-Native Element]

```js
import { $1 } from 'react-native';
```

---

## ims [Import Styled-Components]

```js
import styled from 'styled-components';
```

---

## imsn [Import Styled-Components Native]

```js
import styled from 'styled-components/native';
```

---

## impt [Import PropTypes]

```js
import PropTypes from 'prop-types';
```

---

## rct [Redux Constant]

```js
export const $1 = '$1';
```

---

## crr [Connect Redux]

```js
import { connect } from 'react-redux';
```

---

## sl [Stateless Component]

```js
const $1 = () => (
  $2
);

export default $1;
```

---

## slr [Stateless Component Return]

```js
const $1 = () => {
  return (
    $2
  );
}

export default $1;
```

---

## slc [Stateless Component Function]

```js
function $1($2) {
  $3
}

export default $1;
```

---

## ccs [Component Class]

```js
class $1 extends Component {
  state = { $2 }
  render() {
    return (
      $3
    );
  }
}

export default $1;
```

---

## cccs [Component Class With Constructor]

```js
class $1 extends Component {
  constructor(props) {
    super(props);
    this.state = { $2 };
  }
  render() {
    return (
      $3
    );
  }
}

export default $1;
```

---

## ccsf [Component Class FlowType]

```js
type P = {
  $1
};

type S = {
  $2
};

class $3 extends Component<P, S> {
  constructor(props) {
    super(props);
    this.state = { $4 };
  }
  render() {
    return (
      $5
    );
  }
}

export default $3;
```

---

## pcs [PureComponent Class]

```js
class $1 extends PureComponent {
  state = { $2 }
  render() {
    return (
      $3
    );
  }
}

export default $1;
```

---

---

## pccs [PureComponent Class With Constructor]

```js
class $1 extends PureComponent {
  constructor(props) {
    super(props);
    this.state = { $2 };
  }
  render() {
    return (
      $3
    );
  }
}

export default $1;
```

---

## pcsf [PureComponent Class FlowType]

```js
type P = {
  $1
};

type S = {
  $2
};

class $3 extends PureComponent<P, S> {
  constructor(props) {
    super(props);
    this.state = { $4 };
  }
  render() {
    return (
      $5
    );
  }
}

export default $3;
```

---

## ccsr [Component Class With Redux]

```js
class $1 extends Component {
  state = { $2 }
  render() {
    return (
      $3
    );
  }
}

export default connect($4, $5)($1);
```

---

## edccs [Export default Component Class]

```js
export default class $1 extends Component {
  state = { $2 }
  render() {
    return (
      $3
    );
  }
}
```

---

## rrd [Redux Reducer]

```js
export default (state = $1, action) => {
  switch (action.type) {
    case $2:
      $3
    default:
      return state;
  }
};
```

---

## rpf [Redux pure function]

```js
export const $1 = '$1';

export function $2($3) {
  return {
    type: $1,
    $3
  }
}
```

---

## rpc [Redux pure function const]

```js
export const $1 = '$1';

export const $2 = $3 => ({
  type: $1,
  $3
});
```

---

## cwm [ComponentWillMount]

```js
componentWillMount() {
  $1
}
```


## cwu [ComponentWillUpdate]

```js
componentWillUpdate() {
  $1
}
```

---

## cdu [ComponentDidUpdate]

```js
componentDidUpdate(prevProps, prevState) {
  $1
}
```

---

## scu [ShouldComponentUpdate]

```js
shouldComponentUpdate(nextProps, nextState, nextContext) {
  $1
}
```

---

## cdm [ComponentDidMount]

```js
componentDidMount() {
  $1
}
```

---

# cwum [ComponentWillUnmount]

```js
componentWillUnmount() {
  $1
}
```

---

# cwrp [ComponentWillReceiveProps]

```js
componentWillReceiveProps(nextProps) {
  $1
}
```

---

# cdc [ComponentDidCatch]

```js
componentDidCatch(error, info) {
  $1
}
```

---

# cct [Create Context]

```js

const $1Context = createContext($2);

class $1Provider extends Component {
  state = {
    $3
  }

  render() {
    return (
      <$1Context.Provider value={{ state: { $3 }, actions: {} }}>
        {this.props.children}
      </$1Context.Provider>
    );
  }
}

export default $1Provider;
```

---

# gds [getDerivedStateFromProps]

```js
static getDerivedStateFromProps(nextProps, prevState) {
  $1
}
```

---

# rnss [StyleSheet Style]

```js
const styles = StyleSheet.create({
  $1
});
```

---

# ess [EStyleSheet]

```js
import EStyleSheet from 'react-native-extended-stylesheet';

const styles = EStyleSheet.create({
  $1
});

export default styles;
```

---

## ed [Export default]

```js
export default $1;
```

---

## edl [Eslint Disable Line]

```js
// eslint-disable-line
```

---

## ednl [Eslint Disable Next Line]

```js
// eslint-disable-next-line
```

---

## styc [Styled Component]

```js
const $1 = styled.$2`
  $3
`
```

---

## estyc [Export Styled Component]

```js
export const $1 = styled.$2`
  $3
`
```

## edstyc [Export default Styled Component]

```js
export default styled.$1`
  $2
`
```

## cmmb [Comment Big Block]

```js
/**
|--------------------------------------------------
| $1
|--------------------------------------------------
*/
```

---

## log [Console Log]

```js
console.log('====================================');
console.log($1);
console.log('====================================');
```

---

## cl [Standard console.log]

```js
console.log($1);
```

---

## tt [Test]

```js
test('$1', () => {
  $2
});
```

---

## tdesc [Test Describe]

```js
describe('$1', () => {
  $2
});
```

---

## tit [Test It]

```js
it('should $1', $2($3) => {
  $4
});
```

---

## ffm [FlowFixMe]

```js
// $FlowFixMe
```

---

## rnstory [React-Native Story]

```js
import React from 'react';
import { storiesOf } from '@storybook/react-native';

storiesOf('$1', module)
  .add('default', () => $2);
```

---

## rstory [React Story]

```js
import React from 'react';
import { storiesOf } from '@storybook/react';

storiesOf('$1', module)
  .add('default', () => $2);
```

---


## rue [React useEffect]

```js
React.useEffect(() => {
  $1
}, []);
```

---

## rsf [React Stateless Function]

```js
import React from "react";

function $1(props) {
  return (
    <div>

    </div>
  );
}

export default $1;
```

---
