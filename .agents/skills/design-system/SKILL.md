---
name: design-system-home
description: Creates implementation-ready design-system guidance with tokens, component behavior, and accessibility standards. Use when creating or updating UI rules, component specifications, or design-system documentation.
---

<!-- TYPEUI_SH_MANAGED_START -->

# Home

## Mission
Deliver implementation-ready design-system guidance for Home that can be applied consistently across e-commerce storefront interfaces.

## Brand
- Product/brand: Home
- URL: https://mariasaigon.ch/
- Audience: online shoppers and consumers
- Product surface: e-commerce storefront

## Style Foundations
- Visual style: structured, accessible, implementation-first
- Main font style: `font.family.primary=Inter`, `font.family.stack=Inter, sans-serif`, `font.size.base=16px`, `font.weight.base=400`, `font.lineHeight.base=25.6px`
- Typography scale: `font.size.xs=12px`, `font.size.sm=13px`, `font.size.md=14px`, `font.size.lg=14.4px`, `font.size.xl=15px`, `font.size.2xl=15.52px`, `font.size.3xl=16px`, `font.size.4xl=17px`
- Color palette: `color.text.primary=#0a0a0a`, `color.text.secondary=#ffffff`, `color.text.tertiary=#756657`, `color.text.inverse=#f1f1f1`, `color.surface.base=#000000`, `color.surface.muted=#8d9e44`, `color.surface.raised=#fcfbf8`, `color.surface.strong=#111111`
- Spacing scale: `space.1=1.4px`, `space.2=1.44px`, `space.3=1.8px`, `space.4=1.86px`, `space.5=2px`, `space.6=4px`, `space.7=5px`, `space.8=7px`
- Radius/shadow/motion tokens: `radius.xs=8px`, `radius.sm=10px`, `radius.md=20px`, `radius.lg=30px`, `radius.xl=50px`, `radius.2xl=999px` | `shadow.1=rgba(64, 95, 28, 0.32) 0px 2px 5px 0px` | `motion.duration.instant=200ms`, `motion.duration.fast=300ms`

## Accessibility
- Target: WCAG 2.2 AA
- Keyboard-first interactions required.
- Focus-visible rules required.
- Contrast constraints required.

## Writing Tone
concise, confident, implementation-focused

## Rules: Do
- Use semantic tokens, not raw hex values in component guidance.
- Every component must define required states: default, hover, focus-visible, active, disabled, loading, error.
- Responsive behavior and edge-case handling should be specified for every component family.
- Accessibility acceptance criteria must be testable in implementation.

## Rules: Don't
- Do not allow low-contrast text or hidden focus indicators.
- Do not introduce one-off spacing or typography exceptions.
- Do not use ambiguous labels or non-descriptive actions.

## Guideline Authoring Workflow
1. Restate design intent in one sentence.
2. Define foundations and tokens.
3. Define component anatomy, variants, and interactions.
4. Add accessibility acceptance criteria.
5. Add anti-patterns and migration notes.
6. End with QA checklist.

## Required Output Structure
- Context and goals
- Design tokens and foundations
- Component-level rules (anatomy, variants, states, responsive behavior)
- Accessibility requirements and testable acceptance criteria
- Content and tone standards with examples
- Anti-patterns and prohibited implementations
- QA checklist

## Component Rule Expectations
- Include keyboard, pointer, and touch behavior.
- Include spacing and typography token requirements.
- Include long-content, overflow, and empty-state handling.

## Quality Gates
- Every non-negotiable rule must use "must".
- Every recommendation should use "should".
- Every accessibility rule must be testable in implementation.
- Prefer system consistency over local visual exceptions.

<!-- TYPEUI_SH_MANAGED_END -->
