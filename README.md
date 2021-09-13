# Project Name:
Chat App (a React Native chat application)

# Project Objective:
To build a chat app for mobile devices using React Native. The app will provide users with a chat interface and options to share images and their
location.

# Technologies used:
* React Native & Expo (to set-up development environment)
* Firebase (to authenticate users and store conversations)

# Key Features:
* A page where users can enter their name and choose a background color for the chat screen before joining the chat.
* A page displaying the conversation, as well as an input field and submit button.
* The chat must provide users with two additional communication features: sending images and location data.
* Data gets stored online and offline.

# Technical Requirements:
* The app must be written in React Native.
* The app must be developed using Expo.
* The app must be styled according to the given screen design.
* Chat conversations must be stored in Google Firestore Database.
* The app must authenticate users anonymously via Google Firebase authentication.
* Chat conversations must be stored locally.
* The app must let users pick and send images from the phone’s image library.
* The app must let users take pictures with the device’s camera app, and send them.
* The app must store images in Firebase Cloud Storage.
* The app must be able to read the user’s location data.
* Location data must be sent via the chat in a map view.
* The chat interface and functionality must be created using the Gifted Chat library.
* The app’s codebase must contain comments.

# Getting Started

## Requirements
* Node.js
* Expo Command Line Interface (CLI)

`npm install --global expo-cli`

## Setup
Clone the repo or download the files, and install dependencies

`npm install`
## UI lirary

`npm install react-native-gifted-chat --save`

## Run the App
To get the app running use:

`expo start`
NOTE: You will need to setup an account with Expo before you can view your app and get it up and running.

## Viewing the application
You can run this application on your mobile device by downloading the Expo app from your app store.
Alternatively you can run IOS Simulator through XCode or Android Studio.

NOTE: You will need to setup your own firebase database and add your own database credentials in /components/chat.js, under the "Firebase Config Details", then allow anonymous authorization with your Database.
