# 2l-answer-with-eng-and-chzn

A Claude Code skill that enables bilingual responses in English and Chinese.

一个让 Claude 用英文和中文双语回复的技能。

## Description

This skill instructs Claude to respond in both English and Chinese, with English text first followed by the Chinese translation. Perfect for users who want to see responses in both languages simultaneously.

此技能指示 Claude 用英文和中文双语回复，英文在前，中文翻译在后。非常适合希望同时看到两种语言回复的用户。

## Installation

To install this skill, copy the `SKILL.md` file to your Claude skills directory:

安装此技能，将 `SKILL.md` 文件复制到你的 Claude 技能目录：

```bash
# Windows
copy SKILL.md %USERPROFILE%\.claude\skills\2l-answer-with-eng-and-chzn\SKILL.md

# macOS/Linux
cp SKILL.md ~/.claude/skills/2l-answer-with-eng-and-chzn/SKILL.md
```

## Usage

Once installed, activate the skill by typing:

安装后，输入以下命令激活技能：

```
/2l-answer-with-eng-and-chzn
```

Or simply ask Claude to use the bilingual output skill.

或者直接要求 Claude 使用双语输出技能。

## Rules

1. Always provide responses in both English and Chinese

   始终提供英文和中文双语回复

2. English text comes first, followed by a blank line, then Chinese translation

   英文在前，空一行，然后是中文翻译

3. Each paragraph/sentence should be translated separately

   每个段落/句子应分别翻译

4. Keep both versions natural and fluent — not word-for-word translation

   保持两个版本自然流畅——不要逐字翻译

5. Code blocks remain as-is (no translation needed)

   代码块保持原样，无需翻译

## Example

This is an example response. It demonstrates the bilingual format.

这是一个示例回复。它展示了双语格式。

## License

MIT
