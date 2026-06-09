# QA Checklist

Run every generated image through this checklist before delivery.

---

## Must-Pass (Hard Requirements)

- [ ] **16:9 landscape format** — not square, not portrait
- [ ] **Pure white background** — no gradients, no texture, no shadow on background
- [ ] **Black hand-drawn line art** — slightly wobbly lines, sketch aesthetic
- [ ] **Xiaohei is the active subject** — performing the core action, not watching or decorating
- [ ] **Xiaohei removal test passes** — removing Xiaohei would break the metaphor
- [ ] **One core concept only** — not multiple ideas crammed into one image
- [ ] **At least 35% whitespace** — canvas is not overcrowded
- [ ] **Maximum 8 annotations** — short labels only, no paragraph text
- [ ] **No title text in corners** — no "Workflow:", "Diagram:", or similar header text
- [ ] **No commercial/PPT aesthetic** — does not look like a slide or stock illustration

---

## Failure Signals

If any of these are true, the image fails and needs iteration:

| Signal | Problem |
|---|---|
| Looks like a course slide or tutorial page | Style failure — too formal |
| Xiaohei is standing in a corner watching | Character integration failure |
| Xiaohei looks cute, smiling, or emoji-like | Character treatment failure |
| Background has color, texture, or gradient | Style failure |
| Multiple concepts compete for attention | Concept focus failure |
| Dense text or label paragraphs visible | Annotation failure |
| Standard metaphor reused (funnel, ladder, conveyor) | Originality failure |
| Formal flowchart boxes and arrows | Style failure |
| Drop shadows, glow, or digital effects | Polish failure |

---

## Iteration Guidance

**If the image looks too generic:**
- Make Xiaohei the action subject — Xiaohei should be *doing* the concept
- Add a strange but valid physical metaphor
- Strip out background elements until only the essential remains

**If the image is too complex:**
- Delete nodes until only one action remains
- Keep 3–5 labels maximum
- Remove any secondary figures or objects not directly part of the core metaphor

**If Xiaohei feels decorative:**
- Redesign so that Xiaohei operates a mechanism or performs a physical transformation
- The structure should require Xiaohei — not just include Xiaohei

**If the style looks too clean / digital:**
- Emphasize wobbly lines in the prompt
- Remove any smooth gradients or perfect shapes
- Ask for "rough sketch quality, white paper, not digital illustration"

---

## The Core Delivery Standard

> A high-quality image makes the reader think **"that's odd"** — and then understand the structure within 1 second.
>
> If it looks like a tutorial page rather than a bizarre product sketch on white paper: **it fails.**
