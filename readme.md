# What's This?

This repository serves as a test environment for verifying the integration of @react-native-firebase/messaging with Expo.

## How to Check the Integration Result

1. Install Dependencies:

``` 
yarn --check-cache
```

2. Compile the expo-dev-client:

```
yarn prebuild
```

3. Verify the Result:

Open `android/app/src/main/AndroidManifest.xml`.

You can observe that `com.google.firebase.messaging.default_notification_icon` and `com.google.firebase.messaging.default_notification_color (if notification.color is set)` are added correctly.

4. Test Notification Icon (Optional):

4.1 Build & install the app using `yarn run android`.
4.2 Enable notification permissions.
4.3 Open the [firebase-messaging-test-app] app (which uses expo-notifications, but you can switch to firebase-messaging).
