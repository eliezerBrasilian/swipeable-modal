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

![image](https://github.com/eliezerBrasilian/swipeable-modal/assets/93846923/922d4145-877b-4791-84c1-e7a18285272e) ![image](https://github.com/eliezerBrasilian/swipeable-modal/assets/93846923/c1992c6a-6478-438c-8288-b95545f2823d)


## Simple video of example

https://github.com/eliezerBrasilian/swipeable-modal/assets/93846923/6ee96693-76bd-49a2-a39b-8e559bcb826a



## All the Props



| Parameter | Condition     | Description                |
| :-------- | :------- | :------------------------- |
| `children` | **Required**.  | View,Text,ScrollView, etc...|

| Parameter | Type| Description  |
| :-------- | :-------  | :---------------|
| `visible`  | **boolean**| control the visibility of modal |

| Parameter | Type| Description  |
| :-------- | :-------  | :---------------|
| `borderRadius`  | **number**| control the border of modal |

| Parameter | Type| Description  |
| :-------- | :-------  | :---------------|
| `borderColor`  | **string**| control the border color of modal |

| Parameter | Type| Description  |
| :-------- | :-------  | :---------------|
| `borderWidth`  | **number**| control the width of border of modal |

| Parameter | Type| Description  |
| :-------- | :-------  | :---------------|
| `height`  | **number**| control the minimum heigth of modal |

| Parameter | Type| Description  |
| :-------- | :-------  | :---------------|
| `disappearOnSwipingDown`  | **boolean**| control if modal should disappear after swiped down |


