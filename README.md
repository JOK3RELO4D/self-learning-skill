# Self-Learning Skill

Autonomous skill generator that enables AI agents to learn new technologies from the web. Use this skill when you want to research a library, framework, or tool and generate reusable documentation/skills from authoritative sources.

## Usage

```
/learn <topic>
```

The skill will:

1. **Discover** authoritative documentation via web search
2. **Extract** relevant content from official sources
3. **Synthesize** information into a reusable skill
4. **Save** the generated skill to your workspace

## Installation

Copy the `SKILL.md` and `references/` folder to your agent's skills directory:

- **Workspace-specific**: `.agent/skills/self-learning/`
- **Global**: `~/.gemini/antigravity/skills/self-learning/`

## Contents

```
self-learning/
├── skills/self-learning/
│   ├── SKILL.md                 # Main skill instructions
│   └── references/
│       └── skill_creation_guide.md  # Reference for creating effective skills
├── README.md
└── LICENSE
```

## Acknowledgements

This skill format is inspired by [hyperbrowserai/examples/skills](https://github.com/hyperbrowserai/examples/tree/main/skills).

## License

Apache License 2.0 - See [LICENSE](LICENSE) for details.
