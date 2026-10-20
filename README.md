# Codex Skills 收藏目录

记录第三方 Codex skills 的**用途、安装入口和来源**。自建及来源无法确认的本地技能不收录。

- [开发工作流 · Superpowers](#开发工作流--superpowers)
- [检索、联网与配图](#检索联网与配图)
- [视频、图片与音频 · ChatCut](#视频图片与音频--chatcut)
- [Codex 内置及随插件提供的技能说明](CODEX-BUILTIN.md)

这里整理了 **40 项第三方 skills 的安装入口和介绍**。另有 38 项内置或随宿主分发的技能在附表中说明，明确区分“可单独安装”与“随宿主提供”。链接核对日期：2026-10-20。

## 开发工作流 · Superpowers

来源：[obra/superpowers](https://github.com/obra/superpowers)。这些技能属于同一套工作流，可在 Codex 的插件目录搜索 **Superpowers** 并安装；按[作者的 Codex 安装说明](https://github.com/obra/superpowers#codex-app)操作。

| Skill | 是什么 / 适合做什么 | 安装入口 |
|---|---|---|
| `brainstorming` | 开发前梳理目标、需求和方案，形成可确认的设计。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `dispatching-parallel-agents` | 把互不依赖的任务拆给多个 Agent 并行处理。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `executing-plans` | 按照已经写好的实施计划分阶段执行。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `finishing-a-development-branch` | 完成开发后的分支收尾、合并或 PR 交付。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `receiving-code-review` | 核实代码审查意见，再决定如何修改。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `requesting-code-review` | 在交付前组织代码审查，检查实现是否符合需求。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `subagent-driven-development` | 由主 Agent 拆分实施任务，协调子 Agent 开发和审查。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `systematic-debugging` | 从现象、证据和复现入手，逐步定位故障根因。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `test-driven-development` | 先写能暴露问题的测试，再实现和重构。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `using-git-worktrees` | 用独立 Git 工作目录隔离开发任务。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `using-superpowers` | 识别当前任务适用的 Superpowers 技能并加载工作流。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `verification-before-completion` | 完成前执行验证，以真实结果支持交付结论。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `writing-plans` | 把明确需求拆成可执行的开发步骤和验收检查。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |
| `writing-skills` | 编写、调整和验证可复用的 Agent 技能。 | [安装 Superpowers](https://github.com/obra/superpowers#codex-app) |

## 检索、联网与配图

| Skill | 是什么 / 适合做什么 | 安装入口与来源 |
|---|---|---|
| `find-skills` | 搜索社区技能，找到合适的项目并帮助安装。 | [项目与安装说明](https://github.com/vercel-labs/skills/tree/main/skills/find-skills) |
| `web-access` | 为 Agent 提供联网策略、网页读取和浏览器操作工作流。 | [项目与安装说明](https://github.com/eze-is/web-access#安装) |
| `typesafe-ai` | 用 TypeSafe 的类型化 AI 判断构建分类、评分和路由等功能。 | [项目与安装说明](https://github.com/typesafe-ai/skills/tree/main/skills/typesafe-ai) |
| `ian-xiaohei-illustrations` | 为中文文章生成小黑 IP、白底手绘风格的正文配图。 | [项目与安装说明](https://github.com/helloianneo/ian-xiaohei-illustrations#安装) |

有公开 skill 文件夹的项目，可把上面的链接发给 Codex，并说“帮我安装这个 skill”。以作者当前的安装说明为准。

## 视频、图片与音频 · ChatCut

来源：[ChatCut](https://chatcut.io)。以下为同一产品提供的工作流，使用[ChatCut 官方 Codex 插件安装指南](https://chatcut.io/docs/agent-plugin)接入；桌面版相关工作流随 ChatCut Desktop 提供，并非每项都有独立安装包。

| Skill | 是什么 / 适合做什么 | 安装入口 |
|---|---|---|
| `chatcut-app-promo-guide` | 规划和制作 App、网站或 SaaS 软件产品宣传短片。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-audio-processing-gen` | 制作自定义音频效果和音频转场，如均衡、延迟和混响。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-create-motion-graphics` | 创建可编辑的动态图形、文字动画和说明动画。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-digital-human` | 把人物肖像或已有形象制作为数字人口播视频。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-image-gen` | 通过 ChatCut 的图片模型生成或参考编辑图片。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-image-gen-codex` | Codex 适配的 AI 图片生成工作流，并将图片登记为 ChatCut 素材。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-lipsync` | 让已有视频中的嘴型与指定语音对齐。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-multicam-sync` | 同步多机位素材和独立录音，按说话人形成初剪。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-music` | 生成背景音乐、配乐或带人声歌曲。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-pixel-processing-gen` | 编写视频滤镜、蒙版、调色和自定义画面转场。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-product-help` | 查询 ChatCut 官方使用说明、功能、版本与安装问题。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-skill-creator` | 把已验证的视频编辑流程整理为可复用技能。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-talking-head-guide` | 剪辑口播、访谈、课程等以讲话为主的视频。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-transcription` | 处理转写、字幕校正、字幕翻译及显示样式。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-ugc-ad-guide` | 制作实体商品的 UGC 风格广告和带货视频。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-video-gen` | 通过文字、图片或参考素材生成和修改视频片段。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-video-translation` | 为已有视频翻译原始讲话并配音，可选嘴型同步。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-visual-analysis` | 对比时间线和原素材画面，检查视觉修改结果。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-voice` | 生成配音、旁白、音效，以及经授权的声音克隆。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-voice-isolation` | 抑制背景噪音和混响，改善视频或录音中的人声。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-web-browser` | 为视频制作读取网页、获取截图和收集品牌素材。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |
| `chatcut-widget-forms` | 为 ChatCut Agent 制作文件上传、参数填写和预览选择表单。 | [ChatCut 安装指南](https://chatcut.io/docs/agent-plugin) |

## 来源说明

这些是已识别的第三方项目和发布者。介绍根据对应 skill 的用途概括；安装入口优先使用作者仓库或官方说明。同套产品中的技能共用安装入口；本机已安装名称可能与上游新版本略有不同。

本目录只保存链接和介绍。没有复制 skill 正文、脚本、资源或个人配置。
