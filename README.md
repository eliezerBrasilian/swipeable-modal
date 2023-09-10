
# swipeable-modal

A fully customizable swipeable modal



## Installation

Install on your project with npm

```bash
  npm i swipeable-modal react-native-gesture-handler
```
## Usage/Examples

```javascript
import React, {useState} from 'react';
import {View, Text} from 'react-native';
import SwipableModal from 'swipeable-modal';

function App() {
  const [visibilityOfSwipableModal, setVisibilityOfSwipableModal] =
    useState(true);

  return (
    <View
      style={{
        flex: 1,
        justifyContent: 'center',
        alignItems: 'center',
        backgroundColor: '#6082B6',
      }}>
      <Text style={{color: '#000', fontSize: 22}}>Testando modal</Text>
      <Text style={{color: '#000', fontSize: 22}}>Trying modal</Text>

      <SwipableModal
        visible={visibilityOfSwipableModal}
        disappearOnSwipingDown={false}
        height={250}>
        <Text style={{color: '#000'}}>Content of Modal</Text>
      </SwipableModal>
    </View>
  );
}

export default App;

```


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

# swipeable-modal

A fully customizable swipeable modal



## Installation

Install on your project with npm

```bash
  npm i swipeable-modal react-native-gesture-handler
```
## Usage/Examples

```javascript
import React, {useState} from 'react';
import {View, Text} from 'react-native';
import SwipableModal from 'swipeable-modal';

function App() {
  const [visibilityOfSwipableModal, setVisibilityOfSwipableModal] =
    useState(true);

  return (
    <View
      style={{
        flex: 1,
        justifyContent: 'center',
        alignItems: 'center',
        backgroundColor: '#6082B6',
      }}>
      <Text style={{color: '#000', fontSize: 22}}>Testando modal</Text>
      <Text style={{color: '#000', fontSize: 22}}>Trying modal</Text>

      <SwipableModal
        visible={visibilityOfSwipableModal}
        disappearOnSwipingDown={false}
        height={250}>
        <Text style={{color: '#000'}}>Content of Modal</Text>
      </SwipableModal>
    </View>
  );
}

export default App;

```


## Screenshots

![image](https://github.com/eliezerBrasilian/swipeable-modal/assets/93846923/922d4145-877b-4791-84c1-e7a18285272e)

## Simple video of example

https://github.com/eliezerBrasilian/swipeable-modal/assets/93846923/6ee96693-76bd-49a2-a39b-8e559bcb826a



