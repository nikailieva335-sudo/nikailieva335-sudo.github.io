---
layout: default
title: CAD
parent: Engineering Projects
nav_order: 4
permalink: /engineering-projects/cad/
---

# CAD Projects

---

## Standard Hybrid 6 Year-Old Model Neck.
Crash-test 6 year old dummy neck device design. Plates, brackets and load cell mount.

<div class="drawing-grid three-col">
  <div class="drawing-item">
    <img src="/images/Neck_Hybrid_III.png" alt="Hybrid III Neck Assembly" style="max-width: 250px;">
    <p>Neck Hybrid View 1</p>
  </div>
  <div class="drawing-item">
    <img src="/images/Neck_Hybrid_III_v2.png" alt="Hybrid III Neck Assembly v2" style="max-width: 300px;">
    <p>Neck Hybrid View 2</p>
  </div>
  <div class="drawing-item">
    <img src="/images/Loading_Cell_Drawing_1.png" alt="Loading Cell Drawing" style="max-width: 380px;">
    <p>Loading Cell</p>
  </div>
</div>

<div class="drawing-grid two-col">
  <div class="drawing-item">
    <img src="/images/Molded_Neck_Drawing_1.png" alt="Molded Neck Drawing" style="max-width: 380px;">
    <p>Molded Neck</p>
  </div>
  <div class="drawing-item">
    <img src="/images/Lower_Neck_Bracket_Drawing_1.png" alt="Lower Neck Bracket Drawing" style="max-width: 380px;">
    <p>Lower Neck Bracket</p>
  </div>
  <div class="drawing-item">
    <img src="/images/Top_Plate_Drawing_1.png" alt="Top Plate Drawing" style="max-width: 380px;">
    <p>Top Plate</p>
  </div>
  <div class="drawing-item">
    <img src="/images/Bottom_Plate_Drawing_1.png" alt="Bottom Plate Drawing" style="max-width: 380px;">
    <p>Bottom Plate</p>
  </div>
  <div class="drawing-item">
    <img src="/images/Nodding_Plate_Drawing_1.png" alt="Nodding Plate Drawing" style="max-width: 380px;">
    <p>Nodding Plate</p>
  </div>
</div>

---

## Lightbox Enclosure

Designed a character-themed light-up enclosure combining custom PCB design with 3D-printed housing. Used KiCad to create the timer and blinking LED schematic and PCB layout, and Onshape to design the CAD enclosure.

- Developed, troubleshot, and tested a blinking LED and timer circuit using an Arduino microcontroller
- Designed the schematic and PCB layout in KiCad
- Modeled the enclosure in Onshape to house the electronics

<div class="drawing-grid two-col">
  <div class="drawing-item">
    <img src="/images/Lightbox_V1.png" alt="Lightbox V1" style="max-width: 380px;">
    <p>View 1</p>
  </div>
  <div class="drawing-item">
    <img src="/images/Lightbox_V2.png" alt="Lightbox V2" style="max-width: 400px;">
    <p>View 2</p>
  </div>
</div>

---

## Frog EMG

Collaboration with Duke Pediatric Hospital to produce a toy EMG for children receiving EMG Botox treatments. Expected to be implemented for 150 patients per year. 

<div class="drawing-grid">
  <div class="drawing-item">
    <img src="/images/Grace_Samek_Frog_EMG.png" alt="Frog EMG Device" style="max-width: 400px;">
    <p>Frog EMG</p>
  </div>
</div>

<style>

.drawing-grid {
  display: grid;
  grid-template-columns: repeat(minmax(100px, 1000px));
  gap: 2rem 1.5rem;
  margin: 1.5rem 0;
}
.drawing-item {
  margin-bottom: 1rem;
}

.drawing-grid.two-col {
  display: flex;
  justify-content: left;
  gap: 1rem;
  flex-wrap: wrap;
}

.drawing-grid.three-col {
  display: flex;
  justify-content: left;
  gap: 1rem;
  flex-wrap: wrap;
}

.drawing-item img {
  width: 100%;
  height: auto;
  display: block;
  margin: 0 auto;
  border: 1px solid #444;
  border-radius: 6px;
  background: transparent;
}
.drawing-item p {
  text-align: center;
  font-size: 0.875rem;
  color: #aaa;
  margin: 0.5rem 0 0;
}

@media (min-width: 50rem) {
  .main {
    max-width: 70rem;
  }
}
</style>