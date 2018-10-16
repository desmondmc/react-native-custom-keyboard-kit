
# react-native-custom-keyboard-kit

## Getting started

`$ npm install react-native-custom-keyboard-kit --save`

### Mostly automatic installation

`$ react-native link react-native-custom-keyboard-kit`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-custom-keyboard-kit` and add `RNCustomKeyboardKit.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNCustomKeyboardKit.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNCustomKeyboardKitPackage;` to the imports at the top of the file
  - Add `new RNCustomKeyboardKitPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-custom-keyboard-kit'
  	project(':react-native-custom-keyboard-kit').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-custom-keyboard-kit/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-custom-keyboard-kit')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNCustomKeyboardKit.sln` in `node_modules/react-native-custom-keyboard-kit/windows/RNCustomKeyboardKit.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Custom.Keyboard.Kit.RNCustomKeyboardKit;` to the usings at the top of the file
  - Add `new RNCustomKeyboardKitPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNCustomKeyboardKit from 'react-native-custom-keyboard-kit';

// TODO: What to do with the module?
RNCustomKeyboardKit;
```
  