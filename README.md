# WebrtcAndroid

This is an Android Studio reference project for WebRTC based video and voice calling app.

## build

* date:2022/06/30
* version: branch-heads/5060


gn configuration is：

```shell
gn gen out/Debug/arm --args='target_os="android" target_cpu="arm"'
gn gen out/Debug/arm64 --args='target_os="android" target_cpu="arm64"'
```

```shell
autoninja -C out/Debug/arm
autoninja -C out/Debug/arm64
```
