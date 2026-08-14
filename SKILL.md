---
name: zhiying-shiguang
description: Transform ordinary photos into restrained "纸影拾光" paper artworks: preserve a real photo anchor while compressing the scene into pale paper, watercolor, line drawing, risograph grain, soft blue-gray printing, torn edges, and generous white space. Use when the user asks to make a photo look like "纸影拾光", hand-drawn zine, paper magazine artwork, torn-paper photo illustration, real-scene collage, image distillation, or an editorial artwork derived from a supplied photo.
---

# 纸影拾光

## Overview

Create a paper-zine artwork from a source photo. Read the scene first, then choose one of two paths:

- **Real-scene collage**: keep the original photo, or a recognizable crop of it, as the anchor. Compress the rest into pale paper printing, watercolor haze, line drawing, and restrained torn-paper edges.
- **Image distillation**: do not include the photo directly. Extract the photo's emotion, spatial relationships, color temperature, and implied story, then redraw it as a handmade illustration.

Default to a restrained hand-drawn paper publication style: closer to a fine-art zine plate than a scrapbook page.

## Scene Reading

Before generating or editing, identify these elements from the supplied photo:

1. **Subject anchor**: the person, object, building, landscape edge, gesture, or silhouette that must remain memorable. For people, the face, expression, age impression, and gesture are the highest-priority anchors.
2. **Spatial rhythm**: foreground, middle ground, background, horizon, direction of movement, and negative space.
3. **Light and weather**: hard sun, haze, indoor shadow, dusk, snow, reflection, neon, overcast calm, etc.
4. **Color memory**: 2-4 colors that carry the photo's feeling, not every literal color.
5. **Unspoken mood**: quietness, distance, heat, waiting, intimacy, travel fatigue, ceremony, solitude, playfulness, or tension.
6. **What to omit**: visual clutter, accidental objects, busy texture, irrelevant signage, awkward crops, and over-detailed backgrounds.

Use this reading to write a short "observation note" if the user asks for process notes. Otherwise, keep it internal and go straight to the image work.

## Choose A Path

Use **real-scene collage** when:

- The photo has a strong subject the user likely wants preserved.
- The original texture, face, building, place, or documentary evidence matters.
- The user says "保留照片", "拼贴", "实景", "原照片作为锚点", or asks for a before/after-like result.

Use **image distillation** when:

- The user emphasizes mood, illustration, hand drawing, abstraction, or a less literal reinterpretation.
- The photo is visually ordinary but has a strong atmosphere.
- The user says "照片不进成品", "蒸馏", "重新创作", "插画", or "更手绘".

If the user does not choose, decide based on the scene. For portraits, recognizable architecture, travel memories, and pets, usually keep a photo anchor. For scenery, interiors, street fragments, and mood boards, distill more freely.

## People And Portraits

When a photo contains a person, especially a child, portrait, family member, or candid gesture, preserve identity before style:

- Keep face structure, eye direction, expression, hairstyle, age impression, and pose close to the source photo.
- Preserve meaningful hand positions and actions, such as drawing, holding, hugging, running, turning back, or looking up.
- Separate identity structure from surface treatment. Do not change facial geometry, but do apply visible paper treatment to the face surface: dry warm-ivory paper grain, faded ink, restrained pale peach tint, light blue-gray shadow hatching, and subtle risograph/halftone texture.
- Keep face treatment dry and breathable. Avoid wet watercolor film, cloudy coating, waxy glaze, muddy wash, or a translucent mask over the face.
- Paperize skin visibly but gently. The face should not look like an untouched photo pasted onto a paper background, and it should not be repainted as a generic illustration face. Eyes, mouth, teeth, and nostrils are hard-preserve areas: add only dry grain, slight desaturation, and very light ink texture there.
- Let backgrounds, clothing edges, and secondary objects dissolve first. Keep eyes, mouth, nose, fingers, and core facial silhouette legible.
- Place torn-paper edges around background, hair outer contour, shoulders, clothing, or negative space. Do not tear through eyes, mouth, hands, or other identity-critical areas.
- For human subjects, default to real-scene collage unless the user explicitly requests image distillation. If identity is lost, the result is a failure even when the paper style is attractive.
- Avoid changing ethnicity, age, facial proportions, hairstyle, body type, expression, gaze, or relationship between people.

For portraits and family photos, score both identity preservation and visible face treatment. A result where the person no longer resembles the source should receive at most 3/5. A result where the face is unchanged while only the background is stylized should also receive at most 3.5/5.

## Composition Rules

Build the final image like a quiet physical zine plate:

- Use a warm off-white paper base with visible grain, fiber, scan noise, or uneven ink absorption.
- Leave a calm field of paper around the image, but keep the subject visually dominant. For landscapes, city scenes, architecture, and non-portrait documentary photos, the image field should usually occupy about 70-80% of the page; avoid making the artwork look like a small pasted image on a huge blank sheet.
- Use torn-paper edges mainly where the image dissolves into the paper, especially along one or two sides. Do not build a busy frame.
- Convert background density into soft blue-gray, pale cyan, muted teal, warm beige, and faded ink. Use high-purity color only as a tiny accent if the source photo needs it.
- Keep the subject anchor sharp enough to read; let secondary areas soften into watercolor wash, pencil hatching, halftone, or risograph texture.
- Prefer a single composed artwork, not a scrapbook spread. Avoid visible tape, stickers, note cards, large title blocks, bullet lists, and decorative captions.
- Add tiny typewriter-like caption text only when the user asks for text or when it is nearly invisible and secondary.
- Avoid glossy photo filters, heavy cinematic grading, fake scrapbook stickers, ornate frames, social-media poster effects, cute sticker packs, and large handwritten slogans.

For the user's preferred style, bias toward hand-drawn details: pencil contour lines, light watercolor blooms, dry-brush edges, imperfect ink hatching, and paper-grain printing. Keep the result quiet and airy.

## Prompt Pattern

When using an image generation or image editing tool, assemble the prompt in this structure:

```text
Create a restrained "纸影拾光" paper artwork from the provided photo.
Scene reading: [subject anchor], [spatial rhythm], [light/weather], [color memory], [mood].
Path: [real-scene collage OR image distillation].
Composition: warm off-white paper base, generous white space, restrained torn paper edges where the image dissolves into paper, minimal accents only.
For landscapes/city/architecture: keep the image field around 70-80% of the page with moderate margins; avoid excessive blank paper or a tiny central pasted-image effect.
Style: restrained hand-drawn editorial zine plate, pale watercolor wash, pencil contour, dry brush, subtle blue-gray risograph/halftone grain, imperfect ink registration.
Preserve/emphasize: [important subject, gesture, place, or atmosphere].
If people are present: preserve identity, face proportions, expression, gaze, age impression, hairstyle, pose, hands, and meaningful action.
For faces: keep geometry unchanged, but visibly paperize the surface with dry grain, faded ink, slight desaturation, and subtle pencil/halftone shadow. Avoid cloudy coating or wet film over facial features.
Simplify/remove: [clutter and accidental details].
Avoid: scrapbook layout, big titles, stickers, tape, note cards, bullet journaling, glossy filter, generic poster, heavy frame, photorealistic redraw, generic illustration face, changed identity, cloudy face coating, waxy facial glaze.
```

For **real-scene collage**, add:

```text
Keep the original photo or a recognizable crop as the visual anchor. Turn surrounding detail into pale paper printing, watercolor haze, and line drawing; use torn edges only where the image transitions into blank paper.
```

For **image distillation**, add:

```text
Do not place the photo directly in the final artwork; reinterpret it as a hand-drawn illustration based on its mood, geometry, and color memory.
```

## Output Checklist

Before finalizing, verify:

- The final piece clearly feels like paper, not a flat digital filter.
- Torn edges and white space are compositionally meaningful, not random decoration.
- The subject has enough visual weight. For landscapes, city scenes, and architecture, avoid excessive outer blank paper; the image should usually occupy about 70-80% of the page.
- The source photo's subject or mood is still traceable.
- If people are present, identity, expression, gaze, age impression, hands, and pose are preserved well enough to recognize the source.
- If people are present, the face surface has visible dry paper/print treatment without changing facial geometry or adding a cloudy coating.
- Color accents are restrained and support the scene's movement or emotion.
- The hand-drawn style is visible in line, texture, and edge quality.
- Text, if present, is tiny and secondary; the image should still work with no text.
- For portraits, do not rate the result above 3/5 if the face no longer resembles the source, even if the paper style is good.
