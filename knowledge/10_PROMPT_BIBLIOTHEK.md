# 10_PROMPT_BIBLIOTHEK.md

# Zweck dieser Datei

Diese Datei enthält die zentrale Prompt-Bibliothek für Kinderbuchzauber GPT.

Alle Standardprompts werden hier gesammelt.

Vorteile:

- einfache Wartung
- einheitliche Qualität
- konsistente Ergebnisse
- keine doppelten Prompts in mehreren Dateien

---

# GRUNDREGELN

Für alle Bildprompts gilt:

- Englisch
- ein Prompt pro Bild
- professioneller Stil
- keine Marken
- keine Franchise-Stile
- keine Wasserzeichen
- keine Texte im Bild

---

# UNIVERSALER QUALITÄTSBLOCK

Kann an nahezu jeden Bildprompt angehängt werden.

```text
modern professional children's book quality, clear focal point, clean composition, generous safe margins, polished illustration, no vintage filter, no yellow tint, no grain, no blur, no muddy details, no excessive glow, no glitter overload, no chaotic background, no copied brand style, no text, no watermark
```

---

# BILDERBUCH-PROMPTS

## Standard Bilderbuchseite

```text
A modern, high-quality children's book illustration for [AGE RANGE], showing [SCENE]. The composition is designed as a full book page with a calm integrated light text area in [TEXT AREA POSITION]. Main character: [CHARACTER]. Mood: [MOOD]. Style: polished contemporary children's book illustration, clear shapes, warm but clean colors, professional publishing quality, strong focal point, generous safe margins, no hard text box, no border, no vintage filter, no yellow tint, no grain, no blurry details, no overdecorated background, no text in the image.
```

---

## Bilderbuch Doppelseite

```text
Professional children's picture book double-page spread for ages [AGE RANGE]. Scene: [SCENE]. Main character: [CHARACTER]. Wide cinematic composition designed for a printed picture book spread, clear focal point, integrated light text area, balanced storytelling illustration, contemporary publishing quality, warm clean color palette, no text, no border, no watermark.
```

---

# COVER-PROMPTS

## Standard Frontcover

```text
Create a flat front cover design for a [BOOK TYPE] for [AGE RANGE]. Theme: [THEME]. Main visual: [MAIN VISUAL]. Mood: [MOOD]. The cover should look modern, professional, high-quality, marketable, and original, with a strong focal point, clear title hierarchy, generous safe margins, excellent Amazon thumbnail readability, and a clean contemporary color palette. Include planned space for title, subtitle, author name, and optional USP badge inside the safe area. No 3D mockup, no book fold, no perspective, no border, no vintage filter, no yellow tint, no grain, no blurry details, no glitter overload, no chaotic background, no copied brand style, no text errors.
```

---

## Cover-Neuentwurf

```text
Redesign this children's book cover concept into a cleaner, more professional, more marketable version. Improve hierarchy, readability, focal point, thumbnail impact, and overall publishing quality. Modern children's publishing style, no clutter, no visual noise, no vintage effects.
```

---

# CHARAKTER-PROMPTS

## Neuer Charakter

```text
Create an original children's book character design for [AGE RANGE]. Character: [NAME/ROLE]. Personality: [PERSONALITY]. Visual traits: [TRAITS]. Outfit: [OUTFIT]. The character should be unique, friendly, expressive, and easy to recognize, with a clear silhouette and consistent design language. Modern professional children's book illustration style, clean shapes, appealing proportions, no brand resemblance, no copied franchise style, no text, no watermark.
```

---

## Charakter-Konsistenz

```text
Create a new illustration of the same original character using the established character bible: [CHARACTER BIBLE]. Keep the same silhouette, proportions, clothing system, colors, facial features, and signature accessory. New scene: [SCENE]. Maintain consistent children's book illustration style and do not change the character design.
```

---

# MALBUCH-PROMPTS

## Standard Malvorlage

```text
Pure black and white coloring page for kids, [MAIN SUBJECT], designed for children aged [AGE RANGE]. The main subject is large, centered, friendly, and fully visible with wide safety margins. True bold and easy coloring book style, thick uniform black outlines, smooth continuous solid black lines, every contour fully closed and connected, large simple open coloring spaces, clean vector-like line art, no tiny details, no trapped spaces, no shading, no greyscale, no gradients, no texture, no sketch lines, no broken lines, no faded line edges, no background clutter, pure #000000 lines on a pure #FFFFFF white background, print-ready, easy to color with crayons and markers.
```

---

## Anti-Lücken-Version

```text
Professional children's coloring book page, [MAIN SUBJECT], very simple bold and easy design. Use heavy solid black ink outlines with thick uniform line weight. All outer contours and inner shapes must be completely closed paths with no gaps, no breaks, no fading, no disconnected strokes, no open contours. Large open coloring areas only, simple rounded shapes, minimal child-friendly details, centered composition, full subject visible, wide blank margins. Pure black line art on a completely white background. No shading, no grey pixels, no gradients, no color, no texture, no stippling, no hatching, no sketch style, no thin adult line art, no tiny details, no clutter, no frame.
```

---

# MALBUCH-REPARATURPROMPTS

## Offene Linien

```text
Revise this coloring page into a cleaner print-ready version. Strengthen every outline into thick solid black continuous lines. Close all open contours and reconnect all broken strokes. Remove faded line edges, grey pixels, sketch texture, thin lines, and tiny trapped spaces. Keep the same subject and composition, but simplify the design into large closed coloring areas on a pure white background. No shading, no greyscale, no gradients, no texture.
```

---

## Zu viele Details

```text
Simplify this coloring page for young children. Keep only one large central main subject and a few simple supporting elements. Remove tiny patterns, small decorative details, clutter, and complex background elements. Use thick bold black outlines, large open coloring spaces, fully closed shapes, and a clean white background. No shading, no greyscale, no texture.
```

---

## Grauer Hintergrund

```text
Convert this into a pure black and white print-ready coloring page. Make the background completely flat white #FFFFFF. Remove all grey pixels, paper texture, shadows, gradients, noise, and shading. Keep only solid black #000000 outlines with clean closed paths and large white coloring areas.
```

---

## Negativprompt Malbuch

```text
shading, greyscale, gradient, color, yellow tint, vintage filter, paper texture, canvas texture, background grain, digital noise, blurry lines, sketchy lines, pencil lines, faint lines, grey lines, faded line edges, transparent outlines, open contours, broken outlines, pixelated edges, messy patterns, random line clutter, tiny unreadable details, trapped coloring spaces, overfilled background, facial features on objects, frame, border, watermark, text, signature
```

---

# RÄTSELBUCH-PROMPTS

## Rätselseite

```text
Create a print-ready puzzle book page for children aged [AGE RANGE].

Puzzle type: [PUZZLE TYPE]

Difficulty: [EASY/MEDIUM/HARD]

Theme: [THEME]

The page must include:

- clear title
- short instruction
- child-friendly layout
- enough whitespace
- safe margins
- one verifiable solution

Avoid clutter, tiny details, confusing layouts, decorative overload, and unreadable elements.

Include the answer key.
```

---

## Quizseite

```text
Create a print-ready quiz page for children aged [AGE RANGE] about [TOPIC]. Include a clear heading, one short instruction, [NUMBER] numbered questions, and 3 to 4 answer choices per question. Each question must have exactly one correct answer, no ambiguity, no trick questions, and no misleading options. Use a clean, child-friendly layout with large readable text, enough whitespace, and safe margins. Mark the difficulty as [EASY/MEDIUM/HARD]. Also create the matching answer list.
```

---

## Escape-Rätsel

```text
Create an escape puzzle as part of a continuing children's story for ages [AGE RANGE].

Difficulty: [EASY/MEDIUM/HARD]

The solution must be logically derived from previously provided information.

No random guessing.

No hidden information.

Provide clear page navigation and a verifiable solution.

End with a check: Can a child understand where the solution came from?
```

---

# METADATEN-PROMPTS

## Titelentwicklung

```text
Generate 20 original children's book title ideas for:

Book type: [BOOK TYPE]
Target age: [AGE]
Theme: [THEME]

Requirements:

- easy to remember
- marketable
- child-friendly
- no trademark risk
- suitable for Amazon KDP
```

---

## Untertitel

```text
Generate 10 professional subtitle ideas for this children's book.

Title: [TITLE]
Target age: [AGE]
Book type: [BOOK TYPE]

Focus on clarity, benefits, and audience relevance.
```

---

## Buchbeschreibung

```text
Write a professional Amazon KDP book description for:

Book type: [BOOK TYPE]
Target age: [AGE]
Theme: [THEME]

Structure:

1. Hook
2. What is inside
3. Benefits
4. Target audience
5. Closing paragraph

Professional, readable, parent-friendly language.
```

---

## Keywords

```text
Generate keyword ideas grouped by:

- Book type
- Theme
- Age
- Benefits
- Activities
- Audience
- Emotions

Avoid keyword stuffing and trademarks.
```

---

# KDP-UPLOADCHECK

```text
Review this project before KDP upload.

Check:

- Format
- Page count
- Cover
- Safe area
- Bleed
- Metadata
- Keywords
- Description
- Categories
- Marketability
- Royalty considerations

Provide a structured checklist and identify possible risks.
```

---

# ABSCHLUSSREGEL

Neue Prompts werden ausschließlich in dieser Datei ergänzt.

Prompts sollen nicht mehrfach in anderen Wissensdateien gespeichert werden.

Diese Datei dient als zentrale Prompt-Bibliothek für den gesamten GPT.