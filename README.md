# 项目脚手架模板仓库

## 仓库目的

本仓库用于收集和整理各个端可复用的成熟项目脚手架模板，帮助项目启动时快速选型、搭建工程，并沉淀不同技术栈的实践经验。

仓库中的内容以外部成熟项目为主，不直接替代原始仓库。使用前应结合项目需求，评估维护状态、技术栈版本、许可证、依赖安全性以及二次定制成本。

## 目录结构

目录采用两级分类：

1. 一级目录表示项目领域或端，例如 `backend`、`frontend`、`agent`。
2. 二级目录表示该领域下的场景或技术类别，例如 `microservice`、`web`、`kmp`。
3. 二级目录下使用 `*.md` 文件记录具体脚手架仓库。同一类别下可以收录多个不同框架，文件名应结合开源仓库名称命名。

示例结构：

```text
.
├── backend/
│   └── microservice/
│       ├── <repository-name>.md
│       └── <another-repository>.md
├── frontend/
│   └── kmp/
│       └── <repository-name>.md
├── agent/
│   └── <framework>/
│       └── <repository-name>.md
├── tasks/
│   └── <task_name>/
│       ├── plans.md
│       └── reports.md
└── README.md
```

`tasks/<task_name>/` 用于保存具体收集任务的计划和分析报告，避免过程文档散落在仓库根目录。

## 脚手架条目格式

每个二级目录下的脚手架说明文件建议包含以下内容：

```markdown
# <脚手架名称>

## 仓库链接

- <GitHub 或其他代码托管平台链接>

## 仓库总结

- 适用场景：
- 核心技术栈：
- 已提供能力：
- 优点：
- 注意事项：
```

新增脚手架时，请将说明文件放入对应的“领域/类别”目录，并使用开源仓库名称作为文件名（例如 `go-zero.md`、`kratos.md`）。如果仓库名称不够明确，可以使用 GitHub 的 `owner-repository` 形式，例如 `jetbrains-compose-multiplatform-template.md`，以避免同一类别下的条目重名。

## 当前收录

### Backend / Golang 微服务

- [go-zero](backend/microservice/go-zero.md)：API/RPC、`goctl` 代码生成和内置弹性治理
- [Kratos](backend/microservice/kratos.md)：Protobuf、HTTP/gRPC 和可组合云原生组件
- [Go Micro](backend/microservice/go-micro.md)：服务发现、RPC、消息、存储和 CLI 工作流
- [CloudWeGo Kitex](backend/microservice/kitex.md)：高性能 RPC、Thrift/Protobuf 和服务治理
- [CloudWeGo Hertz](backend/microservice/hertz.md)：高性能 HTTP 和可扩展网络层
- [TarsGo](backend/microservice/tarsgo.md)：Tars 生态高性能 RPC 和跨语言服务治理
