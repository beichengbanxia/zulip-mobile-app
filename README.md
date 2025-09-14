# Zulip Mobile App

这是一个基于WebView的Zulip移动端应用，支持Android平台。

## 功能特性

- ✅ 基于WebView的跨平台支持
- ✅ 支持连接任意Zulip服务器
- ✅ 响应式设计，适配移动端
- ✅ 离线缓存支持
- ✅ 原生Android集成

## 构建说明

### 使用Android Studio
1. 打开Android Studio
2. 选择"Open an existing project"
3. 选择此项目目录
4. 等待Gradle同步完成
5. 点击"Build" -> "Build Bundle(s) / APK(s)" -> "Build APK(s)"

### 使用命令行
```bash
# 进入项目目录
cd zulip_mobile_app

# 构建APK
./gradlew assembleDebug

# 构建发布版APK
./gradlew assembleRelease
```

## 安装说明

1. 构建完成后，APK文件位于 `app/build/outputs/apk/` 目录
2. 将APK文件传输到Android设备
3. 在设备上启用"未知来源"安装
4. 安装APK文件

## 技术栈

- **前端**: HTML5 + CSS3 + JavaScript
- **移动端**: Android WebView
- **构建工具**: Gradle
- **最低支持**: Android 5.0 (API 21)

## 版本信息

- 版本: 1.0
- 构建日期: D:\cursorspace\IM\zulip-main
- 支持平台: Android

## 注意事项

- 需要网络连接才能使用
- 首次使用需要输入Zulip服务器地址
- 支持HTTP和HTTPS协议
- 建议在WiFi环境下使用以节省流量
