# What's This?

This is a test repository for testing the integration of @react-native-firebase/messaging with Expo.

## How to Check the Integration Result

1. Install Dependencies

``` 
yarn
```

2. Compile expo-dev-client

```
yarn prebuild
```

3. Verify the result

Open `android/app/src/main/AndroidManifest.xml`

You will see that `com.google.firebase.messaging.default_notification_icon` and `com.google.firebase.messaging.default_notification_color (if notification.color is set)` are correctly added.