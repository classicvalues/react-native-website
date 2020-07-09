---
id: version-0.63-running-on-simulator-ios
title: Running On Simulator
original_id: running-on-simulator-ios
---

## Starting the simulator

Once you have your React Native project initialized, you can run `npx react-native run-ios` inside the newly created project directory. If everything is set up correctly, you should see your new app running in the iOS Simulator shortly.

## Specifying a device

You can specify the device the simulator should run with the `--simulator` flag, followed by the device name as a string. The default is `"iPhone 11"`. If you wish to run your app on an iPhone SE, run `npx react-native run-ios --simulator="iPhone SE"`.

The device names correspond to the list of devices available in Xcode. You can check your available devices by running `xcrun simctl list devices` from the console.