[![Version](http://vsmarketplacebadge.apphb.com/version-short/EQuimper.react-native-react-redux.svg)](https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux)
[![Install](http://vsmarketplacebadge.apphb.com/installs-short/EQuimper.react-native-react-redux.svg)](https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux)
[![Ratings](http://vsmarketplacebadge.apphb.com/rating-short/EQuimper.react-native-react-redux.svg)](https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux)

# No Semicolon ?

For the version without semi-colon look this one https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux-snippets-for-es6-es7-version-standard

## Usage

After install this snippets add this inside your settings

`"editor.snippetSuggestions": "top",`

## Snippets List

| Snippets | Content |
| -------: | --------|
| imr | Import React |
| imrc | Import React Component |
| imrn | Import React-Native Element |
| ims | Import Styled-Components |
| imsn | Import Styled-Components Native |
| rct | Redux constant |
| crr | Connect Redux |
| sl | Stateless Component |
| slc | Stateless Component Function |
| ccs | Component Class |
| edccs | Export default Component Class |
| rrd | Redux Reducer |
| rpf | Redux Pure Function |
| rpc | Redux Pure Function Const |
| cwm | ComponentWillMount |
| cdm | ComponentDidMount |
| cdu | ComponentDidUpdate |
| cwu | ComponentWillUpdate |
| cwum | ComponentWillUnmount |
| cwrp | ComponentWillReceiveProps |
| ess | EStyleSheet Style |
| ed | Export default |
| edl | EslintDisableLine |
| styc | Styled Component |
| estyc | Export Styled Component |
| edstyc | Export default Styled Component |
| cmmb | Comment Big Block |
| log | Console Log |
| tdesc | Test Describe |
| tit | Test It |

---

# imr [Import React]

```js
import React from 'react';
```

---

## imrc [Import React Component]

```js
import React, { Component } from 'react';
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
