# Maria Saigon

## Mission
Create implementation-ready, token-driven UI guidance for Maria Saigon that is optimized for consistency, accessibility, and fast delivery across content site.

## Brand
- Product/brand: Maria Saigon
- URL: http://127.0.0.1:5501/index.html
- Audience: readers and knowledge seekers
- Product surface: content site

## Style Foundations
- Visual style: clean, functional, implementation-oriented
- Main font style: `font.family.primary=Inter`, `font.family.stack=Inter, sans-serif`, `font.size.base=16px`, `font.weight.base=400`, `font.lineHeight.base=25.6px`
- Typography scale: `font.size.xs=13px`, `font.size.sm=16px`, `font.size.md=17px`, `font.size.lg=18px`, `font.size.xl=20px`, `font.size.2xl=21px`, `font.size.3xl=26px`, `font.size.4xl=48px`
- Color palette: `color.text.primary=#0a0a0a`, `color.surface.base=#000000`, `color.border.muted=#756657`, `color.text.inverse=#405f1c`, `color.surface.muted=#ffffff`, `color.surface.raised=#111111`, `color.surface.strong=#fcfbf8`
- Spacing scale: `space.1=7px`, `space.2=8px`, `space.3=9px`, `space.4=10px`, `space.5=12px`, `space.6=14px`, `space.7=16px`, `space.8=17px`
- Radius/shadow/motion tokens: `radius.xs=4px`, `radius.sm=16px`, `radius.md=18px`, `radius.lg=28px`, `radius.xl=50px`, `radius.2xl=999px` | `shadow.1=rgba(64, 95, 28, 0.32) 0px 2px 5px 0px`, `shadow.2=rgba(58, 42, 36, 0.06) 0px 8px 24px 0px`, `shadow.3=rgba(64, 95, 28, 0.1) 0px 18px 40px 0px`, `shadow.4=rgba(58, 42, 36, 0.08) 0px 14px 36px 0px`

## Accessibility
- Target: WCAG 2.2 AA
- Keyboard-first interactions required.
- Focus-visible rules required.
- Contrast constraints required.

## Writing Tone
Concise, confident, implementation-focused.

## Rules: Do
- Use semantic tokens, not raw hex values, in component guidance.
- Every component must define states for default, hover, focus-visible, active, disabled, loading, and error.
- Component behavior should specify responsive and edge-case handling.
- Interactive components must document keyboard, pointer, and touch behavior.
- Accessibility acceptance criteria must be testable in implementation.

## Rules: Don't
- Do not allow low-contrast text or hidden focus indicators.
- Do not introduce one-off spacing or typography exceptions.
- Do not use ambiguous labels or non-descriptive actions.
- Do not ship component guidance without explicit state rules.

## Guideline Authoring Workflow
1. Restate design intent in one sentence.
2. Define foundations and semantic tokens.
3. Define component anatomy, variants, interactions, and state behavior.
4. Add accessibility acceptance criteria with pass/fail checks.
5. Add anti-patterns, migration notes, and edge-case handling.
6. End with a QA checklist.

## Required Output Structure
- Context and goals.
- Design tokens and foundations.
- Component-level rules (anatomy, variants, states, responsive behavior).
- Accessibility requirements and testable acceptance criteria.
- Content and tone standards with examples.
- Anti-patterns and prohibited implementations.
- QA checklist.

## Component Rule Expectations
- Include keyboard, pointer, and touch behavior.
- Include spacing and typography token requirements.
- Include long-content, overflow, and empty-state handling.
- Include known page component density: buttons (62), cards (49), links (21), inputs (7), navigation (2).


## Quality Gates
- Every non-negotiable rule must use "must".
- Every recommendation should use "should".
- Every accessibility rule must be testable in implementation.
- Teams should prefer system consistency over local visual exceptions.
