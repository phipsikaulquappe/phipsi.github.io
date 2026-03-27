---
layout: default
title: Recorded Drawings
year: 2026
date: 2026-03-22
hide_project_navigation: true
recorded_drawings:
  - /assets/recorded-drawing-data/drawing-01.json
  - /assets/recorded-drawing-data/drawing-02.json
  - /assets/recorded-drawing-data/drawing-03.json
  - /assets/recorded-drawing-data/drawing-04.json
  - /assets/recorded-drawing-data/drawing-05.json
  - /assets/recorded-drawing-data/drawing-06.json
  - /assets/recorded-drawing-data/drawing-07.json
  - /assets/recorded-drawing-data/drawing-08.json
#   - /assets/recorded-drawing-data/drawing-09.json
#   - /assets/recorded-drawing-data/drawing-10.json
  
---

<h1 class="project-title">
    <em>{{ page.title }}</em><span class="year">, {{ page.year }}</span>
</h1>

<div class="drawing-replay">
    <canvas
        id="replayCanvas"
        data-drawings='{{ page.recorded_drawings | jsonify }}'>
    </canvas>
    <div class="recorded-drawing-navigation">
    <button class="drawing-nav drawing-nav-left" id="drawingNavLeft" aria-label="Previous drawing">
        ←
    </button>
    <p id="drawingCounter" class="drawing-counter"></p>
    <button class="drawing-nav drawing-nav-right" id="drawingNavRight" aria-label="Next drawing">
        →
    </button>
</div>

<p id="drawingCounter" class="drawing-counter"></p>