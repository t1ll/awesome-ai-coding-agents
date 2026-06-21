# Contributing

Contributions are welcome. Please read this guide before opening a pull request.

## What belongs in this list

This registry is for resources that help AI agents, coding assistants, and developers write, review, test, debug, or maintain code. Acceptable entries include:

- AI coding agents and agentic coding assistants (IDEs, CLI tools, autonomous agents).
- Code review agents and automated PR reviewers.
- Test-generation agents and tools.
- Language- or framework-specific coding agents.
- Open-source frameworks and libraries for building coding agents.
- Commercial tools whose primary value proposition is agentic software engineering.

## What does **not** belong

- General-purpose LLM chat interfaces without coding-specific features.
- Model cards, model weights, or inference engines that are not coding-agent tooling.
- General SDK documentation or tutorials that are not agent/coding-assistant oriented.
- Closed-source or paywalled-only tools with no public documentation.
- Duplicate entries.

## Quality bar

Every submission must be:

1. **Publicly accessible** — open source or publicly documented.
2. **Actively maintained** — last meaningful commit or release within the last 12 months (exceptions for widely adopted reference projects).
3. **Documented** — a real README or docs page with setup or install instructions.
4. **Correctly categorized** — placed under the category that best describes its primary interface.
5. **Honestly labeled** — use the `Official` or `Community` badge.

## Entry format

Use this pattern:

```markdown
- **[Name](URL)** `Official` — One-sentence description.
  - Install: `command here`
```

If there is no install command, omit the install line.

## Category sections

The README is organized by **agent interface or purpose**, not by vendor. New sections are allowed only if they contain at least five entries.

## Pull request process

1. Fork the repository.
2. Add your entry in the correct category section.
3. Run `./scripts/validate-links.sh` and fix any broken links or anchors.
4. Open a pull request with a clear description of the resource and why it fits.

One resource per pull request is preferred.
