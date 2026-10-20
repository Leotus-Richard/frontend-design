---
name: frontend-design
description: Design, critique, audit, or refine a frontend surface using product-specific UX and visual craft guidance. Use for hierarchy, typography, layout, responsive states, accessibility, motion, copy, and design systems; backend-only work and native runtime setup are outside this skill.
---

# Frontend design

Improve the named surface while respecting its users, product facts, functionality,
and existing design authority. This portable hub does not enable Impeccable's native
runtime, scripts, browser overlays, hooks, pin shortcuts, or update machinery.

## Read the real surface

Identify the requested mode: planning, evaluation, refinement, or implementation.
Inspect supplied PRODUCT.md/DESIGN.md, tokens, components, assets, screenshots,
and the actual target when tools permit. Missing DESIGN.md does not establish
greenfield scope. Keep pinned fonts, palettes, content, and brand decisions.
Ask only for missing constraints that materially affect the result; do not invent
claims, testimonials, images, or product capabilities.

## Choose the smallest relevant playbook

Use these references for design judgment and examples, not their archived native
helper commands. Each copied playbook is labeled source-only; no helper is installed.

| Task | Optional playbook |
| --- | --- |
| Plan a new/replacement surface | [shape](references/source/impeccable/references/upstream/reference/shape.md), [new work](references/source/impeccable/references/upstream/reference/new-work.md) |
| Evaluate UX or technical quality | [critique](references/source/impeccable/references/upstream/reference/critique.md), [audit](references/source/impeccable/references/upstream/reference/audit.md) |
| Refine an existing interface | [craft floor](references/source/impeccable/references/upstream/reference/craft-floor.md), [polish](references/source/impeccable/references/upstream/reference/polish.md), [distill](references/source/impeccable/references/upstream/reference/distill.md) |
| Improve a specific dimension | [type](references/source/impeccable/references/upstream/reference/typeset.md), [layout](references/source/impeccable/references/upstream/reference/layout.md), [copy](references/source/impeccable/references/upstream/reference/clarify.md), [color](references/source/impeccable/references/upstream/reference/colorize.md), [motion](references/source/impeccable/references/upstream/reference/animate.md) |
| Adapt or harden states | [adapt](references/source/impeccable/references/upstream/reference/adapt.md), [harden](references/source/impeccable/references/upstream/reference/harden.md), [onboard](references/source/impeccable/references/upstream/reference/onboard.md) |

Keep a refinement within the established identity. Replace the visual direction
only when redesign is requested. For planning, return the brief before code.
For evaluation, identify concrete locations and separate observed technical
findings from subjective judgment; do not silently edit an evaluation-only target.
A heuristic score is not accessibility or compliance certification.

## Implement and verify within scope

For authorized UI edits, use real content and meaningful interaction states,
clear hierarchy, responsive layouts, keyboard access, visible focus, adequate
contrast, reduced-motion support, and useful loading/error/empty states.
Prioritize the visitor's actual task over decorative novelty. Use platform-specific
[iOS](references/source/impeccable/references/upstream/reference/ios.md) or
[Android](references/source/impeccable/references/upstream/reference/android.md)
references only for the corresponding target; do not claim platform conformance
from a reference checklist alone.

Batch a useful desktop/mobile/state/keyboard verification pass when tools exist.
Repair material findings within the requested budget, then confirm the relevant
states. Report unavailable browser, renderer, measurement, or asset evidence
instead of claiming it passed. Avoid open-ended polishing without a task benefit.

Return the requested brief, review, or change with actual verification limits.
Trackers, commit tools, remote targets, and asset services are optional integrations
subject to current authorization and available tools; no sibling plugin is required.

## Source-only resources

The [reference index](references/README.md) preserves all Impeccable playbooks and
an optional experience-first principle. `native-resources.zip` remains unchanged,
archived evidence: never extract it into a host-scanned skill root or execute its
helpers as part of this hub. Native integration requires a separately scoped review
and test, including dependencies, host/OS behavior, ownership, and cleanup.
Historical tool paths, global local-only/identity rules, and persistent-mode directions
are source examples. Preserve the Apache-2.0 license and original MIT attributions.
