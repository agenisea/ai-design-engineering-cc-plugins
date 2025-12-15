# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in this plugin, please report it responsibly:

1. **Do not** open a public issue
2. Email the maintainers directly or use GitHub's private vulnerability reporting feature
3. Include a detailed description of the vulnerability
4. Provide steps to reproduce if possible

We will respond within 48 hours and work with you to understand and address the issue.

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| Latest  | Yes                |

## Security Considerations

### Plugin Architecture

This plugin is designed with security in mind:

- **No external dependencies** — All functionality is self-contained within Claude Code
- **No data collection** — Your prompts and outputs stay local to your Claude Code session
- **No network calls** — The plugin itself makes no network requests; all API calls are handled by Claude Code
- **Open source** — Full transparency for security audits

### Prompt Injection

The **Argus** persona helps design defenses against prompt injection attacks in your agentic systems:

- Input validation and sanitization
- Structured output enforcement
- Capability restrictions
- Trust boundary definitions

### Data Handling

This plugin:

- Does not store any user data
- Does not log prompts or outputs
- Does not transmit data to external services
- Operates entirely within Claude Code's security model

## Best Practices for Users

1. **Review generated architectures** — Always review security recommendations before implementation
2. **Validate outputs** — Use Argus outputs as a starting point, not a final solution
3. **Keep Claude Code updated** — Security improvements are delivered through Claude Code updates
4. **Report issues** — Help us improve by reporting any security concerns

## Security Features by Persona

### Argus (Security Architecture)

Specifically designed for security architecture:

- Threat modeling
- Zero trust architecture
- Defense in depth patterns
- Authentication/authorization design
- Audit logging specifications
- Prompt injection defenses

### All Personas

Every persona includes:

- Safety guardrails in system prompts
- Scope restrictions to prevent off-topic behavior
- Clear boundaries for agent capabilities
