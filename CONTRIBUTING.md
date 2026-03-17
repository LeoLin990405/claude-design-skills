# Contributing to Claude Design Skills

Thank you for your interest in contributing! This guide will help you get started.

## How to Contribute

### Reporting Bugs

- Use the [Bug Report](https://github.com/LeoLin990405/claude-design-skills/issues/new?template=bug_report.yml) issue template.
- Include the skill name, steps to reproduce, and expected vs. actual behavior.

### Suggesting Features

- Use the [Feature Request](https://github.com/LeoLin990405/claude-design-skills/issues/new?template=feature_request.yml) issue template.
- Describe the use case and how it fits with the existing skill set.

### Submitting Pull Requests

1. **Fork** the repository and create your branch from `main`.
2. **Follow the existing structure** &mdash; each skill lives in `skills/<skill-name>/` with a `SKILL.md` front-matter header.
3. **Include a LICENSE.txt** in your skill directory if it has its own license terms.
4. **Test your skill** by installing it locally (`cd ~/.claude/skills && git clone <your-fork>`).
5. **Open a pull request** using the provided PR template.

## Skill Structure

Every skill must include a `SKILL.md` with YAML front matter:

```yaml
---
name: my-skill
description: Short description of what the skill does and when to use it.
license: Complete terms in LICENSE.txt
---

# Skill Title

Detailed instructions for Claude Code...
```

### Naming Conventions

- Skill directory names use `kebab-case`.
- Keep descriptions concise but include trigger keywords so Claude Code can route requests correctly.

## Code of Conduct

Be respectful, constructive, and collaborative. We follow the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

## Questions?

Open a [discussion](https://github.com/LeoLin990405/claude-design-skills/issues) or reach out to [@LeoLin990405](https://github.com/LeoLin990405).
