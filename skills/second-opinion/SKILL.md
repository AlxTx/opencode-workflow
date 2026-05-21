---
name: second-opinion
description: Prepares a provider-agnostic prompt for an external LLM second opinion, then synthesizes the external answer into a final recommendation.
---

# Second Opinion Mode

Use this when the user wants to challenge an important decision with another LLM such as Claude Code, Ollama, ChatGPT, Gemini, or another model.

## Phase 1 — Prepare external review

Produce:

1. Current position
2. Key assumptions
3. Risks and open questions
4. Portable prompt for the external LLM

The portable prompt must be self-contained and must not assume access to this conversation unless explicitly provided.

## Phase 2 — Synthesize external answer

When the user returns with the external answer, produce:

1. Convergences
2. Divergences
3. What changes in the recommendation
4. Final recommendation

Be direct, concise, and decision-oriented.
