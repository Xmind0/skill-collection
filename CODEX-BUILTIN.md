# Codex 内置及随插件提供的技能

本页说明本机 Codex 中识别到的 **38 项 OpenAI 提供的技能**。它们与可独立安装的第三方技能分开列出。

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

## 官方模板技能

来源为本机 Codex 的 OpenAI Templates 分发。未确认独立公开安装链接；请以客户端中可用的模板或插件入口为准。

| Skill | 是什么 / 适合做什么 |
|---|---|
| `artifact-template-analytics-dashboard` | 制作含获客、留存、收入和转化指标的分析看板表格。 |
| `artifact-template-business-review` | 制作业务表现、指标、战略重点与展望的复盘演示稿。 |
| `artifact-template-design-report` | 制作包含发现、分析和建议的设计报告文档。 |
| `artifact-template-experiment-analysis` | 制作实验假设、方法、结果和局限的分析文档。 |
| `artifact-template-financial-budget` | 制作预算、实际值、情景预测和差异分析表格。 |
| `artifact-template-investment-committee-memo` | 制作包含投资论点、财务分析和风险的投委会备忘录。 |
| `artifact-template-legal-memorandum` | 制作包含问题、事实、分析和结论的法律备忘录。 |
| `artifact-template-market-trends-report` | 制作行业趋势、证据、影响和建议的演示稿。 |
| `artifact-template-minimal-letterhead` | 制作简洁信头版式的正式商务信函。 |
| `artifact-template-operating-calendar` | 制作年度及月度经营里程碑和活动日历。 |
| `artifact-template-operating-review` | 制作每周经营指标、风险、决策和行动复盘演示稿。 |
| `artifact-template-project-kickoff` | 制作项目目标、范围、里程碑、职责和风险的启动演示稿。 |
| `artifact-template-project-tracker` | 制作任务、负责人、状态、时间和进度跟踪表。 |
| `artifact-template-sales-pipeline` | 制作销售机会、阶段、预期收入和进展的跟踪表。 |
| `artifact-template-simple-dark-mode` | 使用简洁深色版式制作演示稿。 |
| `artifact-template-simple-light-mode` | 使用简洁浅色版式制作演示稿。 |
| `artifact-template-strategy-memorandum` | 制作包含背景、选项、取舍和建议的战略备忘录。 |
| `artifact-template-system-design` | 制作架构、组件、数据流和设计取舍的系统设计文档。 |
| `artifact-template-team-alignment` | 制作团队目标、职责、优先级和协作安排的演示稿。 |
| `artifact-template-three-statement-forecast` | 制作利润表、资产负债表和现金流量表联动预测。 |

说明日期：2026-10-20。此页仅保留功能介绍和官方入口。
