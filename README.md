# Zhiying Shiguang

**Zhiying Shiguang** (`纸影拾光`) is a Codex skill for turning ordinary photos into restrained paper-zine artworks. It preserves a real visual anchor from the source image, then compresses the surrounding scene into pale paper, soft blue-gray print, pencil linework, risograph grain, torn edges, and generous white space.

The skill is designed for editorial, handmade, fine-art zine results rather than glossy filters, scrapbook layouts, or generic poster effects.

## What It Does

- Reads the source photo before editing: subject, space, light, color memory, mood, and visual clutter.
- Chooses between two creative paths:
  - **Real-scene collage**: keep the original photo, or a recognizable crop, as the anchor.
  - **Image distillation**: reinterpret the photo as a hand-drawn illustration based on mood and structure.
- Produces quiet paper-based compositions with ivory paper texture, restrained torn edges, pale watercolor, pencil hatching, and soft risograph/halftone print.
- Treats portraits carefully by preserving identity, expression, pose, gaze, hands, and age impression.

## Best For

- Travel photos
- Architecture and city scenes
- Family and portrait photos
- Everyday moments with a clear emotional anchor
- Photography that should become a printed, handmade zine plate

## Install

Place this folder in your Codex skills directory, or keep it anywhere you can reference explicitly:

```bash
~/.codex/skills/zhiying-shiguang
```

If you keep the repository elsewhere, invoke it by path or copy it into your skills directory.

## Usage

In Codex, ask for the skill by name:

```text
Use $zhiying-shiguang to turn this photo into a restrained paper-zine artwork.
```

For portraits, be explicit if identity preservation matters:

```text
Use $zhiying-shiguang. Keep the person recognizable, preserve the face, expression, hands, and pose, but give the whole image a dry paper-print texture.
```

## Style Principles

- Preserve the strongest subject anchor from the photo.
- Reduce background density into pale blue-gray print, pencil line, and watercolor haze.
- Use torn edges only where the image dissolves into paper.
- Leave real white space; do not fill the page with decoration.
- Avoid stickers, tape, large titles, note cards, heavy frames, and scrapbook compositions.
- Keep text tiny and secondary, or omit it entirely.

## Portrait Handling

Portraits are judged by both likeness and paper treatment. The face should not become a generic illustration, but it also should not look like an untouched photo pasted onto a stylized background.

The skill asks Codex to:

- Preserve face geometry, eye direction, expression, hair, age impression, hands, and pose.
- Apply dry paper grain, light desaturation, faded ink, and subtle halftone texture to the face.
- Avoid cloudy coatings, waxy glaze, wet watercolor film, or muddy washes over facial features.
- Treat eyes, mouth, teeth, nostrils, and fingers as hard-preserve areas.

## Repository Contents

```text
.
├── SKILL.md
└── agents/
    └── openai.yaml
```

`SKILL.md` contains the working instructions Codex reads when the skill is invoked. `agents/openai.yaml` provides UI metadata such as the display name and default prompt.

