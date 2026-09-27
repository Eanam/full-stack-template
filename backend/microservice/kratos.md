# Kratos

## 仓库链接

- [go-kratos/kratos](https://github.com/go-kratos/kratos)
- 官方文档：[go-kratos.dev](https://go-kratos.dev/)

## 仓库总结

- 定位：轻量、云原生的 Go 微服务框架，强调小而明确的组件接口。
- 核心技术栈：Go、Protobuf、HTTP、gRPC、`kratos` CLI、OpenTelemetry 扩展生态。
- 脚手架能力：安装 CLI 后可使用 `kratos new` 创建服务，使用 `kratos proto` 添加协议、生成客户端和服务端代码。
- 工程能力：提供 transport、middleware、registry、config、logging、encoding、错误和校验等可组合组件。
- 适用场景：采用 API-first/Proto-first，并希望按需组合基础设施组件的云原生微服务项目。
- 优点：抽象边界清晰、HTTP/gRPC 统一、生成流程完整、组件可替换性较好。
- 注意事项：完整工作流依赖 `protoc` 及相关插件；生产项目需要自行选择并验证注册中心、配置中心和可观测性实现。
- 许可证：MIT。

