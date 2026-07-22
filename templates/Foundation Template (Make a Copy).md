---
id: foundation-name
title: Foundation name
description: Brief summary of the design rule, token group, or principle covered by this page.
slug: /foundations/foundation-name
tags:
  - foundation
  - tokens
  - platform
status: draft
version: 0.1.0
last_updated: YYYY-MM-DD
owner: design-systems
applies_to:
  - web
  - ios
  - android
related:
  - /components/example-component
  - /patterns/example-pattern
ai_keywords:
  - keyword one
  - keyword two
---

# Foundation name

## Purpose
<!-- Explain what system layer this page defines. -->
Example: "Color defines the semantic token system used to communicate hierarchy, action, and feedback across products."

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