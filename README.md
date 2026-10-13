# 鸿枢官网 · Hongshu Website

鸿枢 / Hongshu 的产品官网与下载入口。本仓库只承载官网站点，产品源码与发版在独立仓库维护：

- 产品仓库（唯一事实来源）：<https://github.com/IGNGserver/hongshu>
- 产品定位：自部署的跨设备短信同步平台 —— 短信可靠上传到自己的 MySQL 中枢，在所有授权 Android 与 Web/PWA 设备上查看，无需 Firebase/FCM
- 托管目标：Cloudflare（Pages / Workers 待定，见 [`docs/HOSTING.md`](docs/HOSTING.md)）

> **状态**：仓库已初始化，前端技术栈尚未选定；页面结构、视觉、文案与构建产物均未定案。
> 不要把本仓库现有的目录与文档当成技术选型结论。

## 仓库结构

| 路径 | 内容 |
| --- | --- |
| [`docs/SITE.md`](docs/SITE.md) | 官网定位、范围、与产品仓库的关系、待决策项 |
| [`docs/HOSTING.md`](docs/HOSTING.md) | Cloudflare 托管方案与上线检查清单 |
| [`docs/WORKSPACE.md`](docs/WORKSPACE.md) | 本机 worktree 工作区约定 |
| [`scripts/verify-repository.sh`](scripts/verify-repository.sh) | 仓库契约检查（本地与 CI 共用） |
| [`.github/workflows/ci.yml`](.github/workflows/ci.yml) | CI：仓库契约、whitespace、凭据扫描 |

## 开发

工作区、分支、验证与 PR 流程见 [`AGENTS.md`](AGENTS.md) 与 [`CONTRIBUTING.md`](CONTRIBUTING.md)。

## 许可

[MIT](LICENSE)
