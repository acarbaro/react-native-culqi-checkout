
# react-native-culqi-checkout

## Getting started

`$ npm install react-native-culqi-checkout --save`

### Mostly automatic installation

`$ react-native link react-native-culqi-checkout`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-culqi-checkout` and add `RNCulqiCheckout.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNCulqiCheckout.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.shellmonger.reactnative.RNCulqiCheckoutPackage;` to the imports at the top of the file
  - Add `new RNCulqiCheckoutPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-culqi-checkout'
  	project(':react-native-culqi-checkout').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-culqi-checkout/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-culqi-checkout')
  	```


## Usage
```javascript
import RNCulqiCheckout from 'react-native-culqi-checkout';

// TODO: What to do with the module?
RNCulqiCheckout;
```
  