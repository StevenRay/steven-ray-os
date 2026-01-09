# steven-ray-os

Claude Code skills for product building, design standards, and code quality. How I work.

## What This Is

My personal configuration for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Five modular skills that define how I build products, evaluate design, write code, and handle emergencies.

25+ years of product instinct, packaged for AI collaboration.

## Skills

| Skill | What It Does |
|-------|--------------|
| **steven-ray-core** | Communication style, decision framework, working preferences |
| **product-process** | 7-phase workflow from understand to ship |
| **design-standards** | Awwwards criteria, aesthetic direction, UI quality gates |
| **code-standards** | Quality gates, testing requirements, default tech stack |
| **emergency-protocols** | Incident response, troubleshooting, when things break |

## Installation

```bash
# Clone the repo
git clone https://github.com/stevenray/steven-ray-os.git

# Copy skills to Claude Code
cp -r steven-ray-os/skills/* ~/.claude/skills/
```

## How It Works

Claude Code automatically loads skills based on context:

- Start a new project → `product-process` loads
- Design a UI → `design-standards` loads
- Write code → `code-standards` loads
- Something breaks → `emergency-protocols` loads
- Always → `steven-ray-core` shapes the collaboration style

No manual invocation needed. Claude reads the skill descriptions and loads what's relevant.

## The Philosophy

- **Cofounder energy, not assistant mode.** Push back. Have opinions.
- **Facts only.** Never fabricate APIs, libraries, or capabilities.
- **Ship at 70%.** Done beats perfect.
- **No AI slop.** Distinctive or don't ship.
- **Research first.** Verify before claiming something works.

## Who I Am

Steven Ray. 25+ years building digital products. Co-founded Dialexa (scaled to 300+, sold to IBM). Currently CCO at Concord Servicing, building Stoodio and other ventures.

Based in Sunnyvale, TX. Golf addiction. Direct communication. Strong opinions, loosely held.

## Customizing

Fork this and make it yours. The structure works for any personal operating system:

```
your-os/
├── README.md
├── skills/
│   ├── your-core/
│   │   └── SKILL.md
│   ├── your-process/
│   │   └── SKILL.md
│   └── ...
└── commands/
```

## License

MIT. Take what's useful.

---

*"AI basics get you farther than most."*
