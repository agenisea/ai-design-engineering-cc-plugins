# Human-first AI Design Engineer Plugin for Claude Code

**Design resilient agentic applications with human-first methodology.**

Five specialized personas guide you from initial concept through security architecture—all within Claude Code.

## The Problem

Building agentic applications requires expertise across multiple domains: product architecture, multi-agent coordination, security, and frontend design. Most engineers approach these in isolation, leading to fragmented systems that fail under real-world conditions.

## The Solution

This plugin provides five expert personas that work together to create cohesive, resilient agentic systems:

- **Blueprompt** — Transform rough ideas into structured specifications
- **Brooks** — Design with human-first Jobs To Be Done methodology
- **Agenisea** — Architect multi-agent systems with resilience patterns
- **Argus** — Secure your agents with layered defenses
- **Bliss** — Create distinctive, human-centered interfaces

**Typical flow:** Blueprompt → Brooks → Agenisea → Argus → Bliss *(not required, but recommended)*

## How It Works

1. **Install the plugin** — Add the marketplace and install
2. **Choose a persona** — Use slash commands or trigger phrases
3. **Describe your need** — Provide context for your agentic application
4. **Get expert output** — Receive implementation-ready design artifacts

## Quick Start

```bash
# Add the marketplace
/plugin marketplace add agenisea/ai-design-engineering-cc-plugins

# Install the plugin
/plugin install ai-design-engineer@agenisea
```

## Commands

| Command | Description |
|---------|-------------|
| `/blueprompt` | Create app blueprints and agent prompts for v0, Lovable, Replit, or generic |
| `/brooks` | Design human-first agentic applications using Jobs To Be Done methodology |
| `/agenisea` | Design multi-agent system architectures |
| `/argus` | Design security architectures for agentic applications |
| `/bliss` | Create distinctive, human-centered frontend interfaces |

## Skills (Auto-Triggered)

Skills are automatically invoked by Claude based on trigger phrases:

| Skill | Trigger Phrases | Purpose |
|-------|-----------------|---------|
| **blueprompt** | "blueprompt", "app blueprompt" | App blueprints & agent prompts |
| **brooks** | "brooks", "jtbd brooks" | JTBD methodology for agents |
| **agenisea** | "agenisea", "agent infra", "agent arc" | Multi-agent architecture |
| **argus** | "argus", "agent sec", "agent auth" | Security architecture |
| **bliss** | "bliss", "bliss ui", "bliss ux" | Frontend design |

## The 5 Personas

### Blueprompt
Expert AI Product Architect. Transforms rough ideas into structured specifications for AI builders.

**Outputs:**
- Full Blueprompt (concept, users, flows, screens, data model, agent design)
- App-Only Prompt (copy-paste ready)
- Agent-Only Prompt (system prompt with guardrails)

### Brooks
Expert Agentic Systems Architect using human-first Jobs To Be Done methodology. Focuses on functional, emotional, and social dimensions.

*If you skip Brooks, expect rework later.*

**Outputs:**
- Job Definition
- Success Metrics
- Agent Architecture
- Maturity Roadmap
- Iteration Framework

### Agenisea
Expert Multi-Agent Systems Architect. Creates resilient AI architecture blueprints.

**Outputs:**
- Agent Topology
- Pipeline Orchestration
- Resilience Patterns
- Agent Contracts
- Implementation Scaffold
- Tech Stack Recommendations

### Argus
Expert Agentic Application Security Architect. Designs layered defenses for agentic systems.

**Outputs:**
- Threat Model
- Authentication Architecture
- Authorization Matrix
- Audit System
- Resilience Safeguards
- Human Escalation Rules
- Security Checklist

### Bliss
Expert Frontend Designer specializing in human-centered design. Creates distinctive, accessible interfaces with human-first values.

**Outputs:**
- Design Direction
- Production Code
- Style System (CSS variables, typography, color tokens)

## Usage Examples

### Create an App Blueprint & Agent Prompt
```
/blueprompt

Build a habit tracking app for remote workers who want to build better daily routines.
Target: generic
```

### Design Human-first Agentic Application
```
/brooks

Automate customer onboarding for a SaaS platform.
Users struggle with manual data entry and slow response times.
Success: 90% of customers complete onboarding without human intervention.
```

### Design Multi-Agent Architecture
```
/agenisea

Build a content moderation pipeline:
- 3 parallel review agents (text, image, video)
- 1 aggregator agent
- Sequential pattern with fallback to human review
- Token budget: 100k per request
```

### Design Agent Security
```
/argus

I have a multi-agent system with 4 agents handling customer data:
- Intake agent (receives requests)
- Processor agent (transforms data)
- Validator agent (checks compliance)
- Responder agent (sends results)

Need security architecture for SOC2 compliance.
```

### Create Human-Centered Frontend UI
```
/bliss

Build a dashboard for analytics with:
- Dark mode by default
- Data visualization cards
- Brutalist aesthetic
- Framework: React + Tailwind
```

## Security

This plugin follows security best practices:

- **No external dependencies** — All functionality is self-contained
- **No data collection** — Your prompts and outputs stay local
- **No network calls** — Except for Claude API (handled by Claude Code)
- **Open source** — Full transparency, audit the code yourself

The **Argus** persona specifically helps you design secure agentic systems with:
- Zero trust architecture
- Defense in depth
- Least privilege principles
- Comprehensive audit logging
- Prompt injection defenses

## Requirements

- Claude Code 1.0 or later
- No external dependencies

## Contributing

Contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Ways to contribute:
- **Add new personas** — Expand expertise areas
- **Improve prompts** — Enhance persona outputs
- **Report issues** — Help us improve quality
- **Share examples** — Document real-world usage

## License

MIT License — see [LICENSE](LICENSE) for details.

## Links

- [Repository](https://github.com/agenisea/ai-design-engineering-cc-plugins)
- [Issues](https://github.com/agenisea/ai-design-engineering-cc-plugins/issues)

---

Built by [Agenisea™](https://agenisea.ai) 🪼 | Human-first AI, Engineered with Integrity
