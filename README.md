# Install React Native CLI

## The React Native CLI
 Node comes with `npm` which lets you install the React Native command line interface.
 
 Run the following command in a command prompt or shell:
 ```
 npm install -g react-native-cli
 ```
 > If you get an error like `Cannot find module 'npmlog'`, try installing `npm` directly: `curl -0 -L https://npmjs.org/install.sh | sudo.sh`.

 ### Android development environment

 Setting up your development environment can be somewhat tedious if you're new to Android development. If you're already familiar with Android development, there are a few things you may need to configure. In either case, please make sure to carefully follow the next few steps.

 ##### 1. Install Android Studio

 [Download and install Android Studio](https://developer.android.com/studio/index.html). Choose a "Custom" setup when prompted to select an installation type. Make sure the boxes next to all of the following are checked:

 + `Android SDK`
 + `Android SDK Platform`
 + `Performance (Install  HAXM)`
 + `Android Virtual Device`

 Then, click "Next" to install all of these components.

> If the checkboxes are grayed out, you will have a chance to install these components later on.

Once setup has finalized and you're presented with the Welcome screen, proceed to the next step.

The SDK is installed, by default, at the following location:
```
c:\Users\YOUR_USERNAME\AppData\Local\Android\Sdk
```
The default location for this folder is:
```
c:\Users\YOUR_USERNAME\AppData\Local\Android\Sdk\platform-tools
```
##### Install yarn (optional)

```
npm install -g yarn
```
### Create New Project

``` 
react-native init mysampleapp
```
#### Thank you for read this file.
