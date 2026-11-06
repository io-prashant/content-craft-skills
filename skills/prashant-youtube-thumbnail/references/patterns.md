# Pattern recipes + per-pattern prompts (8 patterns)

These recipes are self-contained: layout, measurements, colors, type and a fill-in prompt for each pattern. Measurements and palettes are approximate. If the user supplies their own reference image for a pattern, study it alongside the recipe and let it refine details; never copy literal text, faces or branding from any reference.

Every generation prompt below produces the SCENE, BACKGROUND, PROPS and TEXT only - no person, no face. The face is added afterwards as a separate compositing step: cut out the user's supplied real photo and place it where the layout puts the subject. Never generate or alter a face or its expression; if the pattern needs an expression the supplied photo does not have, ask for a different photo.

## 01-ranking-rainbow-columns
- Layout: vertical color stripes filling the full frame, equal widths, one per item. Huge black number at the top of each column (roughly top 15-20% of height). Small flat icon or app logo near each column's bottom third. Face cutout stands in front of the middle columns, chest-up, about 45-55% of frame width.
- Colors: column stripes in rainbow order (sampled approx #D9110D red, #F5AC12 amber, then yellow, green, blue); face zone dark (#1A1B1D behind subject).
- Type: numbers in a heavy rounded sans, solid black on the column color, each with a small black "level" label beneath; optional 2-word title strip across the bottom.
- Count rule: number of columns = the real number of items in the video. A pixelated or "?" column only if the video itself teases an unrevealed item.
- Must-haves: equal column widths; flat colors with slight top-to-bottom gradient; numbers aligned; face overlapping two columns.
- Prompt: "16:9 YouTube thumbnail background. [N] vertical color columns in rainbow order (red, orange, yellow, green, blue), a huge black condensed number at the top of each, a small flat white icon near the bottom of each column showing [REAL ITEMS FROM THE VIDEO]. Bottom strip text '[2-3 WORDS]' in heavy white condensed sans. Flat print texture, sharp, no people, no extra words." Then composite the supplied face cutout in front of the middle columns with a thin white outline and soft shadow.

## 02-vs-split-worlds-big-numbers
- Layout: frame split left/right into two contrasting environments (approx 40/60). Huge white-outlined numbers in the top corners (top 12-15%). Face dead center foreground, chest-up, big open smile.
- Colors: bright sky/water tones (sampled approx #E9EAEA light grey, #97A4AD blue-grey, #EAB009 yellow accent on the "rich" side).
- Type: corner numbers in extra-bold sans with thick white outline; no other words needed.
- Must-haves: clear visual contrast between the two sides; both numbers truthful and approved; saturated, bright grade.
- Prompt: "16:9 YouTube thumbnail background, split scene: left side [WORLD A from the video], right side [WORLD B], huge white-outlined numbers '[REAL NUMBER A]' top-left and '[REAL NUMBER B]' top-right. Bright saturated cinematic grade, crisp edges, no people, no other text." Then composite the supplied face cutout centered in front, chest-up.

## 03-concept-composite-app-iv
- Layout: photoreal metaphor scene. Hospital bed centered, IV bags above each labelled with an app logo, subject in bed, worried face. Cool grade.
- Colors: cold teal-blue (sampled approx #111E20 dark teal, #2B5C68, #347587), logo glow accents.
- Type: no headline needed; labels on the props carry the concept.
- Must-haves: one clear metaphor rendered photoreal; matching light direction and shadows across subject, props and labels; labels only for things actually in the video.
- Prompt: "16:9 YouTube thumbnail, photoreal conceptual scene: [METAPHOR SCENE], props labelled [REAL ITEMS FROM THE VIDEO] with soft glow. Cold teal-blue grade, cinematic contrast, vignette, film grain, no people, no headline text." Then composite the supplied face cutout into the scene where the layout puts the subject.

## 04-handwritten-hook-arrow
- Layout: dark red gradient scene. Huge white hand-drawn marker words across the top (roughly top 25-30%). Subject small in frame, shot from a high angle, looking up. Hand-drawn white arrow curving from text to face.
- Colors: deep red to black (sampled approx #631B0A, #9C290C, #2C0D04), white marker strokes (#F9F6F5).
- Type: informal marker handwriting, uneven strokes, natural wobble. 2-4 words.
- Must-haves: hand-drawn texture on both text and arrow; strong scale contrast between tiny face and giant words.
- Prompt: "16:9 YouTube thumbnail background, dark red-to-black gradient. Huge white hand-drawn marker text '[HOOK, 2-4 WORDS]' across the top with a hand-drawn white arrow curving down toward the lower third. Moody red lighting, grain, no people, no other text." Then composite the supplied face cutout small in frame where the arrow points.

## 05-giant-distressed-word-dark
- Layout: one enormous distressed display word filling the frame edge to edge (about 70-80% of width). A small dark figure stands in front; letters sliced and hidden behind the body. Black background, red haze.
- Colors: black + red (sampled approx #140304, #A70202, #D10202).
- Type: tall condensed distressed serif/display caps, stamped ink texture, one word only.
- Must-haves: type as the environment; subject masking the word; deep shadows; no second text element.
- Prompt: "16:9 YouTube thumbnail background, black with red haze. One enormous distressed red display word '[ONE WORD]' filling the frame, tall condensed stamped-ink letters, clear space in the lower center. Cinematic contrast, heavy grain, no people, no other text." Then composite the supplied face cutout as a small dark figure in front, partly masking the letters, lit by red rim light.

## 06-tweet-wall-highlight-box
- Layout: background wall of layered UI cards, slightly rotated, some blurred. Subject center-front, doubtful or regretful expression. Friendly bold geometric lowercase text; the key word reversed out on a solid highlight box.
- Colors: dark scene (sampled approx #151415) with white cards (#ECE9EB) and a yellow highlight box.
- Type: bold geometric sans, lowercase or title case, 2-4 words; key word on a solid box with dark text, tight padding.
- Must-haves: cards show only real content (actual posts or approved mock content); friendly lowercase voice; the single highlight box.
- Prompt: "16:9 YouTube thumbnail background: a wall of layered social-post cards about [REAL TOPIC], slightly rotated, some blurred for depth. Bold geometric lowercase text '[HOOK]' in white, the word '[KEY WORD]' on a solid yellow box with black text. Cinematic grade, sharp, no people, no other words." Then composite the supplied face cutout center-front.

## 07-real-scene-cinematic-hook
- Layout: a real environment with shallow depth of field (bedroom at night, phone glow on the face from below). One huge condensed word across the top third.
- Colors: blue-teal night tones (sampled approx #1D1522, #323349, #545063), white text (#F1EFF0) with dark stroke.
- Type: heavy condensed ALL CAPS sans, one word plus optional exclamation, dark 4-6px stroke.
- Must-haves: a real relatable scene; phone/screen glow on skin; the single aggressive word; dark room bokeh.
- Prompt: "16:9 YouTube thumbnail background, cinematic photo scene: [REAL SCENE from the video, e.g. a bedroom at night with phone glow], shallow depth of field, blue-teal night grade. Huge condensed white text '[ONE WORD]!' across the top third with a dark stroke. Vignette, film grain, no people, no other text." Then composite the supplied face cutout into the scene, eyes to camera.

## 08-cream-editorial-serif
- Layout: cream paper background. One giant serif word in tall caps (about 60-70% of height). Small spaced-caps labels top and bottom. A photo or statue cutout breaks into the letters from the right side.
- Colors: cream paper (#FDF0E3) + brick red type (#AC2003), black small labels.
- Type: tall elegant serif caps for the main word; tiny letter-spaced caps for labels.
- Must-haves: restraint; paper grain; generous margins; subject overlapping the type; no sans-serif, no glow, no vignette.
- Prompt: "16:9 YouTube thumbnail background on cream paper grain. One giant brick-red serif word '[ONE WORD]' in tall caps, small letter-spaced caps label '[SMALL LABEL]' above and below. Flat editorial print look, generous margins, no people, no glow, no vignette, no other text." Then composite the supplied face cutout breaking into the letters from the right.
