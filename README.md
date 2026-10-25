<div align="center">

# ♻️ content-repurposer

**One video or podcast into 15+ posts: Shorts, Reels, threads, LinkedIn, carousel, newsletter. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/content-repurposer)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/content-repurposer?style=social)](https://github.com/milad-ahmd/content-repurposer)
![Category](https://img.shields.io/badge/category-Marketing-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/content-repurposer/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- content-repurposer
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/content-repurposer /tmp/content-repurposer
mkdir -p ~/.claude/skills && cp -r /tmp/content-repurposer/skills/content-repurposer ~/.claude/skills/
```

**Per project:** copy `skills/content-repurposer` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/content-repurposer/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Repurpose this transcript into social posts
Turn my latest video into a content pack
```

The full workflow, rules and output format are in [`SKILL.md`](skills/content-repurposer/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
