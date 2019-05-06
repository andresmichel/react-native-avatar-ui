# react-native-avatar

## Getting Started

- [Installation](#installation)
- [Basic Usage](#basic-usage)
- [Properties](#properties)

### Installation

```bash
$ npm i react-native-avatar --save
```

### Basic Usage

- Install `react-native` first

```bash
$ npm i react-native-cli -g
```

- Initialization of a react-native project

```bash
$ react-native init myproject
```

- Then, edit `myproject/index.ios.js`, like this:

```jsx
import React, { Component } from 'react';
import {
  AppRegistry,
  Text,
  View
} from 'react-native';

import Avatar from 'react-native-avatar';

export default class Swiper extends Component {
  render() {
    return <Avatar size={64} letter={'A'} source={require('./assets/picture.jpg')} />;
  }
}

AppRegistry.registerComponent('myproject', () => Swiper);
```

### Properties

| Prop  | Default  | Type | Description |
| :------------ |:---------------:| :---------------:| :-----|
| size | 64 | `number` | Size for this component. |
| letter | "" | `string` | Placeholder letter |
| source | undefined | `string` | The image source (either a remote URL or a local file resource). |
