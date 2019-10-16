# react-native-tcpip

## Getting started

`$ npm install react-native-tcpip --save`

### Mostly automatic installation

`$ react-native link react-native-tcpip`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-tcpip` and add `Tcpip.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libTcpip.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.TcpipPackage;` to the imports at the top of the file
  - Add `new TcpipPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-tcpip'
  	project(':react-native-tcpip').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-tcpip/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-tcpip')
  	```


## Usage
```javascript
import Tcpip from 'react-native-tcpip';

// TODO: What to do with the module?
Tcpip;
```
