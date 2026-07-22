---
id: component-name
title: Foundation name
description: |-
  Brief summary of what the component does and where it is used.
  slug: /components/component-name
slug: /foundations/foundation-name
tags:
  - component
  - category
  - accessibility
status: draft
version: 0.1.0
last_updated: YYYY-MM-DD
owner: design-systems
related:
  - /foundations/color
  -  /patterns/example-pattern
ai_keywords:
---
# Component name

## Purpose
<!-- Explain what this component is for in 1–3 sentences. -->
Example: "Button is used to trigger a user action such as saving, submitting, or continuing a task."

## Use when
<!-- Add situations where this component is the right choice. -->
- Example: "Use when the user needs to confirm or start an action."
- Example: "Use in forms, dialogs, and page-level actions."

## Do not use
<!-- Clarify common misuse cases. -->
- Example: "Do not use as a text link for navigation."
- Example: "Do not use for multiple equally prominent actions in the same area."

## Variants
<!-- List the supported versions of the component. -->
- Primary — Example: main CTA in a page or modal.
- Secondary — Example: alternative action next to primary.
- Tertiary — Example: low-emphasis optional action.
- Destructive — Example: delete, remove, reset.

## Anatomy
<!-- Name the parts that make up the component. -->
- Container
- Label
- Icon (optional)
- Supporting text (optional)

## States
<!-- List all interactive and visual states. -->
- Default
- Hover
- Focus-visible
- Pressed
- Disabled
- Loading
- Error (if relevant)

## Behavior
<!-- Describe interaction rules in short, explicit statements. -->
- Example: "Click triggers the assigned action immediately."
- Example: "Disabled state prevents pointer and keyboard activation."
- Example: "Loading state keeps layout stable and communicates progress."

## Accessibility
<!-- Include keyboard, semantics, name, and focus requirements. -->
- Example: "Use a native `button` element whenever possible."
- Example: "Icon-only buttons require an accessible name."
- Example: "Visible focus indication is required."
- Example: "Minimum target size is 44x44px."

## Content guidelines
<!-- Explain how labels or text inside the component should be written. -->
- Example: "Use concise verb-led labels such as Save, Continue, or Delete."
- Example: "Avoid vague labels like Click here or Submit form now."

## Design tokens
<!-- Reference semantic tokens instead of raw values. -->
- Background: `color.action.primary`
- Text: `color.text.inverse`
- Border radius: `radius.md`
- Height: `size.control.md`
- Spacing: `space.200` / `space.300`

## Examples
<!-- Add short usage examples, ideally realistic ones. -->
### Good
Example: "Use a primary button labeled Continue at the end of a checkout step."

### Avoid
Example: "Using three primary buttons in the same card."

## Related
<!-- Link to nearby docs. -->
- /foundations/color
- /patterns/form-submission