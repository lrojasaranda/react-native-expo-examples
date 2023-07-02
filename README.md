# react-native-expo-examples

## Navigation
### Installation
```bash
npm install @react-navigation/native
npm install react-native-gesture-handler
npm install react-native-reanimated
npm install react-native-screens
npm install react-native-safe-area-context
npm install @react-native-community/masked-view
```

```bash
npm install @react-navigation/stack
```
### Usage

```bash
npm install @react-navigation/drawer
```

```bash
npm install @react-navigation/bottom-tabs
```

```babel.config.js
#agregar plugin reanimated
module.exports = function(api) {
  api.cache(true);
  return {
    presets: ['babel-preset-expo'],
    plugins: [
      'react-native-reanimated/plugin',
    ],
    
  };
};
```