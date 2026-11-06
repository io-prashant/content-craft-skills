---
name: prashant-youtube-thumbnail
description: Generate 16:9 YouTube thumbnails from 8 named layout patterns - Prashant's real face composited as a photo cutout (never a generated face), strong cinematic grading, 0-4 word hook text, one dominant color plus one accent. The 8 references cover 8 distinct layout patterns (ranking columns, vs split, concept composite, handwritten hook, giant distressed word, tweet wall, cinematic scene, cream editorial), each with its own recipe and fill-in prompt in references/patterns.md. Use when asked to make a YouTube thumbnail, recreate a reference layout, or produce cover art for his videos.
---

# Prashant YouTube Thumbnail

Build a 1280x720 (16:9) thumbnail from ONE of the 8 layout patterns in `references/patterns.md`, with Prashant's real face and his video's topic swapped in. Each pattern recipe defines the layout, type behavior, color story and texture. Swap only the identity (face), the words and the topic props.

The recipes are self-contained: layout, measurements, colors, type and a fill-in prompt are all in the text. Reference images are NOT required and NOT distributed; if the user supplies their own reference image for a pattern, study it alongside the recipe.

Hard identity rule: the face in the final image is always the supplied real photo, composited as a cutout. Never generate, repaint or edit a face, and never generate or change an expression - if the concept needs a different expression, ask for a different photo.

## Inputs (collect before designing)

1. **Video topic + the one hook**: the claim, number, result or tension the video actually delivers. If unclear, ask one question: "What is the one claim or feeling this video delivers?" Then proceed.
2. **Pattern choice**: pick from the 8 patterns below, or the user names one. Match pattern to topic type (see references/patterns.md).
3. **Face photo (required)**: a real photo of Prashant, supplied by the user for each job, whose real expression already fits the concept. The photo is used as-is, composited as a cutout - the face and expression are never generated or altered. Keep beard and hair natural. Plain solid-color tee or dark jacket, no logos.
4. **Optional**: exact text he wants, extra props that actually appear in the video.

## The 8 patterns

| File | Pattern | Use for |
|---|---|---|
| 01-ranking-rainbow-columns | vertical color columns, one per item, number on top, face in front | lists, levels, rankings |
| 02-vs-split-worlds-big-numbers | two contrasting worlds, big corner numbers, hype smile | versus, comparisons, gaps |
| 03-concept-composite-app-iv | photoreal metaphor scene with labeled props | addiction, burnout, system metaphors |
| 04-handwritten-hook-arrow | hand-drawn marker words + arrow + small high-angle face | motivation, challenge |
| 05-giant-distressed-word-dark | one enormous distressed word, small dark figure in front | one-word dark topics |
| 06-tweet-wall-highlight-box | UI-card wall, friendly lowercase text, one word on a highlight box | confessions, opinions |
| 07-real-scene-cinematic-hook | real environment, shallow DOF, one huge condensed word | habits, routines, relatable scenes |
| 08-cream-editorial-serif | cream paper, giant serif word, photo cutout breaking into letters | history, knowledge, storytelling |

Each pattern has a full recipe, approximate measurements and its own fill-in prompt in `references/patterns.md`. Use that pattern's prompt, not a generic one.

## Global design menu (apply only what the chosen pattern shows)

These are the building blocks observed across the reference set. Each pattern uses a subset; the pattern recipe in patterns.md states which. Do not stack all of them onto every thumbnail.

- Canvas: 16:9, 1280x720 minimum. One idea per thumbnail: one face, one concept, 0-4 words. Subject fills 35-60% of frame, eyes near the upper third line.
- Layered depth: background > mid objects > face cutout > text in front. Text may overlap the lower body, never the eyes. Keep text and face out of the bottom-right corner (timestamp overlay).
- Expression: exaggerated and readable at tiny size (shock, regret, thinking, authority stare, hype smile). This is a photo-SELECTION criterion - pick the supplied photo whose real expression fits; never manufacture one. Eyes to camera, or to the key object with an arrow pointing the same way.
- Face treatment where the pattern uses a cutout: thin 4-8px outline or soft shadow, optional colored rim light, face brightened, eyes sharpened, warm skin against a cooler background.
- Grade: high contrast, deep blacks, vignette at corners on the dark patterns. One dominant color + black/white + one accent. Saturation high on accents, muted on backgrounds. Light film grain. The cream editorial pattern is the exception: bright, flat, clean.
- Text: 1-4 words, roughly 15-30% of canvas. Hook phrasing, not title phrasing. Heavy condensed ALL CAPS sans is the default; the pattern recipe names the actual font behavior. Two-tone text or a solid highlight box only where the pattern uses one. Hinglish and Hindi hooks follow the same weights, 2-3 words.
- Icons/arrows: app logos or flat icons, hand-drawn arrows, only where the pattern uses them, and only for things that actually appear in the video.

## Content truth rules (apply to every pattern, no exceptions)

- Every word, number, icon, logo, card and prop must represent something actually in the video or approved by the user. No invented lesson titles, no invented UI cards or endorsements, no logos of tools not featured.
- Column/step counts match the real content count. If the video has 3 lessons, render 3 columns. Add a teased extra (pixelated or "?") only when the video itself teases an unrevealed item.
- No fake stats, money claims, progress numbers or rankings.
- Prashant's real face only, from a supplied photo. No other creator's face, branding or literal text copied from a reference.

## Workflow

1. **Study the chosen pattern's recipe** in references/patterns.md: layout grid, face position, text position and treatment, color story, background type. If the user also supplied a reference image, note its curiosity gap and any extra detail the recipe does not capture.
2. **Write the concept in 1-2 lines**: pattern + hook text (<=4 words, real) + expression + palette.
3. **Generate the scene, background and text** with an image model, using the pattern's fill-in prompt from patterns.md. The supplied face photo is NOT input for regeneration - it stays untouched for compositing. Put overlay text in the prompt in CAPS inside quotes. Generate 2 variants when cheap.
4. **Composite the real face cutout** onto the generated scene in an editor; re-set text in a real font when the model mangles letters; add outline/shadow per the pattern recipe.
5. **Run the QC checklist** below plus the pattern's own must-haves from patterns.md.
6. Deliver the PNG with one line naming the pattern used. Offer one round of targeted tweaks.

## QC checklist (global; each pattern adds its own in patterns.md)

- Readable at 168x94 px: face + max 4 words, emotion legible.
- Every word spelled correctly. Zoom in and check each letter.
- Eyes sharp and brightened, looking at camera or the key object.
- Text never covers the eyes; clear of the bottom-right corner; about 3% from edges.
- Light direction on the face matches the background.
- Every element passes the content truth rules above.
- Pattern-specific must-haves from patterns.md all pass. Where a pattern omits an element (outline, arrow, vignette, icons), its absence is correct, not a defect.

## Rule precedence

If a reference breaks a style preference, you may follow the reference's style. That exception covers style only: it never overrides the content truth rules, identity rules, or third-party rights (no copied faces, logos, exact text or branding).
