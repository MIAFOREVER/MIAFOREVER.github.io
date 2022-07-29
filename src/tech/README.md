# Chromium 系列

## 编译 for Win

`source url` [https://chromium.googlesource.com/chromium/src/+/main/docs/windows_build_instructions.md](https://chromium.googlesource.com/chromium/src/+/main/docs/windows_build_instructions.md)

Chromium 的编译体验从整体上来说还是比较不错的，官方文档说的很详细了。

### 安装 VS
这一步 google 官方说的就比较清楚了，如果是编译最新的代码，需要至少 vs2017 推荐使用 vs2019 及以上版本，与此同时，vs 也能用来 debug 编译出来的 chromium。

### 安装 win10 sdk 
You must have the version 10.0.20348.0 [Windows 10 SDK](https://developer.microsoft.com/en-us/windows/downloads/sdk-archive/) installed
必须安装 win 10 sdk 这个没啥好说的，直接装就行。

### 安装 depot_tools
下载 [depot_tools](https://storage.googleapis.com/chrome-infra/depot_tools.zip)，然后解压，解压之后
