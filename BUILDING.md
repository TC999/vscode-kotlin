# 构建
描述了如何构建和运行扩展。

## 开发/运行
首先在后台 shell 中运行 `npm run watch`。然后，扩展将在后台增量构建。

每次你想要运行带有语言服务器的扩展时：
* 使用 `npm run prepare` 准备扩展（这将自动将语言服务器的二进制文件下载到扩展文件夹中）
* 在 VSCode 中打开调试标签页
* 运行 `Extension` 启动配置

## 调试
你可以附加到在 `localhost:8000` 上运行的语言服务器。注意，这可以通过使用 VSCode 中的 `Attach Kotlin Language Server` 启动配置来完成（需要 [Java Debug Extension](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug))。

## 打包
从仓库的顶级目录运行 `npm run package-extension`。然后，扩展将位于名为 `kotlin-[version].vsix` 的位置。
