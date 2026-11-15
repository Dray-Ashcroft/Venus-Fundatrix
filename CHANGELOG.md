<h1 align="center">Changelog</h1>

<p align="center"><em>Venus Fundatrix · Interactive 3D Female Anatomy Simulator</em></p>

<p align="center">
  <a href="#rc-xi--credits-update">RC XI</a> ·
  <a href="#rc-x--final-release">RC X</a> ·
  <a href="#rc-i--initial-release">RC I</a>
</p>

---

## Release Summary

| Release | Title | Date | Focus |
|:--|:--|:--|:--|
| RC XI | Credits Update | 15 Nov 2026 | © credits button, Project Designer credit, README rewrite *(current)* |
| RC X | Final Release | 19 Oct 2026 | New uterus model, anteverted view, Material 3 stage stepper |
| RC I | Initial Release | 19 Oct 2026 | Four-stage anatomy simulator |

---

## RC XI · Credits Update

*15 Nov 2026 · Current release*

**Changed**
- Credits tab replaced by a round © button
- Credits panel now opens with "Project Designer: Sai Prasad, MSc. Agri Entomology"
- Ovary TS illustration credited to Sai Prasad
- README rewritten in the standard format: tables, credits, collapsible model and library lists

**Added**
- `CHANGELOG.md`
- Optional single-file build: `index.html`, `style.css`, `app.js` and `assets.js` merged into one offline file

---

## RC X · Final Release

*19 Oct 2026*

**Changed**
- Stage 3 uterus model replaced (Beste Zengin, CC BY 4.0); shown anteverted, tilted forward over the bladder
- Stage 3 camera set at a slight angle so the forward tilt is visible
- Stage 3 label dots repositioned for the new model
- Stage stepper redesigned as Material 3 style bubbles: the current stage grows into a labelled pill
- Infundibulum card now covers the fimbriae; ovary card notes that follicles lie in the cortex
- Stronger key light on the models

**Removed**
- Previous uterus model (CC BY-NC 4.0, non-commercial only)
- Separate Fimbriae and stage 3 Corpus luteum dots (corpus luteum remains in the Ovary T.S.)

**Fixed**
- Stage buttons gained titles and labels for screen readers

---

## RC I · Initial Release

*19 Oct 2026*

**Added**
- Four stages: Body, Pelvic Organs, Uterus and Ovaries, Ovary T.S.
- Tappable organs, ligaments, neighbouring organs and bones in stage 2, with Show layers switches
- Label dots for the uterus, oviduct and ovary in stage 3
- Ovary transverse section with follicle stages and corpus luteum in stage 4
- Info panel with stage text and part cards
- Reset view, Full screen and Credits
- Models bundled in `assets.js` for offline use

---

<p align="center">
  <a href="README.md">README</a> · <a href="LICENSE">License (MIT)</a>
</p>
