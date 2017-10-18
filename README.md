# expo-file-system-view
Drop-in component for viewing your expo app file system.
---
`npm install expo-file-system-view`

## Simple use case
Clone this repo to see an example with dummy files
OR
drop it in your own app:
```javascript
import React from 'react'
import { View } from 'react-native'
import FileSystemView from 'expo-file-system-view'

export default class App extends React.Component {
  render () {
    return (
      <View>
        <FileSystemView />
      </View>
    )
  }
}
```
