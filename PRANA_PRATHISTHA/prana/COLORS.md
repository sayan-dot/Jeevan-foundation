# Color System

**Part of:** Prana — The Design Language of Jeevan

**Version:** 1.0

**Status:** Draft

---

# Purpose

This document defines how color is used throughout Jeevan.

Color is one of the fastest ways people understand information.

In healthcare, color should communicate meaning, guide attention, and build trust—not simply decorate the interface.

Every color in Jeevan should have a clear purpose.

---

# Philosophy

Color is communication.

Users should never have to guess what a color means.

The same color should always represent the same concept throughout the application.

Consistency allows users to build familiarity and confidence over time.

Prana uses a restrained color palette because healthcare applications should feel calm rather than visually overwhelming.

---

# Principles

### Color communicates meaning before beauty.

### Every color must have a purpose.

### Less color creates more clarity.

### Never rely only on color to communicate information.

### Colors should support accessibility and readability.

---

# Color Roles

Rather than thinking about individual colors, Prana defines color by purpose.

| Role | Purpose |
|-------|----------|
| Primary | Main actions and brand identity |
| Surface | Cards, backgrounds, containers |
| Success | Completed and positive actions |
| Warning | Requires attention |
| Error | Critical problems or failed actions |
| Neutral | Text, icons, borders and dividers |

---

# Current Color Palette

## Primary

Purpose

Primary actions

Buttons

Active elements

Brand identity

HEX

`#4F8EF7`

---

## Background

Purpose

Application background

HEX

`#F8FAFC`

---

## Surface

Purpose

Cards

Sheets

Containers

HEX

`#FFFFFF`

---

## Text

Primary Text

`#1E293B`

Secondary Text

`#64748B`

Disabled Text

`#94A3B8`

---

## Success

Purpose

Medicine Taken

Successful actions

Positive confirmations

HEX

`#4CAF50`

---

## Warning

Purpose

Medicine due soon

Attention required

HEX

`#F59E0B`

---

## Error

Purpose

Missed medicine

Errors

Critical alerts

HEX

`#EF4444`

---

# Color Usage Rules

Primary Blue should only be used for interactive elements.

Success Green should only communicate successful outcomes.

Warning should encourage attention, not panic.

Error Red should be reserved for situations requiring immediate awareness.

Avoid introducing new colors without a documented purpose.

---

# Accessibility

Color should never be the only indicator of meaning.

Every status should also include:

- Icon
- Label
- Shape or pattern where appropriate

Example

✅ Taken

rather than

Green only.

This ensures the interface remains understandable for users with color vision deficiencies.

---

# What to Avoid

Do not use gradients for primary actions.

Do not use saturated colors as backgrounds.

Avoid using more than one accent color within the same component.

Avoid decorative colors that do not communicate meaning.

---

# Future Considerations

The color system may expand as Jeevan evolves.

Future additions must remain consistent with the philosophy defined in this document.

New colors should solve a communication problem—not introduce visual variety.

---

# Related Documents

DESIGN_PHILOSOPHY.md

ACCESSIBILITY.md

TYPOGRAPHY.md

---

> "Color should guide attention—not compete for it."