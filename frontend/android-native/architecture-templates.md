# Android Architecture Starter Templates

## 仓库链接

- [android/architecture-templates](https://github.com/android/architecture-templates)
- Android 架构指南：[Guide to app architecture](https://developer.android.com/topic/architecture)

## 仓库总结

- 定位：Android 官方提供的可定制工程模板，面向新项目和快速实验，不是教学样例。
- 模板类型：`base` 提供单模块响应式 Compose 架构；`multimodule` 在此基础上提供多模块结构。
- 核心技术栈：Kotlin、Jetpack Compose、Material 3、Room、Hilt、ViewModel、Navigation、Coroutines/Flow、Gradle Kotlin DSL 和 Version Catalog。
- 脚手架能力：按分支克隆模板后运行 `customizer.sh`，输入包名、实体类型和应用名即可生成项目基础代码。
- 工程能力：包含数据层、响应式状态、依赖注入、单元测试、Compose UI 测试和 Hilt 测试替身。
- 适用场景：希望快速建立符合 Android 官方架构指南的 Kotlin/Compose 单模块或多模块项目。
- 优点：官方维护，模板边界明确，定制脚本和生产常用基础设施开箱即用。
- 注意事项：兼容最新稳定版 Android Studio；定制脚本要求 Bash 4+，macOS 用户可能需要安装新版 Bash。
- 许可证：Apache-2.0。

