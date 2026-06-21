# Contributing to 2lang / 贡献指南

Thank you for your interest in contributing to 2lang! This document provides guidelines and information for contributors.

感谢你对 2lang 项目的贡献兴趣！本文档为贡献者提供指南和信息。

---

## 📋 Table of Contents / 目录

- [Code of Conduct / 行为准则](#code-of-conduct--行为准则)
- [How to Contribute / 如何贡献](#how-to-contribute--如何贡献)
- [Reporting Issues / 报告问题](#reporting-issues--报告问题)
- [Submitting Changes / 提交更改](#submitting-changes--提交更改)
- [Style Guide / 风格指南](#style-guide--风格指南)
- [Community / 社区](#community--社区)

---

## Code of Conduct / 行为准则

Please be respectful and inclusive in all interactions. We are committed to providing a welcoming and inspiring community for everyone.

请在所有互动中保持尊重和包容。我们致力于为每个人提供一个友好和鼓舞人心的社区。

---

## How to Contribute / 如何贡献

There are many ways to contribute to 2lang:

有多种方式可以为 2lang 做出贡献：

### 🐛 Report Bugs / 报告问题

Found a bug? Please open an issue with:
- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Your environment (OS, Claude Code version)

发现问题？请提交 issue，包含：
- 问题的清晰描述
- 重现步骤
- 期望与实际行为
- 你的环境（操作系统、Claude Code 版本）

### 💡 Suggest Features / 建议功能

Have an idea? Open an issue with:
- Clear description of the feature
- Use case / motivation
- Possible implementation approach

有想法？提交 issue，包含：
- 功能的清晰描述
- 使用场景/动机
- 可能的实现方式

### 📝 Improve Documentation / 改进文档

Documentation improvements are always welcome:
- Fix typos or unclear explanations
- Add examples
- Translate documentation

文档改进总是受欢迎的：
- 修复拼写错误或不清楚的解释
- 添加示例
- 翻译文档

### 🔧 Submit Code / 提交代码

Want to add a feature or fix a bug? See [Submitting Changes](#submitting-changes--提交更改).

想添加功能或修复问题？请查看[提交更改](#submitting-changes--提交更改)。

---

## Reporting Issues / 报告问题

When reporting issues, please include:

报告问题时，请包含：

1. **Description / 描述**: Clear and concise description of the issue
   问题的清晰简洁描述

2. **Steps to Reproduce / 重现步骤**:
   ```
   1. Go to '...'
   2. Click on '...'
   3. See error
   ```

3. **Expected Behavior / 期望行为**: What you expected to happen
   你期望发生的行为

4. **Actual Behavior / 实际行为**: What actually happened
   实际发生的行为

5. **Environment / 环境**:
   - OS: [e.g., Windows 11, macOS 14, Ubuntu 22.04]
   - Claude Code version: [e.g., 1.0.0]

6. **Screenshots / 截图**: If applicable, add screenshots
   如果适用，添加截图

---

## Submitting Changes / 提交更改

### Step 1: Fork the Repository / 第一步：Fork 仓库

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/2lang.git
cd 2lang

# Add upstream remote
git remote add upstream https://github.com/ORIGINAL_OWNER/2lang.git
```

### Step 2: Create a Branch / 第二步：创建分支

```bash
# Create and switch to a new branch
git checkout -b feature/your-feature-name
# or
git checkout -b fix/your-fix-name
```

### Step 3: Make Changes / 第三步：进行更改

- Make your changes
- Test thoroughly
- Update documentation if needed

- 进行更改
- 充分测试
- 如需要，更新文档

### Step 4: Commit / 第四步：提交

```bash
# Stage your changes
git add .

# Commit with a clear message
git commit -m "Add: brief description of your change"
```

**Commit Message Format / 提交信息格式**:
- `Add:` for new features / 新功能
- `Fix:` for bug fixes / 修复问题
- `Update:` for documentation or minor changes / 文档或小改动
- `Refactor:` for code refactoring / 代码重构

### Step 5: Push and Create PR / 第五步：推送并创建 PR

```bash
# Push to your fork
git push origin feature/your-feature-name
```

Then create a Pull Request on GitHub with:
- Clear title describing the change
- Detailed description of what was changed and why
- Reference any related issues

然后在 GitHub 上创建 Pull Request，包含：
- 清晰描述更改的标题
- 详细描述更改内容和原因
- 引用相关 issue

---

## Style Guide / 风格指南

### Documentation / 文档

- Use bilingual format (English + Chinese) for all documentation
  所有文档使用双语格式（英文+中文）
- Keep translations natural, not word-for-word
  保持翻译自然，不要逐字翻译
- Use clear, concise language
  使用清晰简洁的语言

### Code / 代码

- Follow existing code style
  遵循现有代码风格
- Add comments for complex logic
  为复杂逻辑添加注释
- Keep functions focused and small
  保持函数专注且小巧

### Commit Messages / 提交信息

- Use present tense ("Add feature" not "Added feature")
  使用现在时态（"Add feature" 而不是 "Added feature"）
- Use imperative mood ("Move cursor to..." not "Moves cursor to...")
  使用祈使语气（"Move cursor to..." 而不是 "Moves cursor to..."）
- Keep first line under 50 characters
  第一行保持在 50 个字符以内
- Reference issues and pull requests after the first line
  在第一行之后引用 issue 和 pull request

---

## Community / 社区

- **GitHub Issues**: For bug reports and feature requests
  用于错误报告和功能请求
- **GitHub Discussions**: For questions and general discussion
  用于问题和一般讨论

---

## Questions? / 有问题？

If you have questions about contributing, feel free to open an issue or start a discussion.

如果你对贡献有疑问，欢迎提交 issue 或开始讨论。

---

Thank you for contributing to 2lang! 🎉

感谢你为 2lang 做出贡献！🎉
