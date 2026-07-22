---
id: colors-tegel-ds
title: Color - Tegel Design System
description: --
tags:
  - foundation
  - color
  - semantic-color
  - brand-color
  - typography
status: in progress
version: 0.1.0
last_updated: 2026-07-22
owner: Flavio Santana
applies_to:
  - web
related:
ai_keywords:
  - foundation
  - color
  - accessible-color
  - semantic-color
  - typography
---


# Foundation name

## Purpose
<!-- Explain what system layer this page defines. -->

This page will guide and define several sections which defines the foundation for design on Tegel. 
- Color defines the semantic token system used to communicate hierarchy, action, and feedback across products. Reference on: https://tegel.scania.com/foundations/foundation-colors 
- Typography is language an the visualisation of our voice. This is not just what we say, but how we say it. Scania’s tone of voice is honest, sincere, respectful and confident. Reference on: https://tegel.scania.com/foundations/foundation-typography 
- Accessibility means ensuring that a website or application is universally accessible to all intended users, regardless of their disabilities or the software and hardware they use. Reference on: https://tegel.scania.com/foundations/accessibility







## Principles
<!-- Add the core rules that should stay true across products. -->
- Example: "Use semantic tokens instead of hard-coded values."
- Example: "Use foundations to create consistency across components and patterns."
- Example: "Keep naming stable across platforms."

## Scope
<!-- Clarify where this foundation applies and where it does not. -->
- Example: "Applies to product UI, marketing surfaces, and internal tools."
- Example: "Does not define campaign-specific illustration styles."

## Token model
<!-- Document the token structure or naming model. -->
| Token | Role | Example use |
|---|---|---|
| `color.bg.default` | Default page background | App shell |
| `color.text.primary` | Primary readable text | Body copy |
| `space.200` | Standard small spacing step | Gap between label and field |

## Rules
<!-- Add direct usage rules that remove ambiguity. -->
- Example: "Reference semantic tokens in component specs and code."
- Example: "Do not expose raw hex values in product guidance."
- Example: "Use alias tokens when platform mapping differs."

## Accessibility
<!-- Define the accessibility constraints tied to this foundation. -->
- Example: "Body text combinations must meet 4.5:1 contrast."
- Example: "Do not rely on color alone to communicate state."
- Example: "Typography sizes must preserve readability at zoom."

## Do
<!-- List preferred behaviors or implementation patterns. -->
- Example: "Document light and dark theme behavior."
- Example: "Show token examples in context, not only in tables."

## Do not
<!-- List anti-patterns. -->
- Example: "Do not create one-off tokens for a single component need."
- Example: "Do not rename a stable token without deprecation guidance."

## Examples
<!-- Add practical product examples. -->
### Good
Example: "Use `color.feedback.error` for field validation and pair it with inline text and iconography."

### Avoid
Example: "Using a raw red hex value directly in an input spec."

## Related
<!-- Link to adjacent foundations, components, or patterns. -->
- /components/input
- /patterns/inline-validation