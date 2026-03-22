---
layout: default
title: Recorded Drawing Project
year: 2026
date: 2026-03-22
drawing_data: /assets/recorded-drawing-data/drawing-02.json
---

<h1 class="project-title"><em>{{ page.title }}</em><span class="year">, {{ page.year }}</span></h1>

<div class="drawing-replay">
    <canvas id="replayCanvas" data-source="{{ page.drawing_data }}"></canvas>
</div>