---
description: Compare UI implementation against a target mockup
agent: review
---

Compare the provided target mockup/design with the current UI implementation.

Inputs may include:
- target screenshot, PDF, or Figma export
- current implementation screenshot
- route/URL to inspect
- relevant component files

Process:
1. Identify the target layout, spacing, typography, colors, proportions, and states.
2. Identify what evidence is available for the current implementation.
3. If no current screenshot or running URL is available, ask for it instead of guessing.
4. Compare target vs current implementation.
5. Classify visual differences as:
   - must fix
   - should fix
   - optional polish
6. Recommend concrete code-level corrections.

Rules:
- Do not edit files. This command is diagnostic only.
- Be explicit about uncertainty when evidence is incomplete.
