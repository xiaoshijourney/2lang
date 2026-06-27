# Changelog / 更新日志

All notable changes to this project will be documented in this file.

本项目的所有重要变更都将记录在此文件中。

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)，
本项目遵循 [语义化版本控制](https://semver.org/lang/zh-CN/)。

---

## [Unreleased] / [未发布]

### Added / 新增
- **User input echo translation** — first line of response translates user's input into the other language
- **用户输入回声翻译** — 回复第一行将用户输入翻译成另一种语言
- **English Practice Mode** with 3 difficulty levels (beginner/intermediate/advanced)
- **英语练习模式**，3 个难度等级（初级/中级/高级）
- **Ladder Mode** for gradual bilingual-to-English transition over 4 weeks
- **阶梯模式**，4 周内从双语逐步过渡到纯英文
- 3 new personas: 摸鱼大师 (Slacker), 暴躁老哥 (Grumpy Coder), 二次元 (Anime)
- 3 个新人格：摸鱼大师、暴躁老哥、二次元
- Paragraph-level translation strategy (paragraph-by-paragraph, full response, section-by-section)
- 段落级翻译策略（逐段翻译、完整翻译、按节翻译）
- Mixed content handling (headers, code blocks, lists, tables, inline code, links, images, blockquotes)
- 混合内容处理（标题、代码块、列表、表格、行内代码、链接、图片、引用块）
- Long response handling with section-by-section translation
- 长回复处理，使用按节翻译
- Streaming response handling guidelines
- 流式回复处理指南
- Error handling for invalid input (language codes, persona names, commands)
- 错误处理（语言代码、人格名称、命令）
- Cross-platform usage instructions (OpenAI Codex, GitHub Copilot, Universal AI)
- 跨平台使用说明（OpenAI Codex、GitHub Copilot、通用 AI）
- Language memory feature for saving user preferences
- 语言记忆功能，保存用户偏好
- Mixed language mode (primary + secondary language mixing)
- 混合语言模式（主要语言 + 次要语言混合）
- Expanded language support (zh-CN, zh-TW, ar, ru, pt, it)
- 扩展语言支持（简体中文、繁体中文、阿拉伯语、俄语、葡萄牙语、意大利语）
- Persona favorites for quick access
- 人格收藏夹，快速访问
- Quick commands reference in README
- README 中的快速命令参考
- Comprehensive examples (multi-paragraph, mixed language, error handling, cosplay)
- 综合示例（多段落、混合语言、错误处理、角色扮演）

### Changed / 变更
- Enhanced README with badges, screenshots, and "Why 2lang?" section
- 增强 README，添加徽章、截图和"为什么选择 2lang？"部分
- Improved project structure documentation
- 改进项目结构文档
- Updated cross-platform instructions with new features
- 更新跨平台指令，包含新功能
- Clarified status display rules (when to show/hide/toggle)
- 明确状态显示规则（何时显示/隐藏/切换）

### Fixed / 修复
- Fixed colon + newline content being skipped in translation
- 修复冒号换行后内容漏掉翻译的问题
- Synced project SKILL.md with installed version
- 同步项目 SKILL.md 与已安装版本
- Fixed multi-segment response translation issue
- 修复多段落回复翻译问题

---

## [1.0.0] - 2026-06-21

### Added / 新增
- Initial release of 2lang skill
- 2lang 技能首次发布
- Intelligent language ordering based on content type
- 基于内容类型的智能语序调整
- Content-aware translation rules (technical terms, code blocks, cultural references)
- 内容感知翻译规则（技术术语、代码块、文化引用）
- 8 selectable personas (Default, Professional, Friendly, Teacher, Tech Expert, Creative, Storyteller, Socratic)
- 8 种可选人格（默认、专业、友好、导师、技术专家、创意、叙事者、苏格拉底式）
- Custom persona (cosplay mode) support
- 自定义人格（角色扮演模式）支持
- Quick start with one-command setup
- 一条命令快速启动
- Language and persona switching
- 语言和人格切换
- Status display toggle
- 状态显示切换
- Reset functionality
- 重置功能
- MIT License
- MIT 许可证

---

## Types of Changes / 变更类型

- **Added / 新增**: New features / 新功能
- **Changed / 变更**: Changes to existing functionality / 现有功能的变更
- **Deprecated / 弃用**: Features that will be removed in upcoming releases / 即将移除的功能
- **Removed / 移除**: Features removed in this release / 本版本移除的功能
- **Fixed / 修复**: Bug fixes / 修复的问题
- **Security / 安全**: Vulnerability fixes / 漏洞修复

---

## How to Update This File / 如何更新此文件

When making changes, add a new entry under `[Unreleased]` with the appropriate type (Added, Changed, Fixed, etc.).

进行更改时，在 `[未发布]` 下添加新条目，并使用适当的类型（新增、变更、修复等）。

When releasing a new version:
发布新版本时：

1. Move all `[Unreleased]` items to the new version section
   将所有 `[未发布]` 条目移至新版本部分
2. Update the version number and date
   更新版本号和日期
3. Create a new empty `[Unreleased]` section
   创建新的空 `[未发布]` 部分
