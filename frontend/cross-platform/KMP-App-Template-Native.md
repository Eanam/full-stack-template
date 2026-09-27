# Kotlin Multiplatform App Template Native

## 仓库链接

- [Kotlin/KMP-App-Template-Native](https://github.com/Kotlin/KMP-App-Template-Native)
- 官方模板入口：[kmp.jetbrains.com](https://kmp.jetbrains.com/)

## 仓库总结

- 定位：JetBrains/Kotlin 官方 Kotlin Multiplatform 模板，共享业务逻辑和数据处理，UI 使用各平台原生技术。
- 核心技术栈：Kotlin Multiplatform、Jetpack Compose、SwiftUI、React、Gradle、Ktor 和 kotlinx.serialization。
- 脚手架能力：提供 Android、iOS、桌面和 Web 的基础工程，可复制仓库或通过官方模板入口开始项目。
- 工程能力：共享 ViewModel、网络和序列化代码，平台侧分别使用 Compose、SwiftUI 或 React 构建界面。
- 适用场景：需要共享领域逻辑，但希望保留 Android/iOS 原生 UI 体验和平台设计规范的团队。
- 优点：共享代码与原生体验之间的边界清晰，适合渐进式引入 Kotlin Multiplatform。
- 注意事项：跨平台 UI 需要分别维护；iOS 需要 Xcode，Web 端还需要 Node.js 工具链。
- 许可证：Apache-2.0。

