# CloudWeGo Hertz

## 仓库链接

- [cloudwego/hertz](https://github.com/cloudwego/hertz)
- 官方文档：[CloudWeGo Hertz](https://www.cloudwego.io/docs/hertz/)
- 示例仓库：[cloudwego/hertz-examples](https://github.com/cloudwego/hertz-examples)

## 仓库总结

- 定位：高易用、高性能、强扩展性的 Go HTTP 框架，面向微服务开发。
- 核心技术栈：Go、HTTP/1.1、ALPN、Netpoll，可在 Netpoll 与 Go net 之间切换。
- 脚手架能力：官方提供 Getting Started 和独立示例仓库，可快速搭建 HTTP 服务；通过分层设计支持自定义协议和网络库。
- 工程能力：中间件、数据绑定、日志、错误处理、可观测性，以及通过 `hertz-contrib` 接入注册发现、限流、鉴权、追踪和 OpenTelemetry。
- 适用场景：以 HTTP API 为主、关注性能和网络层扩展能力的微服务或网关项目。
- 优点：HTTP 开发体验较好，性能路径明确，扩展生态覆盖常见生产需求。
- 注意事项：Hertz 本身偏 HTTP 层；服务发现、RPC 和完整治理需要结合 Kitex 或 contrib 组件进行架构组合。
- 许可证：Apache-2.0。

