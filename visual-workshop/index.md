---
layout: visual-workshop
title: Visual Analysis Workshop
description: Reading archival images through AI analysis and rhetoric & composition theory
---

# Visual Analysis Workshop

## Introduction

This page documents an exercise in comparative visual analysis. For each of
four archival images drawn from the Library of Congress, I paired an AI
(Claude) analysis with my own disciplinary reading as a rhetoric and
composition scholar. The goal was not to test whether the AI's reading is
"correct," but to notice where it converges with and diverges from a
discipline-specific lens — one trained to ask questions about literacy
sponsorship, genre, ethos, and the rhetorical work images do in constructing
writers, readers, and writing instruction across time.

Each image is presented with its archival metadata, followed by the two
readings side by side. A closing reflection considers what this exercise
suggests about AI-assisted visual analysis as a method for rhetoric and
composition research.

---

{% for entry in site.data.visual_workshop %}
{% include workshop-image-analysis.html entry=entry %}
---
{% endfor %}

## Reflection

For this exercise I selected four public-domain archival images from the Library of Congress relevant to the history of rhetoric and composition: a photograph of a teacher and students gathered around library books, a photograph of a teacher modeling cursive penmanship at a chalkboard, an exterior photograph of Stephen King's house in Bangor, Maine, and an 18th-century hand-colored satirical print titled "The Moment of Imagination." I asked Claude to describe and analyze each image, then paired its output with metadata and my own disciplinary reading.
Across all four images, Claude is reliably accurate at the level of visual description. What Claude consistently missed was context that depends on disciplinary knowledge rather than visual information alone. It described the chalkboard photograph as a handwriting lesson without registering that the model text on the board reflects an entire pedagogy built on imitation rather than process. With the King house, Claude could name the architectural style and the bat-and-spider ironwork but did not connect that ornamentation to the rhetorical work of authorial branding. The starkest gap was in the 1788 print, where Claude's description was accurate but flat — it read the image as a catalog of objects rather than as satire about the writing process itself.
For students, the most valuable takeaway is this: AI-assisted visual analysis is a strong starting point for description and metadata, but it tends to treat images as inventories of objects rather than as rhetorical acts embedded in genres, audiences, and historical conversations. The guiding question is not whether the AI is right, but what its reading reveals about how it processes images — and what that reveals about what a trained disciplinary reader brings to the same material.
