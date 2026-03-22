---
layout: default
title: Recorded Drawings
year: 2026
date: 2026-03-22
thumbnail: /images/drawing-thumb.jpg
drawing_data: /assets/recorded-drawing-data/drawing-01.json
---

<h1 class="project-title"><em>{{ page.title }}</em><span class="year">, {{ page.year }}</span></h1>

<div class="drawing-replay">
    <canvas id="replayCanvas" data-source="{{ page.drawing_data }}"></canvas>
</div>