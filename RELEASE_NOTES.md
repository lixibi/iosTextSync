版本：macOS 1.0 (1)

发布内容：
- TextSync macOS 菜单栏客户端首个二进制发布。
- 原生 SwiftUI 设计，作为轻量级菜单栏工具运行。
- 支持发送剪贴板到远程、获取远程最新文本到剪贴板、快捷复制历史记录。
- 支持本地缓存、置顶、隐藏、本地编辑和单条云端更新。
- 支持自定义 TextSync 服务器地址，设置保存在本机，不内置任何服务器地址。
- 修正获取最新文本逻辑：直接请求 /api/get 并禁用 GET 缓存，减少拿到旧内容的可能。

发布包：
- TextSync-macOS-v1.0-universal.zip
- 内含 TextSync.app universal 二进制，支持 Apple Silicon 与 Intel Mac。
- 不包含源码、本地缓存、服务器地址或用户设置。

说明：
- 该包为 ad-hoc 签名，未做 Apple notarization。
- 最低系统版本：macOS 13.0。
