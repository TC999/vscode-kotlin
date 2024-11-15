# Kotlin IDE for Visual Studio Code

[![版本](https://raster.shields.io/visual-studio-marketplace/v/fwcd.kotlin)](https://marketplace.visualstudio.com/items?itemName=fwcd.kotlin) 
[![构建](https://raster.shields.io/github/actions/workflow/status/fwcd/vscode-kotlin/build.yml?branch=main)](https://github.com/fwcd/vscode-kotlin/actions/workflows/build.yml) 
[![下载量](https://raster.shields.io/visual-studio-marketplace/d/fwcd.kotlin)](https://marketplace.visualstudio.com/items?itemName=fwcd.kotlin) 
[![安装量](https://raster.shields.io/visual-studio-marketplace/i/fwcd.kotlin)](https://marketplace.visualstudio.com/items?itemName=fwcd.kotlin) 
[![聊天](https://raster.shields.io/badge/chat-on%20discord-7289da)](https://discord.gg/cNtppzN) 

使用 [Kotlin 语言服务器](https://github.com/fwcd/kotlin-language-server) 和 [Kotlin 调试适配器](https://github.com/fwcd/kotlin-debug-adapter)，在 VSCode 中为 Kotlin 提供智能代码补全、linting、调试、格式化等功能。

使用前，请确保已安装 JDK 11+，并在 Gradle 或 Maven 项目中打开一个 Kotlin 文件。对使用独立编译器（`kotlinc`）的 Kotlin 源文件的支持是实验性的。然后，语言服务器将自动在后台启动。

## 特性
* 代码补全
* Linting
* 语义高亮
* 调试
* 定义跳转
* 签名帮助
* 悬停提示
* 格式化
* 文档符号
* 查找引用

## 使用方法

### 调试
* 设置：
    * 在项目中打开 `launch.json` 文件，并调用代码补全来创建一个新的启动配置（或在调试标签页中选择 `添加配置...`）
* 启动：
    * 构建你的项目（每次启动前）
    * 点击 `调试` 标签页中的 `运行` 按钮或按 `F5`
