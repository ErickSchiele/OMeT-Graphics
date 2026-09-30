---
name: design-system-untitled
description: Creates implementation-ready design-system guidance derived from local Figma styles in "Untitled".
---

<!-- TYPEUI_SH_MANAGED_START -->

# Untitled

## Mission
Document and operationalize the Untitled style foundations extracted from Figma so teams can build consistent interfaces quickly.

## Brand
- Product/brand: Untitled
- Audience: Designers and engineers building this product
- Product surface: web app

## Style Foundations
- Visual style: token-driven, expressive, polished
- Typography scale: typography/content/sm/regular, typography/content/sm/regular-2, typography/content/lg/bold, typography/content/lg/regular, typography/content/md/semibold
- Color palette: color/background, color/text, color/text-2, color/background-2, color/background-3, color/background-4, color/background-5, color/background-6, color/text-3, color/text-4, Selection Variables/palette/yellow/300, Selection Variables/palette/teal/500, Selection Variables/palette/teal/600, Selection Variables/palette/green/200
- Spacing scale: space-0, space-1, space-2, space-3, space-4, space-6, space-8, space-12
- Radius/shadow/motion tokens: effect/layer/drop-shadow, effect/layer/drop-shadow-2

## Component Families
- buttons
- inputs
- forms
- navigation
- overlays
- feedback
- data display

## Accessibility
- Target: WCAG 2.2 AA
- Keyboard-first interactions required
- Focus-visible rules required
- Contrast constraints required

## Writing Tone
concise, confident, implementation-focused

## Rules: Do
- Use extracted color tokens before introducing one-off values: color/background
- color/text
- color/text-2
- color/background-2
- color/background-3
- color/background-4.
- Use these typography styles consistently: typography/content/sm/regular
- typography/content/sm/regular-2
- typography/content/lg/bold
- typography/content/lg/regular
- typography/content/md/semibold.
- Define all interaction states for interactive components: default
- hover
- focus-visible
- active
- disabled
- and loading.

## Rules: Don't
- Do not duplicate existing style tokens with one-off naming.
- Do not remove focus-visible indicators or keyboard support.
- Do not hard-code raw values where local styles or variables already exist.

## Guideline Authoring Workflow
1. Restate design intent in one sentence.
2. Define foundations and tokens.
3. Define component anatomy
4. variants
5. and interactions.
6. Add accessibility acceptance criteria.
7. Add anti-patterns and migration notes.
8. End with QA checklist.

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
- Every non-negotiable rule uses "must".
- Every recommendation uses "should".
- Every accessibility rule is testable in implementation.
- Prefer system consistency over local visual exceptions.

## Acceptance Checklist
- Frontmatter exists with valid `name` and `description`.
- Guidance is under 500 lines for `skill.md` when possible.
- Accessibility and interaction states are explicitly documented.
- Rules are concrete, testable, and non-ambiguous.
- Output can be reused in other repositories with only variable replacement.

## TypeUI + Agentic Integration
This `SKILL.md` is intended for `typeui.sh` CLI workflows.
It can later be integrated with agentic tools including Claude Code, OpenCode, Gemini CLI, Cursor, and similar assistants.

<!-- TYPEUI_SH_MANAGED_END -->
