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

Replace this section with your closing reflection: what patterns emerged
across the four AI analyses versus your disciplinary readings? Where did
the AI's observations stop short of rhetorical or historical context that a
rhetoric and composition lens supplies? What does this exercise suggest
about using AI tools like Claude as a starting point — rather than a
substitute — for disciplinary visual analysis?
