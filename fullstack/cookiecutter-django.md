# Cookiecutter Django

## 仓库链接

- [cookiecutter/cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django)
- 官方文档：[cookiecutter-django.readthedocs.io](https://cookiecutter-django.readthedocs.io/)

## 仓库总结

- 定位：用于快速生成生产级 Django 项目的 Cookiecutter 模板。
- 核心技术栈：Django、Python、PostgreSQL、Bootstrap、django-allauth、Docker、Celery（可选）和 pytest/unittest。
- 脚手架能力：执行 `uvx cookiecutter https://github.com/cookiecutter/cookiecutter-django`，交互式选择项目名、数据库、部署、邮件和存储配置。
- 工程能力：自定义 User Model、注册认证、12-Factor 配置、Docker Compose、静态/媒体文件存储、后台任务、Sentry 和 CI 基础。
- 适用场景：需要成熟 Python/Django 后端，同时快速获得管理后台、认证、数据库和部署配置的全栈 Web 项目。
- 优点：生产默认值丰富，配置选项全面，社区维护时间长，适合企业项目基线。
- 注意事项：生成选项较多，团队应建立自己的默认配置；前端通常需要在 Bootstrap、模板渲染或独立 SPA 之间做进一步选择。
- 许可证：BSD-3-Clause。

