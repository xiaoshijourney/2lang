# 2lang

A Claude Code skill that enables bilingual responses in English and Chinese with persona support.

一个让 Claude 用英文和中文双语回复的技能，支持人格选择。

## Features / 功能

- Bilingual output in English and Chinese

  英中双语输出

- Dynamic language order based on user's input

  根据用户输入动态调整语言顺序

- 5 selectable personas with distinct styles

  5 种可选人格，风格各异

- Persona switching anytime

  随时切换人格

## Installation / 安装

To install this skill, copy the `SKILL.md` file to your Claude skills directory:

安装此技能，将 `SKILL.md` 文件复制到你的 Claude 技能目录：

```bash
# Windows
copy SKILL.md %USERPROFILE%\.claude\skills\2lang\SKILL.md

# macOS/Linux
cp SKILL.md ~/.claude/skills/2lang/SKILL.md
```

## Usage / 使用

Once installed, activate the skill by typing:

安装后，输入以下命令激活技能：

```
/2lang
```

On first load, you'll be asked to choose a persona.

首次加载时，系统会请你选择人格。

To switch persona later:

切换人格：

```
switch persona
切换人格
```

## Personas / 人格

| Persona | Style / 风格 |
|---------|-------------|
| Default / 默认 | Natural, no special style / 自然风格，无特殊修饰 |
| Professional / 专业 | Formal, precise, business-like / 正式、精确、商务风格 |
| Friendly / 友好 | Casual, warm, approachable / 随意、亲切、平易近人 |
| Teacher / 导师 | Patient, explanatory, educational / 耐心、解释性强、教育风格 |
| Tech Expert / 技术专家 | Concise, technical, code-focused / 简洁、技术性强、代码导向 |
| Creative / 创意 | Imaginative, expressive, playful / 富有想象力、表达丰富、活泼 |

## Rules / 规则

1. Always provide responses in both English and Chinese

   始终提供英文和中文双语回复

2. Language order matches user's input language

   语言顺序与用户输入语言一致

3. Each paragraph/sentence should be translated separately

   每个段落/句子应分别翻译

4. Keep both versions natural and fluent — not word-for-word translation

   保持两个版本自然流畅——不要逐字翻译

5. Code blocks remain as-is (no translation needed)

   代码块保持原样，无需翻译

6. Match the chosen persona's tone and style

   保持所选人格的语气和风格

## License

MIT
