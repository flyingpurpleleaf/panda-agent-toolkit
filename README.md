# panda-agent-toolkit

**English** | [中文](./README.zh-CN.md)

panda-agent-toolkit is a structured, engineering-focused agent toolkit repository shaped by ten years of real-world development experience.

It serves as a single place to maintain:

- Reusable skills for both custom and daily development scenarios
- Prompt templates designed for consistency and repeatability
- MCP setups and integration patterns
- Agent rules that enforce predictable behavior
- Documentation capturing real-world experience and best practices

Rather than a loose collection of snippets, this repo aims to treat agent tooling as part of a serious engineering workflow.

---

## Why This Repository

Agent development is easy to start and hard to keep clean.

Most people end up with:

- Prompt fragments scattered across notes and chat history
- Skills that work once but are never reused
- MCP configs that are copied, outdated, or undocumented
- Agent rules that live only in someone's head
- Hard-won lessons that never get written down

This repository exists to fix that.

It is not a framework. It is not a product. It is a working toolkit — organized, versioned, and meant to be reused.

---

## What's Inside

### 1. Skills

Reusable capabilities for agents and daily development.

```
skills/
├── custom/          # Skills I wrote myself
├── daily/           # Skills I use in day-to-day development
└── shared/          # Common utilities and helpers
```

Each skill is documented with:

- Purpose
- Inputs / outputs
- Usage examples
- Known limitations

---

### 2. Prompt Templates

Templates designed for consistency and repeatability.

```
prompts/
├── coding/          # Code generation, review, refactoring
├── writing/         # Documentation, summaries, reports
├── analysis/        # Research, comparison, decision-making
└── workflow/        # Multi-step and agentic workflows
```

Principles:

- Prefer explicit structure over clever wording
- Keep templates parameterized and reusable
- Version templates when behavior changes

---

### 3. MCP Integrations

Model Context Protocol setups and integration patterns.

```
mcp/
├── configs/         # Server and client configurations
├── patterns/        # Common integration patterns
└── notes/           # Caveats, limits, debugging tips
```

Focus areas:

- Reliable local development setups
- Clear separation between config and secrets
- Documented failure modes

---

### 4. Agent Rules

Rules that enforce predictable agent behavior.

```
rules/
├── global/          # Always-on behavioral guidelines
├── project/         # Project-specific constraints
└── safety/          # Guardrails and boundaries
```

Goals:

- Make agent behavior explicit, not implicit
- Reduce surprise and drift across sessions
- Keep rules small, testable, and reviewable

---

### 5. Documentation

Practical notes and lessons learned from real usage.

```
docs/
├── guides/          # Step-by-step guides
├── lessons/         # Post-mortems and hard-won lessons
├── comparisons/     # Tool and approach comparisons
└── reference/       # Cheat sheets and quick references
```

This section is intentionally opinionated. It records what actually worked, what failed, and why.

---

## Design Principles

1. **Structure over accumulation** — A small, organized set beats a large, messy one.
2. **Reuse over repetition** — If something is used twice, it belongs here.
3. **Explicit over implicit** — Rules, prompts, and configs should be readable.
4. **Documentation is part of the tool** — An undocumented skill is an unfinished skill.
5. **Engineering discipline applies to agents too** — Treat agent tooling like production code.

---

## Repository Structure

```
panda-agent-toolkit/
├── skills/
├── prompts/
├── mcp/
├── rules/
├── docs/
├── templates/
├── scripts/
├── README.md
├── README.zh-CN.md
└── LICENSE
```

---

## How to Use

1. Browse the section you need (`skills`, `prompts`, `mcp`, `rules`, `docs`).
2. Read the local `README.md` inside each folder for details.
3. Copy, adapt, and integrate into your own workflow.
4. If you improve something, consider contributing it back.

---

## Status

This is an actively maintained personal toolkit. Content is added as new skills, patterns, and lessons emerge from real development work.

Not everything here is polished. Everything here is used.

---

## Contributing

This repository is primarily a personal knowledge base, but suggestions and corrections are welcome.

If you want to contribute:

- Open an issue describing the problem or idea
- Keep changes focused and documented
- Follow the existing structure and naming conventions

---

## License

MIT License (or specify your preferred license).

---

## A Note from the Maintainer

Ten years of shipping software teaches you one thing: tools don't matter unless they're organized.

This repository is my attempt to apply that lesson to agent development — to keep skills, prompts, MCP setups, rules, and experience in one place, structured well enough to actually be reused.

If it helps you build something more reliable, it has done its job.
