![logo](https://cdn.lishaoy.net/flutterCtrip/iOS-andorid.png)

## 跨端(iOS/Android)移动应用创建携程App

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/persilee/flutter_ctrip?color=brightgreen)](https://github.com/persilee/flutter_ctrip/releases) [![author](https://img.shields.io/badge/author-persilee-orange.svg)](https://github.com/persilee) [![blog](https://img.shields.io/badge/blog-lishaoy.net-blue.svg)](https://h.lishaoy.net)

基于 **Flutter** 的跨平台(iOS/Android)移动应用创建携程App，高仿大厂 **App** 项目 *(项目使用的接口都是来自线上真实App抓包而来，可以做到和线上项目相同的效果)*

### 项目效果预览图

|![no-shadow](https://cdn.lishaoy.net/flutterCtrip/appBar.gif "appBar" )|![no-shadow](https://cdn.lishaoy.net/flutterCtrip/searchBar.gif "searchBar" )|
|:---:|:---:|
|![no-shadow](https://cdn.lishaoy.net/flutterCtrip/speak.gif "speak" )|![no-shadow](https://cdn.lishaoy.net/flutterCtrip/banner.gif "banner" )|
|![no-shadow](https://cdn.lishaoy.net/flutterCtrip/destination.gif "destination" )|![no-shadow](https://cdn.lishaoy.net/flutterCtrip/destination-search.gif "destination" )|
|![no-shadow](https://cdn.lishaoy.net/flutterCtrip/travel-search.gif "travel-search" )||

大家也可以，[移步这里点击观看视频](https://www.bilibili.com/video/BV16p4y1Q71f/) （可点击齿轮设置隐藏黑边）

或者安装体验(Android)：[[FCtrip.apk](https://github.com/persilee/flutter_ctrip/releases/download/V1.0.0-beta.1/app-release.apk)]，iOS请自行运行代码安装。

![手机扫描二维码安装](https://www.pgyer.com/app/qrcode/HqqH "手机扫描二维码安装")

Blog地址 : [https://h.lishaoy.net/flutterctrip](https://h.lishaoy.net/flutterctrip)

### 特别提醒

由于百度AI语言识别SDK包的 `libBaiduSpeechSDK.a` 有 **184.2M**，放到GitHub上下载很慢，所以，请[点击下载 libBaiduSpeechSDK.a 文件](https://speech-doc.gz.bcebos.com/ios-asr/ASR_iOS_v3.0.9.0_20200107_Release.zip)，
解压后，把 `BDSClientLib/libBaiduSpeechSDK.a` 目录放到 `flutter_ctrip/ios/Plugin/ASRPlugin/` 目录下。

