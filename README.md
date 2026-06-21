# 2lang

A Claude Code skill that enables multilingual responses with persona support.

一个让 Claude 用多语回复的技能，支持人格选择。

## Features / 功能

- Choose 1-2 languages for responses

  选择 1-2 种回复语言

- Dynamic language order based on user's input

  根据用户输入动态调整语言顺序

- 5 selectable personas with distinct styles

  5 种可选人格，风格各异

- Persona and language switching anytime

  随时切换人格和语言

## Installation / 安装

To install this skill, copy the `2lang` folder to your Claude skills directory:

安装此技能，将 `2lang` 文件夹复制到你的 Claude 技能目录：

```bash
# Windows
xcopy 2lang %USERPROFILE%\.claude\skills\2lang\ /E /I

# macOS/Linux
cp -r 2lang ~/.claude/skills/2lang
```

## Usage / 使用

Once installed, activate the skill by typing:

安装后，输入以下命令激活技能：

```
/2lang
```

On first load, you'll be asked to choose 1-2 languages, then a persona.

首次加载时，系统会请你选择 1-2 种语言，然后选择人格。

To switch languages later:

切换语言：

```
switch languages
切换语言
```

To switch persona later:

切换人格：

```
switch persona
切换人格
```

## Languages / 语言

| Language / 语言 |
|----------------|
| English / 英语 |
| Chinese / 中文 |
| Japanese / 日本語 |
| Korean / 한국어 |
| French / Français |
| Deutsch / 德语 |
| Español / 西班牙语 |

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

1. Always provide responses in all chosen languages.

   始终用所有选择的语言回复。

2. If only one language is chosen, respond in that language only.

   如果只选择了一种语言，仅用该语言回复。

3. If two languages are chosen, the primary language matches user's input language.

   如果选择了两种语言，主要语言与用户输入语言一致。

4. Each paragraph/sentence should be translated separately with a blank line between languages.

   每个段落/句子应分别翻译，语言之间用空行分隔。

5. Keep both versions natural and fluent — not word-for-word translation.

   保持两个版本自然流畅——不要逐字翻译。

6. Code blocks remain as-is (no translation needed).

   代码块保持原样，无需翻译。

7. Match the chosen persona's tone and style in all languages.

   在所有语言中保持所选人格的语气和风格。

## License

MIT
