# AI Agent Rules

Three rule sets that define how an AI agent should write, behave, and present itself — purpose-built for consistent, trustworthy AI behavior in production.

## What's Inside

### 1. Writing Rules — `no_ai_slop_prompt.md`

24 non-negotiable rules for prose that doesn't sound like AI. Banned words, banned phrases, structural rules, and a self-check checklist. Distilled from Louis Rossmann's [no_ai_slop_writing_rules](https://github.com/realrossmanngroup/no_ai_slop_writing_rules). Untouched original with full attribution.

### 2. Behavioral Rules — `agent-behavioral-rules.md`

Rules that govern HOW the agent operates — not how it writes, but how it thinks and acts:
- **Thorough Research Rule**: Cross-reference 5-10 sources before settling on any solution. Single-source answers are unacceptable.
- **Stop and Check Rule**: Halt before multi-step actions. Ask before acting. Never guess when the answer is reachable. No cascading fix attempts.

### 3. Identity & Voice — `agent-identity.md`

Rules that define WHO the agent is:
- Name, gender, personality
- Confidentiality framework (hard rules for privacy)
- Work ethic standards
- Voice and tone guidelines

### 4. Combined — `ALL-RULES.md`

All three rule sets in one file. Paste this into any AI agent or chatbot as a system prompt to enforce writing quality, behavioral discipline, and consistent identity simultaneously.

## Usage

**System prompt**: Paste `ALL-RULES.md` into your AI tool's system prompt or custom instructions.

**Per-session**: Paste the relevant file at the start of a conversation.

**Granular**: Use individual files when you only need one rule set — `agent-behavioral-rules.md` for task execution, `no_ai_slop_prompt.md` for writing quality, `agent-identity.md` for persona.

## Credit

Writing rules: Louis Rossmann's [no_ai_slop_writing_rules](https://github.com/realrossmanngroup/no_ai_slop_writing_rules).

Behavioral and identity rules: Original.
