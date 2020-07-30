# Create Project
```bash
npx expo-cli init project_name
```

# React Navigation

1. Install React Navigation
```bash
npm install react-navigation
```

2. Install Dependencies
```bash
expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
```

3. Install React Navigation Stack
```bash
npm install react-navigation-stack @react-native-community/masked-view
```

4. Install React Navigation Tabs
```bash
npm install react-navigation-tabs
```

5. Start the app and clear cache with 
```bash
expo r -c
```

## Update Imports
Our imports in the upcoming lecture "Navigator Hookup" will now look like this:

```python
import { createAppContainer, createSwitchNavigator } from 'react-navigation';
import { createStackNavigator } from 'react-navigation-stack';
import { createBottomTabNavigator } from 'react-navigation-tabs';
```

## React Navigation v4 Docs:
[Link](https://reactnavigation.org/docs/4.x/getting-started)