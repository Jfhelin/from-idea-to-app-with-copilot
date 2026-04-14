---
name: workshop-simplicity
description: "Default workshop guardrail. Apply automatically during this workshop to keep outputs simple, browser-based, local, and suitable for non-technical users."
---

# Workshop Simplicity

This skill is active for the workshop experience.

Its purpose is to keep the agent focused on simple, fast, confidence-building outcomes for non-technical participants.

## Goals

- keep the experience simple and low-friction
- reduce technical complexity
- prefer browser-only apps
- avoid setup, backend, and enterprise plumbing
- keep the first result usable and easy to open
- use realistic sample data when needed
- favor clarity over completeness

## Always Prefer

- a small browser-based app
- one main screen
- simple interactions
- local sample data
- realistic-looking business examples
- quick success over technical sophistication
- direct instructions like “open this file” over tool-heavy explanations

## Avoid

- auth or login
- databases
- backend services
- cloud deployment
- API keys
- account setup
- enterprise integrations at runtime
- long explanations of code, files, architecture, or tooling
- asking the participant to choose between many technical options

## Simplification Rule

If the user's request is too large, too technical, or too dependent on external systems:
- automatically simplify it
- preserve the visible business value
- remove implementation complexity

Examples:
- CRM integration → realistic local customer data
- analytics system → sample KPI dashboard
- workflow engine → simple task/status view
- authenticated portal → public local demo page

## UX Rule

The first version should be:
- easy to understand
- easy to open
- easy to react to

It does not need to be complete.

## Instruction Rule

When telling the user what to do:
- keep it short
- use plain English
- tell them the next action
- do not expose internal concepts unless asked

## Success Rule

A successful output is one where the participant feels:
> “I asked for something and got a working result quickly.”