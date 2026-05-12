# Daniel Howells

I build interfaces, developer tools, and agent systems for complex data and schema-heavy workflows. I am especially interested in UI, multi-agent systems, visual analysis, retrieval, vector embeddings, and the DX around making those systems easier to use.

I am based in London and work across product engineering, AI-augmented software, design and material intelligence, and TypeScript tooling. I care about typed inputs and outputs, explicit validation, schema-aware automation, good documentation, and interfaces that hold up under real usage.

[Website](https://www.danielhowells.com/) · [npm](https://www.npmjs.com/~howells)

Most of my current work is private, experimental, or not ready for primetime. Projects such as [Routerbase](https://routerbase.dev), [Faceplacer](https://faceplacer.com), [Monogrove](https://monogrove.com), and [Wiretext](https://wiretext.app) cover model discovery, visual analysis, dependency health, and text-native design tooling, but the source is not always public yet. When a project becomes useful outside my own setup, especially tooling, I try to release it.

## Current Work

I am currently building in a few areas:

- Agent-ready developer tools: packages, CLIs, and docs with clear schemas, examples, and operating rules.
- AI evaluation and advisory workflows: systems that turn briefs, evidence, and critique into clearer product decisions.
- Material and architecture intelligence: product graphs, publication retrieval, image understanding, color systems, and design-reference tools for the built environment.
- Personal and operational automation: local CLIs and small tools for making everyday workflows scriptable.
- Product surfaces: web apps, design systems, and focused tools for complicated workflows.

The recurring pattern is simple: explicit contracts, inspectable state, and software that gives agents enough structure to help without guessing.

## Public Projects

### Agent and AI Tooling

| Project | What it does |
| --- | --- |
| [Arc](https://github.com/howells/arc) | A workflow layer for agentic software work: ideation, implementation, testing, review, and release discipline. |
| [Agent Surface](https://github.com/howells/agentsurface) | A guide and toolkit for exposing software to agents through docs, schemas, examples, and affordances. |
| [Envelope](https://github.com/howells/envelope) | A package for wrapping coding-agent CLIs with typed Zod input and output contracts. |
| [@howells/ai](https://github.com/howells/ai) | A TypeScript AI client used in projects such as [Routerbase](https://routerbase.dev), smoothing over provider differences while keeping escape hatches available. |
| [Fiction](https://github.com/howells/fiction) | A Claude Code plugin for long-form fiction work: chapters, characters, outlines, critique, and editing. |
| [Not Just A Skill](https://github.com/howells/not-just-a-skill) | An agent skill that audits and rewrites prose that carries obvious AI-writing tells. |
| [Sift](https://github.com/howells/sift) | An AI-powered email triage CLI for turning messy inbox state into structured, actionable output. |
| [claudeusage](https://github.com/howells/claudeusage) | A CLI for checking Claude Code usage and limits across multiple accounts. |

### Environment, TypeScript, and Package Infrastructure

| Project | What it does |
| --- | --- |
| [Envy](https://github.com/howells/envy) | Zod-powered env parsing, strict schema-defined variables, CLI checks, and deployment-provider preflight checks. |
| [@howells/cli](https://github.com/howells/cli) | The shared harness behind my agent-first CLIs: argument parsing, JSON output, schema exposure, and input hardening. |
| [Srcfull](https://github.com/howells/srcfull) | Image extraction and source-resolution toolkit for finding high-quality web images from messy page markup and CDN URLs. |
| [@howells/lint](https://github.com/howells/lint) | Pinned Biome and Ultracite presets for my TypeScript projects. |
| [@howells/typescript-config](https://github.com/howells/typescript-config) | Pinned TypeScript config presets built around `@total-typescript/tsconfig`. |
| [@howells/husky](https://github.com/howells/husky) | Immutable shared git hooks for keeping pre-commit and pre-push gates consistent across repos. |
| [Scaffold](https://github.com/howells/scaffold) | An opinionated documentation scaffold and baseline for TypeScript apps, packages, and agent-ready repos. |

### Agent-First CLIs

| Project | What it does |
| --- | --- |
| [Motif CLI](https://github.com/howells/motif-cli) | An agent-first fal.ai image generation CLI with structured output, dry runs, history, series, and terminal studio mode. |
| [linearcli](https://github.com/howells/linearcli) | A Linear CLI for issues, projects, teams, and cycles, with structured JSON, schema introspection, and dry runs. |
| [thingscli](https://github.com/howells/thingscli) | A Things 3 CLI that reads from the local database and writes through the URL scheme, designed for agent workflows. |
| [starlingcli](https://github.com/howells/starlingcli) | A Starling Bank CLI for balances, transactions, and payees, with multi-account structured output. |
| [wisecli](https://github.com/howells/wisecli) | A read-only Wise CLI for balances, transfers, and profiles, with multi-token support and schema introspection. |
| [revolutcli](https://github.com/howells/revolutcli) | A read-only Revolut Business CLI for balances, transactions, and accounts using OAuth and JWT auth. |
| [godaddy-cli](https://github.com/howells/godaddy-cli) | A scriptable GoDaddy DNS CLI for humans and automation. |

### UI, Apps, and Focused Tools

| Project | What it does |
| --- | --- |
| [Stacksheet](https://github.com/howells/stacksheet) | A React sheet-stack system with Motion animations, focus handling, safe navigation, and mobile behavior. |
| [Boubakikid](https://github.com/howells/boubakikid) | A round ID generator based on bouba/kiki phonesthesia research. |
| [Regexscope](https://github.com/howells/regexscope) | A visual regex debugger for seeing matches and groups in real time. |
| [Noodles](https://github.com/howells/noodles) | A visual Node.js dev-server manager for macOS. |

I keep older experiments around, but the repositories above are the public projects closest to what I am building now.
