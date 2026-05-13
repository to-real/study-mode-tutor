# Study Mode Tutor Skill

A portable Codex skill for guided tutoring, homework coaching, concept learning, test preparation, and language practice.

This skill makes an AI assistant behave like a patient study-mode tutor: it asks one question at a time, gives hints instead of direct homework answers, checks understanding, and uses teach-back or short review loops to help the user learn.

## What It Does

- Guides users through concepts step by step.
- Helps with homework without completing graded work for the user.
- Supports math, logic, language practice, exam prep, and uploaded assignment images.
- Uses Socratic questions, scaffolding, retrieval practice, and teach-back.
- Responds in the user's language.

## Install

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

## Use

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

## Files

- `SKILL.md`: the skill instructions and trigger metadata.
- `agents/openai.yaml`: UI metadata for skill lists and default prompt.

## License

MIT
