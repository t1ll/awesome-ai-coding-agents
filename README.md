# Awesome AI Coding Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

A curated registry of AI coding agents, agentic IDEs, autonomous engineering tools, and frameworks that write, review, test, and maintain code.

The goal is to be the definitive place to discover tools that turn natural-language intent into working software, whether through a chat interface, IDE, CLI, or fully autonomous loop.

**Inclusion criteria:** Resources must be purpose-built for coding assistance or agentic software engineering. General-purpose LLM chat apps, model cards, and non-coding agents are out of scope. See [CONTRIBUTING.md](./CONTRIBUTING.md) for the full quality bar.

---

## Contents

- [Agentic IDEs](#agentic-ides)
- [CLI Coding Agents](#cli-coding-agents)
- [Autonomous Agents](#autonomous-agents)
- [Code Review Agents](#code-review-agents)
- [Test Generation](#test-generation)
- [Agents for Specific Languages](#agents-for-specific-languages)
- [Open-Source Frameworks](#open-source-frameworks)
- [Commercial Tools](#commercial-tools)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

---

## Agentic IDEs

AI-native integrated development environments where an agent is the primary coding partner.

- **[Cursor](https://www.cursor.com/)** `Official` — AI-first IDE built on VS Code with composer, tab completion, and codebase-aware chat.
- **[Windsurf](https://www.codeium.com/windsurf)** `Official` — Codeium's agentic IDE with cascade editing and contextual awareness.
- **[Zed AI](https://zed.dev/)** `Official` — High-performance multiplayer code editor with built-in AI assistant and agentic editing.
- **[Augment Code](https://www.augmentcode.com/)** `Official` — Enterprise agentic coding assistant deeply integrated into VS Code and JetBrains IDEs.
- **[Trae](https://www.trae.ai/)** `Official` — ByteDance's AI-native IDE with agent mode and multi-file edits.
- **[PearAI](https://pearai.com/)** `Community` — Open-source AI code editor combining chat, agents, and code review in one workspace.
- **[Replit Agent](https://replit.com/ai)** `Official` — Replit's autonomous coding agent that builds and deploys full projects from prompts.
- **[CodeSandbox](https://codesandbox.io/)** `Official` — Cloud development platform with AI-assisted editing and instant deploy previews.
- **[Podium](https://podium.do/)** `Community` — Open-source workspace for coordinating coding agents through shared issues, dependencies, and conversational delegation.

---

## CLI Coding Agents

Terminal-based agents you drive from the command line.

- **[Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview)** `Official` — Anthropic's research-grade CLI coding agent with tool use and project-wide reasoning.
  - Run: `claude`
- **[OpenAI Codex CLI](https://github.com/openai/codex)** `Official` — OpenAI's official CLI agent for codebase understanding and editing.
  - Install: `npm install -g @openai/codex`
- **[Gemini CLI](https://github.com/google-gemini/gemini-cli)** `Official` — Google's command-line coding assistant with repository context.
  - Install: `npm install -g @google/gemini-cli`
- **[Aider](https://github.com/Aider-AI/aider)** `Community` — Open-source pair-programming CLI that edits code in your local git repo.
  - Install: `pip install aider-chat`
- **[OpenCode](https://github.com/anomalyco/opencode)** `Community` — Open-source terminal, desktop, and IDE coding agent with built-in planning and build modes.
  - Install: `curl -fsSL https://opencode.ai/install | bash`

---

## Autonomous Agents

Agents that run longer workflows, plan tasks, and iterate toward a goal with limited human intervention.

- **[Devin](https://devin.ai/)** `Official` — Cognition's autonomous AI software engineer that plans, codes, tests, and deploys end-to-end.
- **[OpenHands](https://github.com/All-Hands-AI/OpenHands)** `Community` — Open-source autonomous software engineering agent with multi-step task planning.
  - Run: `docker run -it --rm --pull always -e SANDBOX_USER_ID=$(id -u) -e WORKSPACE_MOUNT_PATH=$(pwd) -v $(pwd):/workspace:rw -p 3000:3000 -e LOG_ALL_EVENTS=true allhands/openhands:main`
- **[SWE-agent](https://github.com/princeton-nlp/SWE-agent)** `Community` — Princeton NLP agent that edits real GitHub issues using a custom reasoning interface.
  - Install: `pip install swe-agent`
- **[Agentless](https://github.com/princeton-nlp/Agentless)** `Community` — Princeton NLP approach to autonomous software engineering without an explicit agent loop.
- **[AutoCodeRover](https://github.com/nus-apr/auto-code-rover)** `Community` — NUS automated program repair agent for bug fixing and feature implementation.
- **[Devika](https://github.com/stitionai/devika)** `Community` — Open-source autonomous coding agent inspired by early Devin demos.
- **[Morph](https://www.morph.so/)** `Official` — Autonomous coding agent for building and shipping software projects.
- **[Amazon Q Developer Agent](https://aws.amazon.com/q/developer/)** `Official` — AWS agent that implements features, fixes bugs, and upgrades code from natural-language requests.
- **[GitHub Copilot Workspace](https://github.com/features/copilot)** `Official` — Task-oriented agent that turns issues into implementation plans and pull requests.

---

## Code Review Agents

Agents focused on reviewing pull requests, spotting issues, and suggesting improvements.

- **[CodeRabbit](https://coderabbit.ai/)** `Official` — AI-powered pull-request reviewer with line-by-line comments and chat.
- **[PR-Agent](https://github.com/Codium-ai/pr-agent)** `Official` — Open-source PR review agent that summarizes, reviews, and suggests improvements.
  - Install: `pip install pr-agent`
- **[Sourcery](https://sourcery.ai/)** `Official` — AI code reviewer and refactoring assistant for Python, JavaScript, TypeScript, and more.
- **[Greptile](https://greptile.com/)** `Official` — Code review agent that understands your entire codebase and PR diffs.
- **[What The Diff](https://whatthediff.ai/)** `Official` — AI assistant that writes PR descriptions and reviews code changes.
- **[CodeSee](https://www.codesee.io/)** `Official` — Code visualization platform with AI-powered PR review and onboarding.
- **[Amazon Q Developer Code Review](https://aws.amazon.com/q/developer/)** `Official` — AWS agent that reviews code for security, quality, and best practices.
- **[GitHub Copilot Code Review](https://github.com/features/copilot)** `Official` — Native AI code review integrated into GitHub pull requests.

---

## Test Generation

Tools that automatically write, run, and maintain tests.

- **[Qodo](https://www.qodo.ai/)** `Official` — AI test-generation suite for unit, integration, and behavior-driven tests.
- **[Pythagora](https://www.pythagora.ai/)** `Official` — Autonomous agent that builds Node.js features together with their tests.
- **[Keploy](https://keploy.io/)** `Official` — Open-source API test generation from user traffic and mocks.
  - Install: `curl --silent -O https://raw.githubusercontent.com/keploy/keploy/main/keploy.sh && source keploy.sh`
- **[Octomind](https://octomind.dev/)** `Official` — AI agent that discovers, generates, and maintains end-to-end UI tests.
- **[Testim](https://www.tricentis.com/testim)** `Official` — AI-based test authoring and maintenance for web applications.
- **[Testsigma](https://testsigma.com/)** `Official` — Low-code test automation platform with AI-driven test generation and healing.

---

## Agents for Specific Languages

Agents and builders optimized for particular languages or frameworks.

- **[v0](https://v0.dev/)** `Official` — Vercel's AI agent for generating React, Next.js, and Tailwind UI components and apps.
- **[Lovable](https://lovable.dev/)** `Official` — Natural-language full-stack app builder for React and Node.js projects.
- **[Bolt.new](https://bolt.new/)** `Official` — StackBlitz agent that builds and deploys web apps from prompts.
- **[Replit Agent](https://replit.com/ai)** `Official` — Multi-language agent for building and deploying projects in Replit.
- **[FlutterFlow AI Gen](https://www.flutterflow.io/)** `Official` — AI-assisted builder for Flutter and Dart mobile and web applications.
- **[CodeSandbox AI](https://codesandbox.io/)** `Official` — Cloud sandbox with AI-assisted JavaScript and TypeScript development.

---

## Open-Source Frameworks

Libraries and frameworks for building, orchestrating, and extending coding agents.

- **[Continue.dev](https://github.com/continuedev/continue)** `Community` — Open-source autopilot for VS Code and JetBrains that connects any model to any IDE action.
  - Install: search "Continue" in your IDE extension marketplace.
- **[Smolagents](https://github.com/huggingface/smolagents)** `Official` — Hugging Face minimal framework for building agents that write and run code.
  - Install: `pip install smolagents`
- **[LangGraph](https://github.com/langchain-ai/langgraph)** `Official` — LangChain library for building stateful, multi-actor agent workflows.
  - Install: `pip install langgraph`
- **[AutoGen](https://github.com/microsoft/autogen)** `Official` — Microsoft framework for multi-agent AI applications, including coding agents.
  - Install: `pip install pyautogen`
- **[CrewAI](https://github.com/joaomdmoura/crewai)** `Official` — Framework for orchestrating role-playing AI agent crews.
  - Install: `pip install crewai`
- **[LlamaIndex](https://github.com/run-llama/llama_index)** `Official` — Data framework for connecting LLMs to private data and agent tools.
  - Install: `pip install llama-index`
- **[DSPy](https://github.com/stanfordnlp/dspy)** `Official` — Stanford framework for algorithmically optimizing LLM prompts and agents.
  - Install: `pip install dspy`

---

## Commercial Tools

Paid products that add agentic coding assistance to existing workflows.

- **[GitHub Copilot](https://github.com/features/copilot)** `Official` — Microsoft's AI pair programmer for editors and GitHub.
- **[Tabnine](https://www.tabnine.com/)** `Official` — AI coding assistant with private deployment options for enterprises.
- **[Sourcegraph Cody](https://sourcegraph.com/cody)** `Official` — AI coding assistant with codebase search and context from Sourcegraph.
- **[JetBrains AI Assistant](https://www.jetbrains.com/ai/)** `Official` — Built-in AI assistant across JetBrains IDEs.
- **[Codeium](https://www.codeium.com/)** `Official` — Free AI code completion and chat for editors, also powering Windsurf.
- **[Supermaven](https://supermaven.com/)** `Official` — Fast AI code completion with large context windows.
- **[Pieces](https://pieces.app/)** `Official` — AI-enabled snippet manager and coding assistant for the desktop.

---

## Related Awesome Lists

- **[Awesome Oracle Agentic Skills & MCP Servers](../awesome-oracle-agentic-skills-mcp)** — Agentic skills and MCP servers for Oracle products.
- **[Awesome NVIDIA Agentic Skills & MCP Servers](../awesome-nvidia-agentic-skills-mcp)** — Agentic skills and MCP servers for NVIDIA platforms.
- **[Awesome Local LLMs](https://github.com/vince-lam/awesome-local-llms)** — Curated list of local LLM inference projects and tools.
- **[Awesome LLM](https://github.com/Hannibal046/Awesome-LLM)** — Curated list of open-source LLMs, training, and deployment resources.

---

## Contributing

Read [CONTRIBUTING.md](./CONTRIBUTING.md) for the quality bar, entry format, and PR process.

---

## License

This list is released into the public domain under [CC0-1.0](./LICENSE).

## Want us to build this for you?

Enterprise AI Atlas is maintained by [Vibe Coding Agency](https://vibecodingagency.com). We prototype and ship agentic systems, MCP servers, and enterprise AI integrations for teams that need working software fast — without hiring a full AI engineering team.

**Free guide:** [The Non-Technical Founder's Guide to Agentic AI](https://vibecodingagency.com/resources/white-papers/non-technical-founders-guide-agentic-ai.pdf) — what agents and MCP servers are, and how to get a system built.
