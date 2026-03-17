<p align="center">
  <img src="https://img.shields.io/badge/Claude%20Code-Skill-8A2BE2?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude Code Skill">
</p>

<h1 align="center">Claude Design Skills</h1>

<p align="center">
  <strong>Complete Design Toolkit for Claude Code</strong>
  <br>
  <em>7 specialized skills covering generative art, visual design, frontend UI, theming, and brand identity</em>
</p>

<p align="center">
  <a href="https://github.com/LeoLin990405/claude-design-skills/stargazers"><img src="https://img.shields.io/github/stars/LeoLin990405/claude-design-skills?style=flat-square" alt="Stars"></a>
  <a href="https://github.com/LeoLin990405/claude-design-skills/issues"><img src="https://img.shields.io/github/issues/LeoLin990405/claude-design-skills?style=flat-square" alt="Issues"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/LeoLin990405/claude-design-skills?style=flat-square" alt="License"></a>
  <img src="https://img.shields.io/badge/skills-7-green?style=flat-square" alt="Skills: 7">
  <img src="https://img.shields.io/badge/p5.js-ED225D?style=flat-square&logo=p5.js&logoColor=white" alt="p5.js">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
</p>

<p align="center">
  <a href="#skills">Skills</a> &bull;
  <a href="#quick-start">Quick Start</a> &bull;
  <a href="#project-structure">Project Structure</a> &bull;
  <a href="#contributing">Contributing</a> &bull;
  <a href="#license">License</a>
</p>

---

## Skills

| Skill | Category | Description |
|-------|----------|-------------|
| **[algorithmic-art](skills/algorithmic-art/SKILL.md)** | Generative | Create algorithmic art using p5.js with seeded randomness &mdash; flow fields, particle systems, interactive explorations |
| **[canvas-design](skills/canvas-design/SKILL.md)** | Visual | Design posters, visual art, and static compositions as PNG/PDF with 30+ bundled fonts |
| **[frontend-design](skills/frontend-design/SKILL.md)** | Frontend | Build distinctive, production-grade web components, pages, and dashboards |
| **[web-artifacts-builder](skills/web-artifacts-builder/SKILL.md)** | Frontend | Scaffold multi-component Claude.ai HTML artifacts with React, Tailwind CSS, and shadcn/ui |
| **[theme-factory](skills/theme-factory/SKILL.md)** | Theming | Apply one of 10 curated color/font themes to any artifact, or generate a new theme on the fly |
| **[slack-gif-creator](skills/slack-gif-creator/SKILL.md)** | Media | Create animated GIFs optimized for Slack with validation tools and easing utilities |
| **[brand-guidelines](skills/brand-guidelines/SKILL.md)** | Brand | Apply Anthropic's official brand colors and typography to any artifact |

---

## Quick Start

### Installation

```bash
cd ~/.claude/skills
git clone https://github.com/LeoLin990405/claude-design-skills.git
```

### Usage

Claude Code automatically routes your request to the right skill:

```text
"Create generative art"           -> algorithmic-art
"Design a poster"                 -> canvas-design
"Build a landing page"            -> frontend-design
"Create a React artifact"         -> web-artifacts-builder
"Apply a dark theme"              -> theme-factory
"Make a Slack GIF"                -> slack-gif-creator
"Use Anthropic brand colors"      -> brand-guidelines
```

You can also invoke a skill directly by name in your prompt.

---

## Project Structure

```
claude-design-skills/
├── SKILL.md                          # Root skill index (Claude Code entry point)
├── README.md
├── LICENSE                           # MIT
├── CONTRIBUTING.md
├── CHANGELOG.md
├── .github/
│   ├── workflows/
│   │   └── claude-review.yml         # CI workflow
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml
│   │   ├── feature_request.yml
│   │   └── config.yml
│   └── PULL_REQUEST_TEMPLATE.md
└── skills/
    ├── algorithmic-art/              # p5.js generative art
    │   ├── SKILL.md
    │   └── templates/
    ├── canvas-design/                # Visual design with 30+ fonts
    │   ├── SKILL.md
    │   └── canvas-fonts/
    ├── frontend-design/              # Production-grade frontend UI
    │   └── SKILL.md
    ├── web-artifacts-builder/        # React/shadcn artifact scaffolding
    │   ├── SKILL.md
    │   └── scripts/
    ├── theme-factory/                # 10 curated themes
    │   ├── SKILL.md
    │   └── themes/
    ├── slack-gif-creator/            # Animated GIF toolkit
    │   ├── SKILL.md
    │   ├── core/
    │   └── requirements.txt
    └── brand-guidelines/             # Anthropic brand styling
        └── SKILL.md
```

---

## Contributing

Contributions are welcome! Please read the [Contributing Guide](CONTRIBUTING.md) before submitting a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
  <sub>Built with collaboration between human and AI</sub>
</p>
