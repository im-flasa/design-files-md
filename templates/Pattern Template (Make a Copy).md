---
id: pattern-name
title: Pattern name
description: Brief summary of the reusable user flow or interaction pattern.
slug: /patterns/pattern-name
tags:
  - pattern
  - flow
  - category
status: draft
version: 0.1.0
last_updated: YYYY-MM-DD
owner: design-systems
components_used:
  - /components/example-component
  - /components/example-component-2
related:
  - /foundations/example-foundation
  - /patterns/related-pattern
ai_keywords:
---

# Pattern name

## Purpose
<!-- Explain the user problem this pattern solves. -->
Example: "Inline validation helps users identify and correct form issues without losing context."

## Use when
<!-- Describe the situations where this pattern is appropriate. -->
- Example: "Use when users need immediate or near-immediate feedback in forms."
- Example: "Use when a task repeats across products and should behave consistently."

## Do not use
<!-- Clarify situations where another pattern is better. -->
- Example: "Do not use for page-level failures unrelated to a specific field."
- Example: "Do not use when feedback is purely informational and non-blocking."

## User goal
<!-- Describe the outcome from the user perspective. -->
Example: "Help users complete tasks accurately and recover from errors quickly."

## Components involved
<!-- List the building blocks used by the pattern. -->
- Input
- Select
- Helper text
- Button
- Alert

## Flow
<!-- Document the sequence step by step. -->
1. Example: "User starts the task or interaction."
2. Example: "System responds with guidance, validation, or next-step affordance."
3. Example: "User corrects, confirms, or continues."
4. Example: "System shows success, next state, or recovery path."

## Rules
<!-- Add implementation or behavior rules. -->
- Example: "Keep feedback close to the relevant element."
- Example: "Do not interrupt the user before they have enough context."
- Example: "Preserve task progress when showing recoverable errors."

## Accessibility
<!-- Describe assistive technology, focus, and readability requirements. -->
- Example: "Associate messages programmatically with the relevant control."
- Example: "Do not depend only on color to communicate errors or success."
- Example: "Move focus intentionally only when it improves task recovery."

## Content guidance
<!-- Explain how messages and labels should be written. -->
- Example: "State what happened, why it matters, and how to fix it."
- Example: "Use short, corrective language rather than blame-oriented wording."

## Variations
<!-- Compare supported versions of the pattern. -->
| Case | Pattern behavior |
|---|---|
| Required field empty | Show an inline error after blur or submit |
| Invalid format | Explain the expected format next to the field |
| Async validation | Show loading, then a success or error outcome |

## Examples
<!-- Add realistic examples of the pattern in context. -->
### Good
Example: "After submit, focus moves to the first invalid field and the error text explains how to fix the issue."

### Avoid
Example: "Show a generic toast saying Something went wrong without pointing to the field."

## Related
<!-- Link to the connected docs. -->
- /foundations/color
- /components/input
- /patterns/form-submission