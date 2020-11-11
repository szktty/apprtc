# AppRTC (iOS, Android)

WebRTC のソースコードに含まれるサンプルアプリケーション AppRTC を Xcode と Android Studio でビルドできるようにしたものです。

libwebrtc のバイナリは次のリポジトリで配布されているものを使っています。

- iOS: https://github.com/shiguredo/sora-ios-sdk-specs
- Android: https://github.com/shiguredo/shiguredo-webrtc-android


## 注意

サンプルのソースコードは Xcode / Android Studio でビルド・実行する最小限しか変更していません。
**動作は保証しません。クラッシュして全然使えない可能性もあります。ご理解ください。**


## システム条件

以下はテストに使った環境です。


### iOS

- iOS 14+
- Xcode 12+
- Swift 5.3+


### Android

- Android 11+
- Android Studio 4.0+


## ビルドの手順

### iOS

1. `iOS` ディレクトリで `pod install` を実行する

2. `AppRTC.xcworkspace` を開く

3. コード署名を自分のものに変更する

4. ビルド


### Android

1. Android Studio で `Android` ディレクトリをインポートする

2. ビルド

