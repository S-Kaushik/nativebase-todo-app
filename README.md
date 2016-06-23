## Native Starter - Starter Kit for [React Native](https://facebook.github.io/react-native/docs/getting-started.html) + [NativeBase](http://nativebase.io/) + [Redux](http://redux.js.org) + [CodePush](https://github.com/Microsoft/react-native-code-push) Apps (iOS & Android)

[![Join the chat at https://gitter.im/start-react/native-starter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/start-react/native-starter?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


![Native-Starter-Kit](/Screenshots/logo.png)


#### A simple starter project for [React Native](https://facebook.github.io/react-native/docs/getting-started.html) + [NativeBase](http://nativebase.io/) + [Redux](http://redux.js.org) + [React Native Navigator](https://facebook.github.io/react-native/docs/navigator.html) apps on iOS and Android.

No need of reinventing the wheel. To have immediately something to continue building on, it would be best to start from some starter kit for getting React Native - based applications off the ground in a hurry. 

This is a starter kit that you can install on the fly to get the basic plumping of React Native with NativeBase, Redux and CodePush. 

*Find out more [Free React.js and React Native Themes at StartReact.com](http://www.startreact.com/).*

# Content

-	[Screens](#screens)
-	[Technologies](#technologies)
-	[Installation](#installation)
-	[Featured Apps - Native Starter Pro](#featured-apps---native-starter-pro)


## Screens

 iOS | Android 
 :--:| :-----: 
 ![iOS-demo](/Screenshots/iOS-demo.gif) | ![android-demo](/Screenshots/android-demo.gif) 


## Technologies
*Technologies used in Native Starter Kit*

### [React Native](https://github.com/facebook/react-native)
React Native helps in making the development work easier and allowing the developers to focus on the core app features in every new release. It is the fastest-developing mobile app development that essentially permits you to create an isolated product with often outcomes.

**The hymn of React Native — learn once, write anywhere.**

React Native takes charge of the view controllers and programatically generates native views using javascript. This means that you can have all the speed and power of a native application, with the ease of development that comes with React.


### [NativeBase](nativebase.io)

NativeBase is a free and open source framework that enables developers to build high-quality mobile apps using React Native iOS and Android apps with a fusion of ES6. NativeBase builds a layer on top of React Native that provides you with basic set of components for mobile application development. 

The applications stack of components is built using native UI components and because of that, there are no compromises with the User Experience of the applications.  NativeBase is targeted specially on the look and feel, and UI interplay of your app. 

NativeBase without a doubt fits in well with mobile applications which cut downs one huge part of your app The Front end.

-	*[On GitHub](https://github.com/GeekyAnts/NativeBase)*
-	*[NativeBase Features](http://nativebase.io/documentation)*
-	*[NativeBase Components](http://nativebase.io/components)*


### [Redux](http://redux.js.org)

As the requirements for JavaScript single-page applications have become increasingly complicated, our code must manage more state than ever before. UI state is also increasing in complexity, as we need to manage the active route, the selected tab, whether to show a spinner or not, should pagination controls be displayed, and so on.

Redux is a predictable state container for JavaScript apps. It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. 

Redux attempts to make state mutations predictable by imposing certain restrictions on how and when updates can happen. These restrictions are reflected in the steps of three.

-	The **state** of whole application is stored in an object tree within a single **store**.
-	The only way to mutate the state is to emit an **action**, an object describing what happened.
-	To specify how the state tree is transformed by actions, you write pure **reducers**.


### [CodePush](https://github.com/Microsoft/react-native-code-push)

React Native app is composed of JavaScript files, images, which are bundled together by the packager and distributed as part of a platform-specific binary (i.e. an .ipa or .apk file). Once the app is released, updating either the JavaScript code or image assets, requires you to recompile and redistribute the entire binary.

The CodePush plugin helps get product improvements in front of your end users instantly, with the aid of preserving your javascript and images synchronized with updates you launch to the CodePush server. This way, your app gets the benefits of an offline mobile experience, as well as the "web-like" agility of side-loading updates as soon as they are available.




## Installation
####1. Clone this project or Download that ZIP file

```sh
$ git clone https://github.com/start-react/native-starter-kit.git
```

####2.  Make sure you have [npm](https://www.npmjs.org/) installed globally

More details here
https://nodejs.org/en/download/ 

####3. On the command prompt run the following commands

```sh
$ cd native-starter-kit/

$ npm install

$ rnpm link
```

####4. Simulate for iOS

**To Run the project using XCode**

*	Open the project in XCode from ios/NativeStarter.xcodeproj

*	[CodePush](https://github.com/Microsoft/react-native-code-push) plugin installation:

	*	Go to **"Build Phases"** tab of your project configuration.

	*	Click **"+"** underneath the **"Link Binary With Libraries"** list and select the **libz.tbd** library underneath the iOS node that matches your target version.

	![CodePush-plugin-installation](/Screenshots/codepush-plugin-installation.png)

*	Hit the play button.


####5. Simulate for Android

Run the following command from terminal

```sh
$ react-native run-android
```

## Featured Apps - Native Starter Pro
Having tried with the free version, Native Starter Kit and appreciate our product?

Get on the mobile fast track with [Native Starter Pro](http://strapmobile.com/native-starter-pro/), to build high-quality iOS and Android mobile apps. 

**Work in progress. Stay tuned!**
