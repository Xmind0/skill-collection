# Codex 内置及随插件提供的技能

本页说明本机 Codex 中识别到的 **18 项 OpenAI 提供的技能**。它们与可独立安装的第三方技能分开列出。

内置功能通常随 Codex 提供；插件功能通过 Codex 的插件目录获取。未找到独立公开安装入口的项目明确注明，不将通用帮助页标作独立安装链接。

- [官方技能说明](https://learn.chatgpt.com/docs/build-skills)
- [官方插件说明](https://learn.chatgpt.com/docs/plugins)
- [返回第三方收藏目录](README.md)

## 系统技能

| Skill | 是什么 / 适合做什么 | 获取方式 / 官方来源 |
|---|---|---|
| `imagegen` | 生成新图片或按要求编辑现有图片。 | 随 Codex 提供；[官方源码](https://github.com/openai/skills/tree/main/skills/.system/imagegen) |
| `openai-docs` | 查询 OpenAI、Codex 和 API 的官方资料。 | 随 Codex 提供；[官方源码](https://github.com/openai/skills/tree/main/skills/.system/openai-docs) |
| `review-agent` | 为代码审查提供专门的审查流程。 | 随 Codex 提供；未确认独立公开安装入口 |
| `skill-creator` | 创建或更新通用 Codex skill。 | 随 Codex 提供；[官方源码](https://github.com/openai/skills/tree/main/skills/.system/skill-creator) |
| `skill-installer` | 从公开仓库或官方技能目录安装 skills。 | 随 Codex 提供；[官方源码](https://github.com/openai/skills/tree/main/skills/.system/skill-installer) |

## 文档、可视化、网站和宠物

以下为 Codex 内置能力或官方插件提供的工作流。具体可用项目取决于当前客户端及插件目录；未确认可脱离宿主独立安装，不提供推测的下载链接。

| Skill | 是什么 / 适合做什么 | 获取方式 |
|---|---|---|
| `visualize` | 在对话里制作交互式图表、模拟和解释工具。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `plugin-management` | 发现插件，检查连接、权限和依赖，管理插件安装。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `sites` | 创建、修改和发布网站，管理 Sites 网站项目。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `sites-remix` | 基于已有 Sites 网站创建一个新版本。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `create-pet` | 从角色想法或参考图创建 ChatGPT Work 动画宠物。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `pets` | 查看、选择、下载和管理 ChatGPT Work 动画宠物。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `update-pet` | 修改动画宠物名称、说明或动作素材。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `documents` | 创建、编辑和检查 Word 文档及其版式。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `pdf` | 读取、制作和检查 PDF，包括可填写表单。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `presentations` | 创建和修改演示文稿及 PowerPoint 文件。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `excel-live-control` | 通过已连接的 Excel 会话操作当前工作簿。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `spreadsheets` | 创建、分析和修改表格、公式、图表与工作簿。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |
| `template-creator` | 从参考文档、表格或演示稿建立可复用模板技能。 | 随宿主或对应插件提供；[官方插件使用说明](https://learn.chatgpt.com/docs/plugins) |

20 项官方模板技能单独整理在 [OpenAI Templates](OPENAI-TEMPLATES.md)。

说明日期：2026-10-20。
