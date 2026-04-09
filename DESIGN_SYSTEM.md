# Two Swans - Design System (Working File)

This file defines how the interface is designed, structured, and animated.

The goal is not to generate UI.
The goal is to preserve taste, clarity, and intention.

---

## 1. Core Principle

Design is not decoration.
Design is guidance.

Every screen must answer:
- What should the user understand?
- What should they do next?

If unclear -> remove or restructure.

---

## 2. Layout Logic

- Use structured asymmetry, not rigid grids everywhere
- Alternate left / right compositions
- Maintain strong vertical rhythm
- Use breathing space intentionally, not empty space

Avoid:
- perfect symmetry everywhere
- tight stacking
- chaotic overlaps

---

## 3. Typography

Headlines:
- serif (Instrument Serif / Playfair)
- editorial, calm, confident
- large, but not aggressive

Body:
- Inter
- readable, slightly airy
- never too light or too small

Hierarchy:
- clear separation between headline / body / support
- avoid decorative text styling

---

## 4. Color System

Base:
- white / off-white background
- dark text

Accent:
- soft blush tones (`#F3E8EA`, `#EADDE1`)

Usage:
- highlight surfaces
- subtle emphasis
- never loud

Avoid:
- strong color contrast
- multiple accent colors

---

## 5. Card System

Cards are:
- soft, rounded
- lightly elevated
- slightly tinted, not pure white

States:
- default: calm
- hover: lift (`-4px`), soft shadow increase

Never:
- scale aggressively
- over-style

---

## 6. Motion Philosophy

Motion is not animation.
Motion is behavior.

Rules:
- opacity + translateY (`10-16px`)
- duration: `200-700ms`
- easing: `cubic-bezier(0.16, 1, 0.3, 1)`

Avoid:
- bounce
- elastic motion
- large parallax
- looping effects

---

## 7. Signature Motion

"Swan line":
- thin curved line
- drawn once in hero
- fades into background

Meaning:
- flow
- guidance
- pairing

Never repeat aggressively.

---

## 8. Composition (Case Study Section)

Use curated layout:
- 1 hero image (dominant)
- 2 support images
- 1 accent image

Rules:
- slight vertical offsets
- subtle overlap
- no grid alignment

Thread system:
- horizontal line
- images "attached" visually

This is a key storytelling section.

---

## 9. Interaction Language

Links:
- soft underline reveal

Cards:
- lift slightly

Buttons:
- small lift + tone shift

Everything should feel:
- smooth
- inevitable
- calm

---

## 10. Restraint Rule

If something feels:
- decorative
- noticeable
- trendy

Reduce it.

The design should feel:
quiet, confident, and intentional.

---

## 11. Final Check

Before shipping any screen:

Ask:
- Is it clear?
- Is it calm?
- Is it guiding action?

If not -> refine.
