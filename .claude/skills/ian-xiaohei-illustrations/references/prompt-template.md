# Image Generation Prompt Template

Use this template to construct prompts for each illustration.

---

## Base Style Prompt (always include)

```
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines, sketch quality. Sparse colored annotations: red for emphasis, orange for flow/arrows, blue for secondary labels. No gradients, no shadows, no glow effects. No commercial illustration style. No PPT or infographic layout. 16:9 landscape format. At least 35% of canvas is blank white space. Main subject occupies 40–60% of canvas width.
```

---

## Character Prompt (always include)

```
Central character is Xiaohei: a small solid-black figure, white circular dot eyes, thin irregular limbs, blank expression, slightly wobbly outline. Always wearing a small straw hat, hand-drawn with wobbly lines, tilted slightly to one side — present in every image without exception. Xiaohei must actively perform the core conceptual action — not stand watching or act as decoration. If Xiaohei were removed, the metaphor should collapse.
```

---

## Structure Type Prompts (pick one)

**Workflow:**
```
Left-to-right or top-to-bottom sequence of 3–5 stages. Xiaohei is at a transition point between stages. Stages represented by low-tech physical objects, not UI components.
```

**Before / After:**
```
Split canvas: left side shows [problem state], right side shows [resolved state]. Visual contrast is obvious without reading labels. Xiaohei appears in [one side / both sides].
```

**Conceptual Metaphor:**
```
Physical low-tech scenario that maps onto the concept. [Describe the invented metaphor]. Xiaohei performs [specific action] that drives the metaphor.
```

**Character State:**
```
Xiaohei in a specific physical posture embodying [state]. Environment reinforces the mood through [describe elements]. No abstract symbols — only physical metaphors.
```

**System / Modules:**
```
Loosely arranged physical modules or zones. Xiaohei operates or connects [key element]. Objects represent system components using low-tech physical things.
```

**Method / Layers:**
```
Horizontal layers or stacked zones. Xiaohei works within or between the layers. Sketch-like, not formal pyramid chart.
```

**Map / Journey:**
```
Winding or branching path with waypoints. Xiaohei is positioned at [meaningful point on the path]. Exploratory feel, not a formal decision tree.
```

**Comic Strip:**
```
[N] mini panels in a grid. Each panel: one action only. Xiaohei appears across panels in sequence: [describe each panel briefly].
```

---

## Annotation Prompt (always include)

```
5–8 short handwritten-style English text labels placed near relevant elements. Each label: 2–8 words maximum. Casual, slightly irregular lettering — not typeset. No paragraph text. No title text in corners.
```

---

## Full Assembled Prompt Example

```
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines, sketch quality. Sparse colored annotations: red for emphasis, orange for flow arrows, blue for secondary info. No gradients, no shadows. 16:9 landscape. At least 35% blank white space.

Central character Xiaohei: solid black, white dot eyes, thin wobbly limbs, blank expression. Xiaohei physically cranks a hand-operated sorting mechanism. Objects of different sizes flow in from the left; Xiaohei sorts them into two output channels on the right. The mechanism is low-tech — like a hand-cranked wooden sorter, not a digital interface.

5 handwritten labels: "raw input" near the left pile, "turn the crank" near Xiaohei's hands, "filtered" on the small-objects channel, "kept" on the large-objects channel, "nothing automatic" near the crank handle. Labels in casual slightly-wobbly handwriting style.

No title text. No background decoration. Xiaohei is the necessary operator — remove them and the sorting mechanism has no driver.
```

---

## Edit Prompts

**Remove corner title:**
```
Edit this image: remove the title text in the top-left corner (and any underline beneath it). Keep all other elements exactly as they are. Do not add any new text or objects.
```

**Strengthen Xiaohei's role:**
```
Regenerate this image keeping the core concept. Make Xiaohei the actual structural driver — not a bystander. Increase the sense that Xiaohei is operating or causing the thing to work. More bizarre, still clean white background, still minimal labels.
```

**Reduce visual complexity:**
```
Simplify this image: remove [specific overcrowded elements]. Keep only one core action and 3–5 short labels. Maintain the white background and hand-drawn style.
```
