# AGENTS

## Public API Lookup

When needing an implementation that requires an external service or data source, first check the public APIs catalog at https://github.com/public-apis/public-apis before implementing from scratch or selecting a paid provider.

- Browse/search the catalog for an API matching the required domain or functionality.
- Prefer free, no-auth, or CORS-enabled APIs where they fit the requirements.
- Document the chosen API (name, category, auth requirement, link) in the implementation spec or task notes.
- If no suitable public API exists, proceed with the implementation as designed and record the decision.

## Reusable project templates & knowledge sources

Before scaffolding from scratch, check these agent-native templates and curated lists for reusable project shapes, agent instructions, skills, workflows, MCP configs, and libraries:

### Agent-native starters
- [joeylu/agent-starter-kits](https://github.com/joeylu/agent-starter-kits) — copy-ready templates (Next.js/React/TS, Expo, WeChat Mini) with agent rules and local tooling notes
- [Gilberto-de-Piento/ai-agent-project-template](https://github.com/Gilberto-de-Piento/ai-agent-project-template) — canonical `AGENTS.md`, memory bank, handoff, 5 skills, 9 workflows, adapters for Claude/Gemini/Cursor/Cline/Copilot/Codex
- [kyh/init](https://github.com/kyh/init) — AI-native TS boilerplate (web, mobile, extension, desktop); Tailwind/shadcn/ui, Drizzle, Postgres, Vitest, Stripe; `llms.txt`, agent wiki
- [GeekyAnts/create-ai-native-project](https://github.com/GeekyAnts/create-ai-native-project) — CLI scaffolding `AGENTS.md`/`CLAUDE.md`, skills, agents, Docker, CI, MCP servers across stacks
- [SiCar10mw/ai-dev-template](https://github.com/SiCar10mw/ai-dev-template) — constitution-first, spec-first, TDD, governance, adversarial AI review, MCP, ADRs, threat model
- [heldernoid/agentic-build-templates](https://github.com/heldernoid/agentic-build-templates) — 120 agent-buildable specs (AGENTS.md + PLAN.md + ARCHITECTURE.md + mocks)
- [johnku2011/boilerplates-with-ai-skills](https://github.com/johnku2011/boilerplates-with-ai-skills) — `npx bwai-cli` starters with curated skills + `skills.lock` provenance + SkillSpector CI gate
- [valuecodes/agentic-monorepo-starter](https://github.com/valuecodes/agentic-monorepo-starter) — Turborepo monorepo with agent doc sync across `.claude`/`.codex`/`.cursor`

### Library / framework discovery
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) — meta-list of awesome lists across topics
- [jnv/lists](https://github.com/jnv/lists) — definitive list of lists, including language-specific resources
- [awesomelist.link](https://awesomelist.link/) — search across 1,541 awesome lists / 262k entries

### Open-source vetting
- [ossf/scorecard](https://github.com/ossf/scorecard) — automated security-health scoring for OSS dependencies
- [libraries.io](https://libraries.io/) — open-source library metadata across package managers

Guideline: when an external service or library is needed, prefer reusing an existing public API, library, or template above before implementing from scratch. Document the chosen resource (name, category, auth requirement, link) in the implementation spec or task notes.
