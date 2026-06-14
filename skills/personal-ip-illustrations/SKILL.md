---
name: personal-ip-illustrations
description: "Generate Ian/Xiaohei-inspired Chinese article illustrations using the user's fixed personal IP: a hand-drawn East Asian cartoon boy paired with a white Bichon Frise companion. Use when the user asks for 手绘配图, 个人IP配图, 小黑风格, 正文插图, 文章配图, 观点解释图, 白底手绘图, or wants to replace 小黑 with the user's own IP while preserving the clean absurd product-sketch style."
---

# Personal IP Illustrations

Generate 16:9 horizontal Chinese article illustrations in a clean, absurd, hand-drawn product-sketch style. The recurring visual IP is always the user's cartoon boy plus a white Bichon Frise companion.

The goal is not a cute poster, mascot sticker, formal PPT diagram, or commercial illustration. The goal is one clear whiteboard-like image that turns a key idea, workflow, state, or metaphor into a simple strange physical action.

## Read As Needed

- `references/ip-guidelines.md`: fixed boy IP, Bichon companion, style keywords, and taboos.
- `references/composition-patterns.md`: structure types, metaphor method, object pool, and action rules.
- `references/prompt-template.md`: reusable generation prompt template.
- `references/qa-checklist.md`: post-generation checks and iteration rules.
- `assets/examples/`: visual calibration only. Do not copy the example composition.

## Workflow

1. Extract the image's single core idea from the user's article, paragraph, screenshot, or request.
2. Pick one structure type from `references/composition-patterns.md`.
3. Turn the abstract idea into one low-tech physical action: press, sort, pull, catch, repair, weigh, connect, open, filter, carry, or fold.
4. Make the boy perform the main conceptual action.
5. Make the Bichon actively help with a smaller supporting action.
6. Generate one image per prompt. Do not combine multiple requested images into one canvas unless the user asks for a small comic panel.
7. Check the result with `references/qa-checklist.md`. Regenerate or edit if either character is decorative, the image looks like PPT, or the style drifts away.

## Required Generation Rules

- Use a 16:9 horizontal canvas.
- Use a pure white background.
- Use minimalist black hand-drawn line art with soft pencil/color-pencil texture.
- Preserve large empty space; the main subject should occupy about 40%-60% of the canvas.
- Use only a few short handwritten Chinese labels, usually 0-6 labels.
- Use orange only for the main path or arrow.
- Use red only for a key warning, problem, or result.
- Use blue sparingly for secondary notes and for the boy's shirt.
- Do not write a top-left title or the structure type on the image.
- Do not copy the original Xiaohei character. Replace it with the personal boy IP and Bichon companion.

## Character Rule

The boy and the Bichon must be paired by default. The boy carries the main conceptual action. The Bichon performs a visible supporting action, such as pushing a scrap, holding a string, guarding a tiny gate, fetching a card, nudging a lever, carrying a shuttlecock, or helping sort items.

If removing either character would not change the image's meaning, rewrite the prompt.

## Prompting

Use `references/prompt-template.md` as the base. Fill the variables with the current article idea, then use the image generation tool. If the user provides reference images, treat them as identity/style references and keep the same IP rules unless the user explicitly asks to change the character design.

## Saving

For project-bound output, save selected final images into the workspace, preferably:

```text
assets/personal-ip-illustrations/
```

Name files with a short ordered slug, for example:

```text
01-idea-press.png
02-handoff-path.png
```
