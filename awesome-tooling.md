# Awesome Tooling

A searchable list of currently-available **open-source** tooling for AI-assisted development — the default survey map for this repo's exercise loop (see `skills/tooling-survey`). Every entry is verified before inclusion: canonical repo link, real license, factual one-line description. Format: `- [Name](repo) — what it does. (LICENSE)`.

**Status: under assembly — MVP complete.** Every entry below was individually verified on 2026-08-06 (repo exists at the linked path, license read from the repo itself, archived status checked). Sections are periodically re-verified by an independent research loop; entries rejected for failing the license bar (no license, custom terms, NonCommercial clauses) are dropped rather than listed.

## Agent Harnesses & CLIs

Coding agents, agent CLIs, and IDE-integrated agents that drive development work. *Last verified: 2026-08-06.*

- [Aider](https://github.com/Aider-AI/aider) — Terminal-based AI pair programming assistant that edits code in a git repo through conversational dialogue. (Apache-2.0)
- [AutoCode](https://github.com/FengyuanYin/AutoCode) — Cross-platform terminal AI coding agent with tool calling, MCP support, and project-aware context. (MIT)
- [Cline](https://github.com/cline/cline) — Autonomous coding agent available as an SDK, IDE extension, and CLI assistant that reads, writes, and executes code. (Apache-2.0)
- [Codex](https://github.com/openai/codex) — Lightweight coding agent that runs in the terminal. (Apache-2.0)
- [Continue](https://github.com/continuedev/continue) — Open-source coding agent and code-completion extension for VS Code and JetBrains IDEs. (Apache-2.0)
- [Devika](https://github.com/stitionai/devika) — Agentic AI software engineer that plans, researches, and writes code toward high-level objectives. (MIT)
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) — Open-source AI agent that brings Gemini into the terminal for coding and task automation. (Apache-2.0)
- [Goose](https://github.com/aaif-goose/goose) — Local, extensible AI agent that automates coding and engineering tasks from the desktop or CLI. (Apache-2.0)
- [Kilo Code](https://github.com/Kilo-Org/kilocode) — Agentic engineering platform for planning, building, and fixing code in the IDE. (MIT)
- [OpenCode](https://github.com/anomalyco/opencode) — Open-source terminal coding agent that reads, writes, and creates files while executing shell commands. (MIT)
- [OpenHands](https://github.com/OpenHands/OpenHands) — Platform for AI-driven development that runs autonomous coding agents in sandboxed containers. (MIT)
- [Open Interpreter](https://github.com/openinterpreter/openinterpreter) — Coding agent that lets language models execute code and scripts locally on the user's machine. (Apache-2.0)
- [Plandex](https://github.com/plandex-ai/plandex) — Open-source AI coding agent designed for large projects and multi-step tasks. (MIT)
- [Roo Code](https://github.com/RooCodeInc/Roo-Code) — AI coding agent for VS Code with multiple specialized modes. (Apache-2.0) (archived)
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) — Autonomous software-engineering agent that takes a GitHub issue and submits a fixing patch. (MIT)

## Skills & Prompt Collections

Reusable skill packs, prompt libraries, and instruction-file collections for coding agents. *Last verified: 2026-08-06.*

- [Awesome Claude Code Subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) — Collection of 100+ specialized Claude Code subagent definitions. (MIT)
- [Awesome Copilot](https://github.com/github/awesome-copilot) — Community-contributed instructions, agents, skills, hooks, and plugins for the GitHub Copilot ecosystem. (MIT)
- [Awesome Prompt Engineering](https://github.com/promptslab/Awesome-Prompt-Engineering) — Hand-curated resource library for prompt engineering across major models. (Apache-2.0)
- [Awesome Prompts](https://github.com/ai-boost/awesome-prompts) — Curated list of prompts from top-rated GPTs, covering prompt engineering, attack, and protection. (GPL-3.0)
- [Claude Code Templates](https://github.com/davila7/claude-code-templates) — CLI tool and template collection for configuring and monitoring Claude Code setups. (MIT)
- [Claude Quickstarts](https://github.com/anthropics/claude-quickstarts) — Starter projects demonstrating Claude API integration patterns, including tool use and agent workflows. (MIT)
- [Fabric](https://github.com/danielmiessler/fabric) — Open-source framework of crowdsourced, reusable prompt patterns for augmenting humans with AI. (MIT)
- [mattpocock/skills](https://github.com/mattpocock/skills) — Matt Pocock's engineering skills for coding agents: grilling interviews, spec and ticket flows, TDD, and code review as small composable skill files. (MIT)
- [MengTo/Skills](https://github.com/MengTo/Skills) — Agent skills for designers and builders across Codex, Claude, and Cursor: HTML-to-interaction, full-page capture, UI inspiration. (MIT)
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) — Guides, papers, lessons, and notebooks covering prompt engineering, context engineering, RAG, and agents. (MIT)
- [Prompt Master](https://github.com/nidhinjs/prompt-master) — Claude skill that writes accurate, context-complete prompts for other AI tools. (MIT)
- [Skill-Anything](https://github.com/SYuan03/Skill-Anything) — Converts any source (PDF, video, web, audio, text) into interactive learning packages with quizzes and spaced repetition. (MIT)
- [Superpowers](https://github.com/obra/superpowers) — Agentic skills framework and software-development methodology built as a composable skill library. (MIT)
- [SZoloth/skill-pack](https://github.com/SZoloth/skill-pack) — Curated bundle of reusable Claude Code instruction packs. (MIT)
- [wshobson/agents](https://github.com/wshobson/agents) — Multi-harness agentic plugin marketplace of subagent and skill definitions. (MIT)

## MCP Servers & Registries

Model Context Protocol servers, clients, SDKs, and registries that connect agents to tools and data. *Last verified: 2026-08-06.*

- [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients) — Curated list of Model Context Protocol clients. (MIT)
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — Large curated directory of MCP servers by category. (MIT)
- [AWS MCP Servers](https://github.com/awslabs/mcp) — Suite of MCP servers exposing AWS services and documentation to agents. (Apache-2.0)
- [Cloudflare MCP Server](https://github.com/cloudflare/mcp-server-cloudflare) — MCP servers for managing Cloudflare resources from an agent. (Apache-2.0)
- [Context7](https://github.com/upstash/context7) — MCP server serving up-to-date, version-specific library documentation to coding agents. (MIT)
- [FastMCP](https://github.com/PrefectHQ/fastmcp) — Pythonic framework for building MCP servers and clients quickly. (Apache-2.0)
- [GitHub MCP Server](https://github.com/github/github-mcp-server) — GitHub's official MCP server for repos, issues, and pull requests. (MIT)
- [MCP Go](https://github.com/mark3labs/mcp-go) — Go implementation of the Model Context Protocol. (MIT)
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) — Official Python SDK for building MCP servers and clients. (MIT)
- [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) — Official reference implementations of MCP servers (filesystem, fetch, git, memory, and more). (Apache-2.0)
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) — Official TypeScript SDK for building MCP servers and clients. (MIT)
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) — Browser automation for agents via Playwright over MCP. (Apache-2.0)

## Hooks, Guardrails & Security

Hooks, permission guards, secret scanners, and sandboxing for safe agent operation. *Last verified: 2026-08-06.*

- [E2B](https://github.com/e2b-dev/E2B) — Open-source sandboxed cloud environments for running untrusted AI-generated code. (Apache-2.0)
- [Gitleaks](https://github.com/gitleaks/gitleaks) — Scans repos, commits, and diffs for hardcoded secrets. (MIT)
- [Guardrails](https://github.com/guardrails-ai/guardrails) — Framework adding input/output validation guards to LLM applications. (Apache-2.0)
- [LLM Guard](https://github.com/protectai/llm-guard) — Toolkit sanitizing LLM inputs and outputs: prompt-injection detection, secret redaction, content filters. (MIT)
- [NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails) — Programmable rails constraining LLM conversation flow and tool use. (Apache-2.0)
- [pre-commit](https://github.com/pre-commit/pre-commit) — Framework for managing git pre-commit hooks — the enforcement point most agent guardrails hang from. (MIT)
- [Secretlint](https://github.com/secretlint/secretlint) — Pluggable linter preventing credentials from being committed. (MIT)
- [Semgrep](https://github.com/semgrep/semgrep) — Fast static analysis with writable rules, commonly gating agent-written code. (LGPL-2.1)
- [TruffleHog](https://github.com/trufflesecurity/trufflehog) — Finds and verifies leaked credentials across git history, filesystems, and cloud stores. (AGPL-3.0)

## Spec-Driven & Workflow Frameworks

Spec, requirements, and ticket-driven development frameworks for agent workflows. *Last verified: 2026-08-06.*

- [Agent OS](https://github.com/buildermethods/agent-os) — Spec-driven operating system of instructions and standards for coding agents. (MIT)
- [AI Dev Tasks](https://github.com/snarktank/ai-dev-tasks) — PRD-to-task-list workflow files for feature development with coding agents. (Apache-2.0)
- [BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD) — Agile-flavored multi-agent method: planning, story files, and role agents for larger builds. (MIT)
- [Claude Code Spec Workflow](https://github.com/Pimzino/claude-code-spec-workflow) — Requirements → design → tasks workflow automation for Claude Code. (MIT)
- [OpenSpec](https://github.com/Fission-AI/OpenSpec) — Spec-driven development workflow keeping specs as the source of truth agents implement against. (MIT)
- [PRPs Agentic Engineering](https://github.com/Wirasm/PRPs-agentic-eng) — Product Requirement Prompt methodology and command library for agentic engineering. (MIT)
- [Spec Kit](https://github.com/github/spec-kit) — GitHub's toolkit for spec-driven development: formalize the spec, then let the agent execute against it. (MIT)
- [Task Master](https://github.com/eyaltoledano/claude-task-master) — Parses PRDs into dependency-ordered task lists agents work through. (MIT)

## Memory & Knowledge

Agent memory systems, knowledge bases, and context-management tools. *Last verified: 2026-08-06.*

- [Basic Memory](https://github.com/basicmachines-co/basic-memory) — Local-first knowledge base agents read and write through MCP, stored as plain Markdown. (AGPL-3.0)
- [Chroma](https://github.com/chroma-core/chroma) — Embedding database commonly used as agent retrieval memory. (Apache-2.0)
- [Cognee](https://github.com/topoteretes/cognee) — Memory layer building knowledge graphs from documents and conversations for agent recall. (Apache-2.0)
- [Graphiti](https://github.com/getzep/graphiti) — Temporally-aware knowledge graphs designed for agent memory. (Apache-2.0)
- [Khoj](https://github.com/khoj-ai/khoj) — Self-hostable personal AI that searches and reasons over your own notes and documents. (AGPL-3.0)
- [Letta](https://github.com/letta-ai/letta) — Stateful agents with self-editing long-term memory (the MemGPT lineage). (Apache-2.0)
- [Logseq](https://github.com/logseq/logseq) — Local-first outliner knowledge base on plain files. (AGPL-3.0)
- [Mem0](https://github.com/mem0ai/mem0) — Memory layer API giving agents persistent, user-scoped memories. (Apache-2.0)
- [SilverBullet](https://github.com/silverbulletmd/silverbullet) — Hackable Markdown-based personal knowledge platform. (MIT)
- [Supermemory](https://github.com/supermemoryai/supermemory) — Memory engine and API for adding long-term memory to agents and apps. (MIT)
- [Zep](https://github.com/getzep/zep) — Memory server summarizing, embedding, and retrieving conversation history for agents. (Apache-2.0)

## Orchestration & Multi-Agent

Multi-agent frameworks, routers, and schedulers for coordinating agents. *Last verified: 2026-08-06.*

- [AutoGen](https://github.com/microsoft/autogen) — Microsoft's framework for multi-agent conversation and orchestration. (MIT)
- [CAMEL](https://github.com/camel-ai/camel) — Framework for building and studying communicating multi-agent systems. (Apache-2.0)
- [Claude Flow](https://github.com/ruvnet/claude-flow) — Orchestration layer coordinating swarms of Claude Code agents. (MIT)
- [CrewAI](https://github.com/crewAIInc/crewAI) — Role-based multi-agent framework: crews of agents with tasks and tools. (MIT)
- [Google ADK](https://github.com/google/adk-python) — Google's Agent Development Kit for building and orchestrating agents in Python. (Apache-2.0)
- [LangGraph](https://github.com/langchain-ai/langgraph) — Graph-based orchestration for stateful, controllable agent workflows. (MIT)
- [Mastra](https://github.com/mastra-ai/mastra) — TypeScript agent framework with workflows, RAG, and evals built in. (Apache-2.0)
- [MetaGPT](https://github.com/FoundationAgents/MetaGPT) — Multi-agent framework simulating a software company: role agents produce specs, designs, and code. (MIT)
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — Lightweight multi-agent workflows with handoffs, guardrails, and tracing. (MIT)
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) — Type-safe agent framework built on Pydantic validation. (MIT)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) — Microsoft's model-agnostic SDK for agents and plugin orchestration. (MIT)
- [smolagents](https://github.com/huggingface/smolagents) — Hugging Face's minimal library for code-acting agents. (Apache-2.0)
- [VoltAgent](https://github.com/VoltAgent/voltagent) — TypeScript framework for building and observing multi-agent systems. (MIT)

## Evals & Testing

Eval harnesses, LLM-judge tooling, and agent benchmarks. *Last verified: 2026-08-06.*

- [AgentBench](https://github.com/THUDM/AgentBench) — Benchmark evaluating LLMs as agents across diverse environments. (Apache-2.0)
- [autoevals](https://github.com/braintrustdata/autoevals) — Library of ready-made evaluators, including LLM-as-judge scorers. (MIT)
- [DeepEval](https://github.com/confident-ai/deepeval) — Unit-testing framework for LLM outputs with pytest-style assertions. (Apache-2.0)
- [Evals](https://github.com/openai/evals) — OpenAI's framework and registry of benchmarks for evaluating LLMs. (MIT)
- [HELM](https://github.com/stanford-crfm/helm) — Stanford's holistic evaluation framework for language models. (Apache-2.0)
- [Inspect](https://github.com/UKGovernmentBEIS/inspect_ai) — UK AISI's framework for large language model evaluations. (MIT)
- [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) — EleutherAI's standard few-shot evaluation harness. (MIT)
- [Promptfoo](https://github.com/promptfoo/promptfoo) — Test prompts, agents, and RAG pipelines with assertions and red-teaming. (MIT)
- [Ragas](https://github.com/vibrantlabsai/ragas) — Evaluation toolkit for RAG and LLM application pipelines. (Apache-2.0)
- [SWE-bench](https://github.com/SWE-bench/SWE-bench) — Benchmark testing whether systems can resolve real GitHub issues. (MIT)

## Observability

Tracing, logging, and cost/token monitoring for agent systems. *Last verified: 2026-08-06.*

- [AgentOps](https://github.com/AgentOps-AI/agentops) — Session replays, metrics, and monitoring for AI agents. (MIT)
- [Evidently](https://github.com/evidentlyai/evidently) — Evaluation and monitoring for ML and LLM systems, drift included. (Apache-2.0)
- [Helicone](https://github.com/Helicone/helicone) — Proxy-based LLM observability: request logs, costs, and caching. (Apache-2.0)
- [Laminar](https://github.com/lmnr-ai/lmnr) — Open-source platform for tracing and evaluating AI applications. (Apache-2.0)
- [Langfuse](https://github.com/langfuse/langfuse) — Open-source LLM engineering platform: traces, evals, prompt management, and metrics. (MIT)
- [OpenLIT](https://github.com/openlit/openlit) — OpenTelemetry-native observability for LLMs, agents, and GPUs. (Apache-2.0)
- [OpenLLMetry](https://github.com/traceloop/openllmetry) — OpenTelemetry instrumentation for LLM and agent frameworks. (Apache-2.0)
- [Opik](https://github.com/comet-ml/opik) — Comet's open-source platform for tracing, evaluating, and monitoring LLM apps. (Apache-2.0)

## Output Styles & Registers

Conversational-mode tooling: output styles, technical-level presets, personas, and terse modes that change how an agent talks without changing what it can do. A young category — many styles circulate as gists and unlicensed snippets; entries here meet the license bar. *Last verified: 2026-08-06.*

- [Awesome Claude Code Output Styles](https://github.com/hesreallyhim/awesome-claude-code-output-styles-that-i-really-like) — Curated collection of Claude Code output styles, from practical registers to full personas. (MIT)
- [Caveman](https://github.com/JuliusBrussee/caveman) — why use many token when few token do trick: terse-register skill for 30+ agents with measured ~65% output reduction. (MIT)
- [Caveman Output Style](https://github.com/carlosduplar/caveman-output-style-claude-code) — Always-on caveman formatting as a Claude Code output style, ~40% fewer output tokens. (MIT)

## Meta: Lists & Directories

Other awesome-lists and directories that index AI-development tooling. Several well-known lists are absent here because they carry NonCommercial licenses. *Last verified: 2026-08-06.*

- [Awesome](https://github.com/sindresorhus/awesome) — The original awesome-list of awesome lists, and the conventions this file follows. (CC0-1.0)
- [Awesome AI Devtools](https://github.com/jamesmurdza/awesome-ai-devtools) — Curated list of AI-powered developer tools. (MIT)
- [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps) — Large collection of LLM app examples with agents and RAG. (Apache-2.0)
- [Awesome LLMOps](https://github.com/tensorchord/Awesome-LLMOps) — Curated list of tools for operating LLMs in production. (CC0-1.0)
