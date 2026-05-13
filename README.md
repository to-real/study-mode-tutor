# Study Mode Tutor Skill / 学习模式辅导 Skill

## Description / 简介

**EN:** A portable Codex skill that turns an AI assistant into a guided study-mode tutor. It helps users learn through Socratic questions, hints, step-by-step scaffolding, short practice loops, and teach-back, while avoiding direct answers to homework or graded work.

**中文：** 这是一个可移植的 Codex Skill，用来让 AI 助手进入“学习模式”。它通过苏格拉底式提问、提示、分步引导、小练习和复述检查来帮助用户真正学会，而不是直接替用户完成作业或考试题。

## What It Does / 功能

- **EN:** Guides users through concepts step by step.
- **中文：** 引导用户一步一步理解概念。
- **EN:** Helps with homework without completing graded work for the user.
- **中文：** 可以辅导作业，但不会直接代做。
- **EN:** Supports math, logic, language practice, exam prep, and uploaded assignment images.
- **中文：** 支持数学、逻辑、语言练习、备考，以及上传题目图片后的辅导。
- **EN:** Uses Socratic questions, scaffolding, retrieval practice, and teach-back.
- **中文：** 使用提问式教学、脚手架引导、主动回忆和“让用户反过来讲一遍”的方式巩固学习。
- **EN:** Responds in the user's language.
- **中文：** 默认使用用户当前使用的语言回应。

## Install / 安装

**Manual install / 手动安装：**

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

如果你的 Skill 管理器支持通过 GitHub URL 安装，也可以直接使用这个仓库地址安装。

## Use / 使用

Example prompts / 示例提示词：

```text
Use study-mode-tutor to help me understand quadratic equations.
```

```text
Use study-mode-tutor. I have this homework problem, but don't give me the answer directly.
```

```text
Use study-mode-tutor to quiz me for my biology exam, one question at a time.
```

```text
使用 study-mode-tutor 帮我学习二次函数。请一步一步引导我，不要直接给答案。
```

```text
使用 study-mode-tutor 帮我备考生物，一次问我一道题。
```

## Files / 文件

- `SKILL.md`: skill instructions and trigger metadata. / Skill 指令和触发描述。
- `agents/openai.yaml`: UI metadata for skill lists and default prompt. / Skill 列表和默认提示词的 UI 元数据。

## License / 许可证

MIT
