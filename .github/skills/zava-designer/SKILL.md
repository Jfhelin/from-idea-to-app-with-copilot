---
name: zava-designer
description: "Default design skill for this workshop. Apply automatically whenever building, styling, or improving app UI. Ground all visual decisions in the Jfhelin/zava-design-guidelines repository via GitHub MCP."
---

# Zava Designer

Zava is the default design language for apps built in this workshop.

Apply it automatically whenever UI is created or improved. The participant does not need to ask for Zava explicitly.

## Goals

- apply a calm, modern, enterprise-ready visual style
- improve hierarchy, readability, spacing, and responsiveness
- ground visual decisions in approved design guidance
- preserve functional clarity and accessibility

## Grounding Workflow

Use GitHub MCP to retrieve design guidance from `Jfhelin/zava-design-guidelines`.

Prefer:
- `brand/tokens.json`
- `brand/page-structure.md`
- `brand/zava-ui-patterns.md`
- `brand/zava-style.md`
- `brand/logo-usage.md`
- relevant published GitHub issues

Do not invent a brand style before checking the repo guidance.

## Design Defaults

Prefer:
- dark teal header/footer regions
- light gray-blue body background
- white content surfaces
- clean system typography
- lightly bordered cards and panels
- minimal, purposeful motion
- clear controls and readable tables
- direct, concise copy tone

Avoid:
- heavy shadows
- bright competing accents
- dark dashboard anti-patterns
- gradients
- decorative clutter
- custom logo variations

## Logo Rule

When branding is appropriate:
- check `brand/logo-usage.md`
- follow issue guidance for placement
- do not recolor or distort the logo
- reference the approved raw GitHub URL directly in the app if needed
- if the logo is unavailable at runtime, use a simple text wordmark fallback

## Scope Rule

Do not change the app's product scope or core workflow.

Only improve presentation, clarity, structure, and consistency.

## Output Rule

When UI changes are made, keep the summary brief:
- what visual improvements were made
- that the app still works the same way