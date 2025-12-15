# Contributing to AI Design Engineer Plugin

Thanks for your interest in contributing to the AI Design Engineer plugin for Claude Code!

## Getting Started

1. Fork the repository
2. Clone your fork locally
3. Make your changes
4. Test with Claude Code locally

## Development Workflow

```bash
# Add the local marketplace for testing
/plugin marketplace add ./

# Install the plugin
/plugin install ai-design-engineer@agenisea

# Test your changes
/bliss
/blueprompt
/agenisea
/argus
/brooks
```

## How to Contribute

### Reporting Bugs

- Check existing issues first to avoid duplicates
- Use a clear, descriptive title
- Include steps to reproduce the issue
- Describe expected vs actual behavior

### Suggesting Features

- Open an issue describing the feature
- Explain the use case and why it would be valuable
- Be open to discussion about implementation approaches

### Pull Requests

1. Create a branch from `main` for your changes
2. Make your changes with clear, focused commits
3. Test all commands and skills locally
4. Open a PR with a clear description of changes
5. Link any related issues

## Code Style

- Follow existing patterns in the codebase
- Keep commands, agents, and skills focused and single-purpose
- Use consistent YAML frontmatter structure
- Include `## Research First` sections in commands/skills
- Include `## Tone` sections for persona consistency

## Areas for Contribution

- **New personas**: Add specialized agents for other design domains
- **Prompt improvements**: Enhance system prompts for better output
- **Trigger phrases**: Improve skill activation descriptions
- **Documentation**: Examples, tutorials, use cases
- **Translations**: Localized versions of prompts

## Plugin Structure

```
claude-code/plugins/ai-design-engineer/
├── .claude-plugin/
│   └── plugin.json       # Plugin manifest
├── commands/             # Slash commands
├── agents/               # Subagent definitions
└── skills/               # Agent skills (SKILL.md)
```

## Questions?

Open an issue or reach out to the maintainers. We're happy to help!
