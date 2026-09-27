# 分析报告

## 阶段 1：候选筛选（completed）

基于 GitHub 仓库定位、官方 README、初始化能力、维护状态和许可证，筛选出以下全栈项目脚手架：

| 仓库 | 定位 | 许可证 |
| --- | --- | --- |
| [t3-oss/create-t3-app](https://github.com/t3-oss/create-t3-app) | 可选模块的 Next.js 全栈类型安全 CLI | MIT |
| [wasp-lang/wasp](https://github.com/wasp-lang/wasp) | React、Node.js、Prisma 声明式全栈框架 | MIT |
| [cookiecutter/cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django) | 生产级 Django 项目生成器 | BSD-3-Clause |
| [ixartz/Next-js-Boilerplate](https://github.com/ixartz/Next-js-Boilerplate) | Next.js、TypeScript、Drizzle 和测试工程模板 | MIT |
| [nuxt/nuxt](https://github.com/nuxt/nuxt) | Vue 全栈框架和 `npm create nuxt` Starter | MIT |
| [redwoodjs/sdk](https://github.com/redwoodjs/sdk) | 基于 Cloudflare 的 Server-first React 全栈框架 | MIT |
| [laravel/laravel](https://github.com/laravel/laravel) | Laravel 官方 PHP 应用基础骨架 | MIT |

上述仓库均为公开、未归档项目。Redwood 采用当前官方推荐的 `redwoodjs/sdk`，没有继续使用旧的 `redwoodjs/graphql` 作为入口。

## 阶段 2：条目编写（completed）

已按 `fullstack/<repository-name>.md` 创建 7 个独立条目：

- `fullstack/create-t3-app.md`
- `fullstack/wasp.md`
- `fullstack/cookiecutter-django.md`
- `fullstack/next-js-boilerplate.md`
- `fullstack/nuxt.md`
- `fullstack/redwood-sdk.md`
- `fullstack/laravel.md`

每个条目均包含仓库链接、官方文档、定位、技术栈、脚手架能力、适用场景、优点、注意事项和许可证。

## 阶段 3：索引和文档校验（completed）

- 已确认 7 个条目均位于根目录 `fullstack/` 下。
- 已确认每个条目包含 `仓库链接`、`仓库总结` 和 GitHub 地址。
- 已在根 README 增加全栈开发收录索引和目录示例。
- 已确认本任务的计划阶段和 Task 状态均已更新为 completed。
