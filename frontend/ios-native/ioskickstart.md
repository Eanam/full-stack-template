# iOSKickstart

## 仓库链接

- [shurutech/iOSKickstart](https://github.com/shurutech/iOSKickstart)

## 仓库总结

- 定位：基于 SwiftUI 的 iOS App 命令行生成器，用于从配置快速创建新应用。
- 核心技术栈：Swift、SwiftUI、Xcode、Swift Package/原生 iOS 工程、Firebase Crashlytics/Analytics 可选集成。
- 脚手架能力：执行远程 `create_swift_app.sh` 后，可交互配置应用名、侧边栏、Tab 数量（2-5 个）、认证、条款、引导页、本地化和主题模式。
- 工程能力：Splash、登录注册、用户资料、条款、Onboarding、Main Tab Screens、设置、网络层和配置文件结构。
- 适用场景：需要快速生成带登录流程、引导流程和多 Tab 主界面的 SwiftUI App，尤其适合产品原型和业务起步项目。
- 优点：初始化命令简单，Tab 数量和常见产品流程可配置，是本批项目中最直接的多 Tab 生成器。
- 注意事项：脚本通过远程 URL 执行，使用前应审查脚本内容并固定版本；生成后需替换示例 API、Firebase 配置和 Dummy 内容。
- 许可证：GitHub API 未返回标准 SPDX 标识，使用前请核对仓库 LICENSE。

