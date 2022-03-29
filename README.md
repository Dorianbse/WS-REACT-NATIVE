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

There are a couple of things you need to install to set up the environment for React Native. Here, we are using Expo to test easily our application on a device.

#### Step1 - Install NPM and NodeJS
- NodeJS and NPM, https://docs.npmjs.com/downloading-and-installing-node-js-and-npm

#### Step2 - Install expo cli

After installing NodeJS and NPM successfully in your system:

- `npm install -g expo-cli`

#### Step3 - Create project

- `expo init MyReactNativeApp`

After executing the above command, a folder with specifies name is created.

#### Step4 - Start react native

To verify the installation browse through the project folder and try starting the project
using the start command.

- `cd MyReactNativeApp`
- `npm start` or `expo start`

If everything went well you will get a QR code.

One way to run react native apps on your android devise is to using expo.
Install expo client in your devise and scan the obtained QR code.

Now that you have successfully run the app, let's modify it. Open `App.js` in your text editor of choice and edit some lines. The application should reload automatically once you save your changes.

## 3. React Native – Get started

### EX1 - Hello World!

Inside of the square render the text "Hello, world".

Helpful links: [View](https://reactnative.dev/docs/view), [Text](https://reactnative.dev/docs/text), [StyleSheet](https://reactnative.dev/docs/stylesheet)

![image](https://user-images.githubusercontent.com/76050470/160011671-a3875487-66df-465b-b99a-abb501d78f4e.png)

### EX2 - Capturing Taps

The most basic form of interaction is capturing a user's tap (or press) on a screen.
Using the Button component, capture a tap event and alert "Hello".

Helpful links: [Button](https://reactnative.dev/docs/button), [TouchableOpacity](https://reactnative.dev/docs/touchableopacity)

### EX3 - Custom Component

Previously we've been exclusively using component from React Native. 

Build your own button component that accepts an onPress and text prop. Use the TouchableOpacity and Text components to accomplish this.

### EX4 - State & Props

We've taken a look at props previously - props allow us to pass data down to a component to interact with it.
These props can be static values or dynamic. What we haven't used is state. 
State allows us to track changing values and update our UI automatically when they change.

Using state track how many times a user presses the button and display that number.

Helpful links: [Use state hooks ](https://reactjs.org/docs/hooks-state.html), [Introducing Hooks](https://reactjs.org/docs/hooks-intro.html)

![image](https://user-images.githubusercontent.com/76050470/160016262-3b3aa8f0-554b-4fa7-98ff-3898f3ff2e00.png)

### EX5 - Styling

React Native follows the same principles of CSS.

 Create 3 squares that are vertically and horizontally centered.
 Each square should have a unique background color but all shared styles should only be defined once.
 
 Helpful links: [StyleSheet](https://reactnative.dev/docs/stylesheet), [FlexBox](https://reactnative.dev/docs/flexbox)
 
 ![image](https://user-images.githubusercontent.com/76050470/160016582-1957152a-ee99-4985-9b8f-d61b2aacfe76.png)

### EX6 - Scrollable Content

Render 15 squares in a scrollable list.

Helpful links: [ScrollView](https://reactnative.dev/docs/scrollview), [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html#keys)

![image](https://user-images.githubusercontent.com/76050470/160016788-3e794fbd-3671-443b-ab6e-9109d9f156c0.png)

### EX7 - Building a Form

Using the `TextInput` component capture a user's name and, upon a button press, `alert` their name back to them. Add some style to the `TextInput` while you're.

Helpful links: [TextInput](https://reactnative.dev/docs/textinput)

### EX8 - Long Lists & working with an API

When you have longs lists of data the ScrollView component won't cut it - it's just not built for it.

Render the array of people using the `FlatList` component.

Like a web browser, React Native implements the `fetch` and `XMLHttpRequest` APIs.
This means that the same logic and packages we would use to fetch data in a web browser will work in React Native.

Fetch data from the `https://randomuser.me/api/?results=100&inc=name` url (it returns JSON) and render it in the `FlatList`.

Helpful links: [FlatList](https://reactnative.dev/docs/flatlist#docsNav), [SectionList](https://reactnative.dev/docs/sectionlist#docsNav), [Fetch API docs](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)

![image](https://user-images.githubusercontent.com/76050470/160017792-1740dbca-c5e3-4434-ad7c-a7b8eba00b30.png)

## 4. Let's build a register page

#### Step1 - Create the form

Now that you are able to create some compoenents and add style to them, create a register form with 2 inputs (email and pass word) and a button and add style to make it presentable.

There is an example:

![Capture d’écran 2022-03-29 141026](https://user-images.githubusercontent.com/75833671/160592728-c19d9dd5-e27f-4a5f-8981-1bd970d52b7f.png)

