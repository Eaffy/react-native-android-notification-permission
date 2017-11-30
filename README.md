# react-native-android-notification-permission
### 判断 Android 设备是否开启远程通知——check for notification permission of Android device
#### Installing
`npm install react-native-android-notification-permission --save`
#### Lingking Native Dependencies
`react-naitve link react-native-android-notification-permission`
#### Usage
`import RNAndroidNotificationPermission from 'react-native-android-notification-permission';`
```
async _checkAndroidNotificationPermission () {
    const permissions = await RNAndroidNotificationPermission.checkNoticficationPermission();
    console.log(permissions);
}
```
#### API
* checkNoticficationPermission()
