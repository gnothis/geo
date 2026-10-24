<div align="center">

# 📐 Interactive Geometry 4.0 (Interactive Geometry PWA)

<p align="center">
  <b>An interactive educational web course covering planimetry, trigonometry, and stereometry for desktops and mobile devices.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-active-success?style=for-the-badge&logo=none" alt="Status">
  <img src="https://img.shields.io/badge/math-KaTeX-blue?style=for-the-badge" alt="KaTeX">
  <img src="https://img.shields.io/badge/platform-Web%20%2F%20PWA-orange?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="License">
</p>

</div>

---

## 🧭 Overview

**Interactive Geometry 4.0** is a powerful interactive web application designed to explore and visualize geometric principles. It combines "live" sketches with draggable vertices (via mouse or touch), rigorous mathematical proofs, mathematical formulas powered by **KaTeX**, and practical inquiry-based quests.

The app is fully responsive, optimized for both desktop monitors and mobile/tablet devices (featuring full touch support, pinch-to-zoom gestures, layer bars, and a built-in mobile simulator view).

---

## 📚 Course Structure & Modules

### 📐 2D Planimetry & Trigonometry (10 Modules)
1. **Angles & Parallel Lines** — adjacent, vertical angles, and transversal line rules (alternate interior "Z", corresponding "F", consecutive interior "C").
2. **Centers & Euler Line** — orthocenter ($H$), centroid ($M$, ratio 2:1), circumcenter ($O$), incenter ($I$), and triangle midline.
3. **Congruence & Similarity** — congruence criteria (SAS, ASA, SSS) and area scaling laws ($S_2 = k^2 \cdot S_1$).
4. **Pythagorean Theorem** — geometric construction of squares on sides and an animated proof by rearrangement.
5. **Sine & Cosine Laws** — proofs via the circumscribed circle diameter ($2R$) and generalized Pythagorean theorem for acute/obtuse angles.
6. **Quadrilaterals** — properties of parallelograms, rectangles, rhombuses, squares, and trapezoids.
7. **Areas & Perimeter** — formula derivations through shape dissection into rectangles.
8. **Secrets of the Circle** — tangents ($\perp R$), chords, secants, inscribed and circumscribed quadrilaterals.
9. **Inscribed & Central Angles** — proof that $\angle APB = \frac{1}{2} \angle AOB$ using isosceles triangles with radius $R$.
10. **Trigonometry** — sine, cosine, and tangent on the unit circle, alongside the left-hand root rule ($\sqrt{N}/2$).

### 🧊 3D Stereometry & Space
* **Platonic Solids** — tetrahedron, cube, octahedron, dodecahedron, icosahedron: why there are strictly 5 in the universe, their connection to Plato's elements, and duality pairs.
* **3D Polyhedra Gallery** — interactive rotation, wireframes, and translucent faces.
* **Bodies of Revolution** — generation of cylinders, cones, and spheres from 2D profiles.
* **Interactive Cross-Sections** — dynamic cutting planes with polygon detection (including a regular hexagon inside a cube).
* **Unfolding** — smooth folding of 3D figures from flat patterns.
* **Euler's Formula** — verification of $V - E + F = 2$ across various polyhedra.

### 🎯 Interactive Research Quests
1. **"Banish the Orthocenter Out!"** — find vertex positions where the altitude intersection point moves outside the triangle.
2. **"Catch Thales' Right Angle"** — locate the chord position that forms a $90^\circ$ inscribed angle.
3. **"Hexagonal Cube Cross-Section"** — configure the cutting plane to slice a hexagon.
4. **"Queen Dido's Problem"** — an interactive exploration of the isoperimetric problem (why a circle encloses maximum area for a fixed perimeter).

---

## 🛠️ Tech Stack

* **Core:** HTML5 Canvas, Vanilla JavaScript (ES6+), CSS3 (utilizing modern CSS variables and responsive Grid/Flex containers).
* **Mathematics:** [KaTeX](https://katex.org/) for high-performance math typesetting.
* **UI/UX:** Fully responsive (touch-action, multi-touch, mobile frame simulator, layer bars, and live metrics dashboard).

---
