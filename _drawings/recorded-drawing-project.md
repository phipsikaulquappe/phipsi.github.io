---
layout: default
title: Recorded Drawings
year: 2026
date: 2026-03-22
thumbnail: /images/drawing-thumb.jpg
recorded_drawings:
  - /assets/recorded-drawing-data/drawing-01.json
  - /assets/recorded-drawing-data/drawing-02.json
  - /assets/recorded-drawing-data/drawing-03.json
---

<h1 class="project-title">
    <em>{{ page.title }}</em><span class="year">, {{ page.year }}</span>
</h1>

<div class="drawing-replay-wrapper">
    <button class="drawing-nav drawing-nav-left" id="drawingNavLeft" aria-label="Previous drawing">
        ←
    </button>

    <div class="drawing-replay">
        <canvas
            id="replayCanvas"
            data-drawings='{{ page.recorded_drawings | jsonify }}'>
        </canvas>
    </div>

    <button class="drawing-nav drawing-nav-right" id="drawingNavRight" aria-label="Next drawing">
        →
    </button>
</div>

<p id="drawingCounter" class="drawing-counter"></p>