# REACT-NATIVE

## 1. React-Native - Overview

React, letting you compose a rich mobile UI from declarative components.
With React Native, you don't build a mobile web app, an HTML5 app, or a hybrid app; you build a real
mobile app that's indistinguishable from an app built using Objective-C or Java.
React Native uses the same fundamental UI building blocks as regular iOS and Android apps.
You just put those building blocks together using JavaScript and React.

#### React Native Features

- React – This is a Framework for building web and mobile apps using JavaScript.
- Native − You can use native components controlled by JavaScript.
- Platforms – React Native supports IOS and Android platform.

#### React Native Advantages

- JavaScript − You can use the existing JavaScript knowledge to build native mobile apps.
- Code sharing − You can share most of your code on different platforms.
- Community – The community around React and React Native is large, and you will be able to find any answer you need


Developed by Facebook in 2015 and used by major players in the of the application market such as
Airbnb, SoundCloud or Instagram, this framework is widely acclaimed and recognized for its robustness.


<p align="center">
  <img src="https://user-images.githubusercontent.com/76050470/159978481-24fbf9b1-e2ed-4a44-b0b9-0744109c9ce8.png"/>
</p>

## 2. Environment Setup

There are a couple of things you need to install to set up the environment for React Native.

#### Step1 - Install NPM and NodeJS
- NodeJS and NPM, https://docs.npmjs.com/downloading-and-installing-node-js-and-npm

#### Step2 - Install create-react-native-app

After installing NodeJS and NPM successfully in your system:

- `npm install -g create-react-native-app`

#### Step3 - Create project

- `create-react-native-app MyReactNativeApp`

After executing the above command, a folder with specifies name is created.

#### Step4 - NodeJS Python Jdk8

Make sure you have Python NodeJS and jdk8 installed in your system if not, install them.
In addition to these it is recommended to install latest version of yarn to avoid certain issues.

#### Step 5 - Install React Native CLI

Install react native command line interface on npm, using the install -g reactnative-cli command as shown below.

- `npm install -g react-native-cli`

#### Step6 - Start react native

To verify the installation browse through the project folder and try starting the project
using the start command.

- `cd MyReactNativeApp`
- `npm start`

If everything went well you will get a QR code.

One way to run react native apps on your android devise is to using expo.
Install expo client in your android devise and scan the obtained QR code.

#### Step7 For people who are not on android - 

If you want to run android emulator using android studio, come out of the current
command line by pressing ctrl+c.

Then, execute run eject command as:
- `npm run eject`

This prompts you options to eject, select the first one using arrows and press enter.

Then, you should suggest the name of the app on home screen and project name of the
Android studio and Xcode projects.

Though your project ejected successfully, you may get an error.

Ignore this error and run react native for android using the following command if you have setup AndroidStudio else setup it here.

-`react-native run-android`

#### Step8 - local.properties

Open the android folder in your project folder SampleReactNative/android (in this case).
Create a file with named local.properties and add the following path in it.

`sdk.dir = /C:\\Users\\YourUsername\\AppData\\Local\\Android\\Sdk`

Here, replace YourUsername with your user name.

#### Step9 - Hot Reloading

And to build application modify the App.js and the changes will be automatically updated on the android emulator.
If not, click on the android emulator press ctrl+m then, select Enable Hot Reloading option.

## 3. React Native – Get started

#### EX1 - Hello World!

Inside of the square render the text "Hello, world".

Helpful links: [View](https://reactnative.dev/docs/view), [Text](https://reactnative.dev/docs/text)

![image](https://user-images.githubusercontent.com/76050470/160011671-a3875487-66df-465b-b99a-abb501d78f4e.png)

#### EX2 - Capturing Taps

The most basic form of interaction is capturing a user's tap (or press) on a screen.
Using the Button component, capture a tap event and alert "Hello".

Helpful links: [Button](https://reactnative.dev/docs/button), [TouchableOpacity](https://reactnative.dev/docs/touchableopacity)

#### EX3 - Custom Component

Previously we've been exclusively using component from React Native. 

Build your own button component that accepts an onPress and text prop. Use the TouchableOpacity and Text components to accomplish this.

#### EX4 - State & Props

We've taken a look at props previously - props allow us to pass data down to a component to interact with it.
These props can be static values or dynamic. What we haven't used is state. 
State allows us to track changing values and update our UI automatically when they change.

Using state track how many times a user presses the button and display that number.

Helpful links: [Use state hooks ](https://reactjs.org/docs/hooks-state.html), [Introducing Hooks](https://reactjs.org/docs/hooks-intro.html)

![image](https://user-images.githubusercontent.com/76050470/160016262-3b3aa8f0-554b-4fa7-98ff-3898f3ff2e00.png)

#### EX5 - Styling

React Native follows the same principles of CSS.

 Create 3 squares that are vertically and horizontally centered.
 Each square should have a unique background color but all shared styles should only be defined once.
 
 Helpful links: [StyleSheet](https://reactnative.dev/docs/stylesheet), [FlexBox](https://reactnative.dev/docs/flexbox)
 
 ![image](https://user-images.githubusercontent.com/76050470/160016582-1957152a-ee99-4985-9b8f-d61b2aacfe76.png)

#### EX6 - Scrollable Content

Render 15 squares in a scrollable list.

Helpful links: [ScrollView](https://reactnative.dev/docs/scrollview), [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html#keys)

![image](https://user-images.githubusercontent.com/76050470/160016788-3e794fbd-3671-443b-ab6e-9109d9f156c0.png)

#### EX7 - Building a Form

Using the `TextInput` component capture a user's name and, upon a button press, `alert` their name back to them. Add some style to the `TextInput` while you're.

Helpful links: [TextInput](https://reactnative.dev/docs/textinput)

#### EX8 - Long Lists & working with an API

When you have longs lists of data the ScrollView component won't cut it - it's just not built for it.

Render the array of people using the `FlatList` component.

Like a web browser, React Native implements the `fetch` and `XMLHttpRequest` APIs.
This means that the same logic and packages we would use to fetch data in a web browser will work in React Native.

Fetch data from the `https://randomuser.me/api/?results=100&inc=name` url (it returns JSON) and render it in the `FlatList`.

Helpful links: [FlatList](https://reactnative.dev/docs/flatlist#docsNav), [SectionList](https://reactnative.dev/docs/sectionlist#docsNav), [Fetch API docs](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)

![image](https://user-images.githubusercontent.com/76050470/160017792-1740dbca-c5e3-4434-ad7c-a7b8eba00b30.png)



