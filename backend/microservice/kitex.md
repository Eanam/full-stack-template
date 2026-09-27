# CloudWeGo Kitex

## 仓库链接

- [cloudwego/kitex](https://github.com/cloudwego/kitex)
- 官方文档：[CloudWeGo Kitex](https://www.cloudwego.io/docs/kitex/)

## 仓库总结

- 定位：高性能、强扩展性的 Go RPC 微服务框架。
- 核心技术栈：Go、Thrift、Protobuf、gRPC、HTTP/2、TTHeader、Netpoll。
- 脚手架能力：内置代码生成工具，可根据 Thrift 或 Protobuf 生成协议代码和服务骨架。
- 工程能力：服务注册与发现、负载均衡、熔断、限流、重试、监控、日志、追踪和诊断等治理扩展。
- 适用场景：RPC 调用密集、对吞吐和延迟敏感，且需要对协议、传输或治理组件做定制的微服务系统。
- 优点：性能和扩展点突出，协议覆盖较广，代码生成和生产治理能力完善。
- 注意事项：需要在 IDL、代码生成器、治理组件和 CloudWeGo 生态之间建立版本兼容矩阵；不适合作为单纯轻量 HTTP 项目的唯一框架。
- 许可证：Apache-2.0。

