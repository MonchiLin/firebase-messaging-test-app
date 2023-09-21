# 这是哪里?

这里是用于测试 @react-native-firebase/messaging 与 expo 集成的测试仓库.

## 如何检查集成结果

1. 安装依赖

```
yarn
```

2. 编译 expo-dev-client

```
yarn prebuild
```

3. 验证结果

打开 `android/app/src/main/AndroidManifest.xml`

可以看到 `com.google.firebase.messaging.default_notification_icon` 和 `com.google.firebase.messaging.default_notification_color (如果设置了 notification.color)` 被正确添加了. 

