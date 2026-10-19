# PokéBonk 安卓封装项目

这是一个 Android Studio 项目：通过 Android WebView 加载原网站 https://pokebonk.com/，并以横屏、沉浸式全屏方式显示。

## 如何生成 APK

1. 安装 Android Studio。
2. 在 Android Studio 中打开项目根目录。
3. 等待 Gradle 同步并安装提示需要的 Android SDK Platform 35。
4. 选择 Build → Build Bundle(s) / APK(s) → Build APK(s)。
5. APK 位于 app/build/outputs/apk/debug/app-debug.apk。

## 说明

- 这是网页封装，不是离线版游戏；需要联网加载游戏。
- WebView 的 Cookie 和本地存储通常不与 Chrome 共享。
- 游戏需要 Android System WebView / Chrome 支持 WebGL。
- 本项目与任天堂、宝可梦公司或 GAME FREAK 无关联。
