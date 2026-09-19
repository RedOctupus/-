# 工程化介绍、规范与指南

面向 **AI 应用 / 金融场景项目** 的文档库：企业级开发流程、工程化专题交互课、面试备考材料，以及可复用的交互页模板。

## 目录结构

| 分类 | 路径 | 说明 |
| --- | --- | --- |
| 项目开发指南 | [`docs/project/`](docs/project/) | AI 金融项目从需求到发布的流程说明（Markdown + 交互版 HTML） |
| 面试备考 | [`docs/interview/`](docs/interview/) | 通用大模型岗 Q&A 与智能财富管家全流程 30 问 |
| 工程化交互专题 | [`guides/interactive/`](guides/interactive/) | 单主题沉浸式 HTML 指南（CI/CD、Langfuse、DeepEval） |
| 模板 | [`templates/`](templates/) | 生成交互版文档用的 HTML 模板 |

## 快速入口

### 项目开发指南

- [AI 金融项目开发指南（Markdown）](docs/project/AI金融项目开发指南.md)
- [AI 金融项目开发指南（交互版，浏览器打开）](docs/project/AI金融项目开发指南-交互版.html)

### 面试备考

- [大模型应用开发岗 — 面试问题与回答总结](docs/interview/面试问题总结_v.11.md)
- [智能财富管家 — 全流程面试题库（30 问）](docs/interview/AI金融项目面试题库-全流程版.md)

### 工程化交互专题

| 主题 | 文件 |
| --- | --- |
| 软件开发流程与 CI/CD | [14_ci_cd_guide.html](guides/interactive/14_ci_cd_guide.html) |
| Langfuse 可观测 | [21_langfuse_guide.html](guides/interactive/21_langfuse_guide.html) |
| DeepEval 评估框架 | [22_deepeval_guide.html](guides/interactive/22_deepeval_guide.html) |

> 交互 HTML 为静态单页，可直接用浏览器打开；部分页面依赖 CDN（字体、Marked、Mermaid 等），离线时需联网。

### 模板

- [交互指南页模板](templates/interactive-guide-template.html) — 基于 Markdown 渲染 + Mermaid / Markmap 的交互壳

## 推荐阅读顺序

1. **立项与流程**：`docs/project/AI金融项目开发指南.md`（或交互版）
2. **交付与协作**：`guides/interactive/14_ci_cd_guide.html`
3. **质量与观测**：`22_deepeval_guide.html` → `21_langfuse_guide.html`
4. **答辩 / 面试**：`docs/interview/` 下两份材料按项目深度选用

## 贡献与使用

- 新增交互专题：复制 `templates/interactive-guide-template.html` 到 `guides/interactive/`，按现有编号或主题命名。
- 新增 Markdown 指南：放入 `docs/project/` 或 `docs/interview/`，并在本 README 的对应表格中补一行链接。

## License

文档仅供课程与团队内部学习使用；对外转载请注明出处。
