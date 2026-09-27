# 分析报告

## 阶段 1：候选筛选（completed）

基于 GitHub 仓库描述、官方 README、许可证和维护时间，筛选出以下 Go 微服务框架：

| 仓库 | 定位 | 许可证 |
| --- | --- | --- |
| [zeromicro/go-zero](https://github.com/zeromicro/go-zero) | Web/RPC、API 描述和 `goctl` 代码生成、内置弹性治理 | MIT |
| [go-kratos/kratos](https://github.com/go-kratos/kratos) | 轻量云原生微服务框架，Protobuf、HTTP/gRPC、可插拔组件 | MIT |
| [micro/go-micro](https://github.com/micro/go-micro) | 服务发现、RPC、消息、存储和 CLI 驱动的服务/Agent 工程 | Apache-2.0 |
| [cloudwego/kitex](https://github.com/cloudwego/kitex) | 高性能、可扩展 Go RPC 框架和代码生成 | Apache-2.0 |
| [cloudwego/hertz](https://github.com/cloudwego/hertz) | 高性能、可扩展 Go HTTP 框架，适合微服务 | Apache-2.0 |
| [TarsCloud/TarsGo](https://github.com/TarsCloud/TarsGo) | Tars 生态的高性能 Go RPC 框架 | BSD-3-Clause |

这些项目均为公开、未归档仓库，且官方资料明确包含微服务、RPC/HTTP 或工程生成能力。具体活跃度和版本信息以仓库当前页面为准。

## 阶段 2：条目编写（completed）

已按 `backend/<category>/<repository-name>.md` 规则创建 6 个独立条目：

- `backend/microservice/go-zero.md`
- `backend/microservice/kratos.md`
- `backend/microservice/go-micro.md`
- `backend/microservice/kitex.md`
- `backend/microservice/hertz.md`
- `backend/microservice/tarsgo.md`

每个条目均包含仓库链接、官方文档、定位、技术栈、脚手架能力、适用场景、优点、注意事项和许可证。

## 阶段 3：结果校验（completed）

- 已确认 6 个 Markdown 条目均位于 `backend/microservice/` 类别目录下。
- 已确认每个条目包含 `仓库链接` 和 `仓库总结` 两个必需章节。
- 已确认 `plans.md` 的阶段勾选和 Task 状态均已更新为 completed。

## 阶段 4：目录归档调整（completed）

用户确认同一类 Go 微服务框架应统一收录在 `backend/microservice/` 下，因此已将原先按项目分别建立的目录合并为一个类别目录，并使用仓库名称作为 Markdown 文件名。
