# Study Mode Tutor Skill

<p align="center">
  <a href="#中文"><img src="https://img.shields.io/badge/中文-阅读-blue" alt="中文"></a>
  <a href="#english"><img src="https://img.shields.io/badge/English-Read-green" alt="English"></a>
</p>

## 中文

### 简介

`study-mode-tutor` 是一个可移植的 Codex Skill，由 ChatGPT 学习模式的提示词演化而来。

它会让 AI 助手进入“学习模式”：通过苏格拉底式提问、提示、分步引导、小练习和复述检查来帮助用户真正学会，而不是直接替用户完成作业或考试题。

### 功能

- 引导用户一步一步理解概念。
- 可以辅导作业，但不会直接代做。
- 支持数学、逻辑、语言练习、备考，以及上传题目图片后的辅导。
- 使用提问式教学、脚手架引导、主动回忆和“让用户反过来讲一遍”的方式巩固学习。
- 默认使用用户当前使用的语言回应。

### 安装

手动安装：

1. 将这个文件夹复制到你的 Codex skills 目录。
2. 最终路径应该类似：

```text
~/.codex/skills/study-mode-tutor/SKILL.md
```

Windows PowerShell 通常是：

```powershell
$env:USERPROFILE\.codex\skills\study-mode-tutor
```

如果你的 Skill 管理器支持通过 GitHub URL 安装，也可以直接使用这个仓库地址安装。

### 使用示例

```text
使用 study-mode-tutor 帮我学习二次函数。请一步一步引导我，不要直接给答案。
```

```text
使用 study-mode-tutor 帮我备考生物，一次问我一道题。
```

```text
使用 study-mode-tutor。这里有一道作业题，请先提示我怎么想，不要直接解答。
```

### 文件

- `SKILL.md`：Skill 指令和触发描述。
- `agents/openai.yaml`：Skill 列表和默认提示词的 UI 元数据。

### 许可证

MIT

## English

### Description

`study-mode-tutor` is a portable Codex Skill evolved from the ChatGPT Study Mode prompt.

It turns an AI assistant into a guided study-mode tutor: it uses Socratic questions, hints, step-by-step scaffolding, short practice loops, and teach-back to help users learn, while avoiding direct answers to homework or graded work.

### What It Does

- Guides users through concepts step by step.
- Helps with homework without completing graded work for the user.
- Supports math, logic, language practice, exam prep, and uploaded assignment images.
- Uses Socratic questions, scaffolding, retrieval practice, and teach-back.
- Responds in the user's language.

### Install

Manual install:

1. Copy this folder to your Codex skills directory.
2. The final path should look like:

```text
~/.codex/skills/study-mode-tutor/SKILL.md
```

On Windows PowerShell, that is usually:

```powershell
$env:USERPROFILE\.codex\skills\study-mode-tutor
```

If your skill manager supports GitHub URL installs, install this repository URL directly.

### Use

Example prompts:

```text
Use study-mode-tutor to help me understand quadratic equations.
```

```text
Use study-mode-tutor. I have this homework problem, but don't give me the answer directly.
```

```text
Use study-mode-tutor to quiz me for my biology exam, one question at a time.
```

### Files

- `SKILL.md`: skill instructions and trigger metadata.
- `agents/openai.yaml`: UI metadata for skill lists and default prompt.

### License

MIT
