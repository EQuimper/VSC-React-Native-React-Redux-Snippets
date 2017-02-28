## Snippets List

| Snippets | Content |
| -------: | --------|
| imr | Import React |
| imrc | Import React Component |
| imrn | Import React-Native Element |
| rct | Redux constant |
| ccr | Connect Redux |
| sl | Stateless Component |
| slc | Stateless Component Function |
| ccs | Component Class |
| rrd | Redux Reducer |
| cwm | ComponentWillMount |
| cdm | ComponentDidMount |
| cwu | ComponentWillUpdate |
| ess | EStyleSheet Style |
| ed | Export default |
| edl | EslintDisableLine |

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

## rct [Redux Constant]

```js
export const $1 = '$1';
```

---

## ccr [Connect Redux]

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

## cwm [ComponentWillMount]

```js
componentWillMount() {
  $1
}
```

## cwu [ComponentWillUpdate]

```js
componentWillMount() {
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

## edl

```js
// eslint-disable-line
```