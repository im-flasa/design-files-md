---
id: colors-tegel-ds
title: Color - Tegel Design System
description: Without using words, colors tell the story of a brand. Colors convey an immediate and lasting impression, which is why the brand color palette is of crucial importance.
tags:
  - foundation
  - color
  - semantic-color
  - brand-color
status: in progress
version: 0.1.0
last_updated: 2026-07-29
owner: Flavio Santana
applies_to:
  - web
related:
ai_keywords:
  - foundation
  - color
  - accessible-color
  - semantic-color
---

# Foundation name

## Purpose
Color at Scania and Tegel Design System: Without using words, colors tell the story of a brand. Colors convey an immediate and lasting impression, which is why the brand color palette is of crucial importance.

## Principles
- Brand palette: The brand palette contains the Scania primary brand colors.
	- Black and White
- Background colors: Our grey scale is used to define background colors, as well as some graphic elements such as dividers.
	- Grey 50, 100, 150, 200, 250, 300, 350, 400, 500, 600, 650, 700, 750, 800, 850, 900, 950
- Extended palettes: Used for different states.
	- Blue scale: The blue scale is mainly used for interactive components such as header, CTA, links and buttons for their various states. You can find which value should be used on the corresponding component page
		- Blue 50, 100, 200, 300, 400, 500, 600, 700, 800, 900
	- Red scale: The extended red scale is used to visually translate the different states of CTA such as danger buttons, and its lighter values could also be used as background color for banners notifications.
		- Red 50, 100, 200, 300, 400, 500, 600, 700, 800, 900
	- Yellow scale: The extended yellow scale is used to visually translate different warning states, and its lighter values could also be used as background color for banners, notifications and more.
		- Yellow 50, 100, 200, 300, 400, 500, 600, 700, 800, 900
	- Green scale: The extended green scale is used to visually translate different success states, and its lighter values could also be used as background color for banners, notifications and more.
		- Green 50, 100, 200, 300, 400, 500, 600, 700, 800, 900

## Scope
These colors are applied only for Tegel Design System and Scania context.

## Token model
<!-- Document the token structure or naming model. -->
| Token | Role | Example use |
|---|---|---|
<!--Scania Base -->
| `color.base.black` | Black color for text application in light mode | `#000000` |
| `color.base.white` | White color for text application in light mode | `FFFFFF` |
<!--Scania Transparent -->
| `color.transparent.950` | Transparent color for light mode | `#0E1013` |
| `color.transparent.750` | Transparent color for light mode | `#0D1727DB`|
| `color.transparent.650` | Transparent color for light mode | `#041530B8` |
| `color.transparent.500` | Transparent color for light mode | `#0A2850A3` |
| `color.transparent.350` | Transparent color for light mode | `#07275880` |
| `color.transparent.250` | Transparent color for light mode | `#3A517C59` |
| `color.transparent.200` | Transparent color for light mode | `#303C612B` |
<!--Scania Transparent Inverse -->
| `color.transparent.inverse.50` | Transparent color for dark mode | `#F6F7F9FF` |
| `color.transparent.inverse.200` | Transparent color for dark mode | `#E9F0FCE0`|
| `color.transparent.inverse.250` | Transparent color for dark mode | `#DBE6F8CC`|
| `color.transparent.inverse.300` | Transparent color for dark mode | `#C3D8F7B8`|
| `color.transparent.inverse.400` | Transparent color for dark mode | `#AAC9F699`|
| `color.transparent.inverse.500` | Transparent color for dark mode | `#AED0FF7D`|
| `color.transparent.inverse.600` | Transparent color for dark mode | `#A4C7F566`|
<!--Scania Transparent Invisible -->
| `color.transparent.invisible.light` | Transparent invisible for light mode | `#FFFFFF00`|
| `color.transparent.invisible.dark` | Transparent invisible for dark mode  | `#00000000`|
<!--Scania Transparent Scrim -->
| `color.transparent.scrim.light` | Transparent overlay for light mode | `#00000066`|
| `color.transparent.scrim.dark` | Transparent overlay for dark mode  | `#00000099`|
<!--Scania Transparent Shadow -->
| `color.transparent.shadow.350` | Transparent shadow | `#00000059`|
| `color.transparent.shadow.250` | Transparent shadow | `#00000040`|
| `color.transparent.shadow.200` | Transparent shadow | `#00000059`|
| `color.transparent.shadow.150` | Transparent shadow | `#00000026`|
| `color.transparent.shadow.100` | Transparent shadow | `#0000001A`|
| `color.transparent.shadow.10` | Transparent shadow | `#00000003`|
| `color.transparent.shadow.00` | Transparent shadow | `#00000000`|
<!--Scania Blue -->
| `color.blue.50` | Color blue | `#E4E9F1FF`|
| `color.blue.100` | Color blue | `#BACDE8FF`|
| `color.blue.200` | Color blue | `#87AFE8FF`|
| `color.blue.300` | Color blue | `#4A89F3FF`|
| `color.blue.400` | Color blue | `#2A6ECFFF`|
| `color.blue.500` | Color blue | `#2058A8FF`|
| `color.blue.600` | Color blue | `#16417FFF`|
| `color.blue.700` | Color blue | `#0F3263FF`|
| `color.blue.800` | Color blue | `#041E42FF`|
| `color.blue.900` | Color blue | `#001533FF`|
<!--Scania Green -->
| `color.green.50` | Color green | `#D3EEE7FF`|
| `color.green.100` | Color green | `#9BD9C2FF`|
| `color.green.200` | Color green | `#65BDA5FF`|
| `color.green.300` | Color green | `#009E7EFF`|
| `color.green.400` | Color green | `#008064FF`|
| `color.green.500` | Color green | `#00664FFF`|
| `color.green.600` | Color green | `#004D3BFF`|
| `color.green.700` | Color green | `#0A382EFF`|
| `color.green.800` | Color green | `#00251BFF`|
| `color.green.900` | Color green | `#001A12FF`|
<!--Scania Grey -->
| `color.grey.00` | Color grey | `#FFFFFFFF`|
| `color.grey.50` | Color grey | `#F6F7F9FF`|
| `color.grey.100` | Color grey | `#EDEFF3FF`|
| `color.grey.150` | Color grey | `#E0E5EBFF`|
| `color.grey.200` | Color grey | `#D1D7E0FF`|
| `color.grey.250` | Color grey | `#B4BECDFF`|
| `color.grey.300` | Color grey | `#93A2B7FF`|
| `color.grey.350` | Color grey | `#7E90A9FF`|
| `color.grey.400` | Color grey | `#6E829FFF`|
| `color.grey.500` | Color grey | `#5F728CFF`|
| `color.grey.600` | Color grey | `#4E5E75FF`|
| `color.grey.650` | Color grey | `#475467FF`|
| `color.grey.700` | Color grey | `#3A4554FF`|
| `color.grey.750` | Color grey | `#2D3643FF`|
| `color.grey.800` | Color grey | `#242C37FF`|
| `color.grey.850` | Color grey | `#1C222BFF`|
| `color.grey.900` | Color grey | `#15181DFF`|
| `color.grey.950` | Color grey | `#0B0C0FFF`|
<!--Scania Red -->
| `color.red.50` | Color red | `#FFDFE3FF`|
| `color.red.100` | Color red | `#FFB9B8FF`|
| `color.red.200` | Color red | `#FC8A88FF`|
| `color.red.300` | Color red | `#EA4851FF`|
| `color.red.400` | Color red | `#D1001BFF`|
| `color.red.500` | Color red | `#B20018FF`|
| `color.red.600` | Color red | `#8A0012FF`|
| `color.red.700` | Color red | `#6C0011FF`|
| `color.red.800` | Color red | `#480008FF`|
| `color.red.900` | Color red | `#350004FF`|
<!--Scania Yellow -->
| `color.yellow.50` | Color yellow | `#F9EEC3FF`|
| `color.yellow.100` | Color yellow | `#F8E596FF`|
| `color.yellow.200` | Color yellow | `#F4D65DFF`|
| `color.yellow.300` | Color yellow | `#F1C21BFF`|
| `color.yellow.400` | Color yellow | `#EAAD06FF`|
| `color.yellow.500` | Color yellow | `#B87C14FF`|
| `color.yellow.600` | Color yellow | `#975717FF`|
| `color.yellow.700` | Color yellow | `#6B3B10FF`|
| `color.yellow.800` | Color yellow | `#4D260AFF`|
| `color.yellow.900` | Color yellow | `#361B07FF`|

## Rules
<!-- Add direct usage rules that remove ambiguity. -->
Reference semantic tokens in component specs and code.

## Accessibility
<!-- Define the accessibility constraints tied to this foundation. -->
Never use text combinations that does not meet meet at least 4.5:1 contrast."
Always refer to accessibility standards what is described by https://www.w3.org/TR/WCAG21/ 