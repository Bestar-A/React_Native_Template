# React Native Template

This is `React Native Template` created by `BestarDev`.  
I want to build this project by online eas build.  

## Installation
Refer this *installation* process  
### - For Local Project
```
npm install
```
### - For Global Node Env
```
npm install --global expo-cli eas-cli
```

## Preview
After install all neccessary npm packages, then you will type this command to get preview screen.  
```
npm start
```
If you encouter some network issue while connecting to expo site, then use this command to work offline mode.  
```
npm start --offline
```
You can use `yarn` instead of `npm`.  
After executing this command, then you will power on an `Android Emulator` (like Android Studio Emulator, Memu, Momo, GenyMotion, Nox and so on). And then you must install `Expo Go` App on this emulator. You can download `Expo Go` App [here](https://d1ahtucjixef4r.cloudfront.net/Exponent-2.30.11.apk) or Refer [here](https://expo.dev/tools).  
After power on the emulator, then you will press *simple* `a` key in the command prompt. Before press `a` key in the command prompt, this CMD will be waiting for your key press.  
This is the screen you will get after execute the above command.  
<img src='./assets/Screen.jpg'/>

## Requirement
I have some network issue to build this project for android. I think `expo` is the most convenient way to **Create** *React Native App* and **Build** without any issue like `gradle` or any other stuff. But `expo` only works online and build the project online too. I have been faced with network issue as build this project.
### Build Step
You can use `expo` or `eas` build command, because you have already installed `expo-cli` and `eas-cli`.
> **Be aware of this!**  
You can use `expo build` command for Android SDK 47 or older, but you must use `eas build` command for SDK 47 or above. So I want to recommend `eas build` command for this project.

Follow these steps to build this project.  
- Login to Expo and Connect with VS Code
  ```
  expo login
  ```
  And then you can type Email or Username and Password for expo account. If you don't have expo account, then you must login and verify. Adn then you can use this email and password for the above.
  > **Be aware of this!**
  You should use Command Prompt instead of PowerShell. If you use PowerShell, you might get `sign issue` when using `expo` or `eas` command.
  
- Build by EAS CLI
```
eas build -p android
```
After building this project, I think you can get the final `APK` file to your expo account. I want to confirm this and get the final standalone `APK` file.  
I will be gald if you complete this final `Requirement Step`.
