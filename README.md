# 3D parametric model fortifcation 

An open-source toolkit for archaeologists and researchers to help with 3D reconstructions of fortifications. This tool uses Blender's Geometry Nodes.
This code is part of the article: Ondrej, F. 2026. Parametric 3D model of the high medieval fortification on the example of the Upper Fortress in Kestřany. IANSA

---

## Description

This repository contains a procedural (parametric) 3D model of historical fortifications, designed for rapid reconstruction, visualization, and analysis of medieval defensive architecture.
The model is implemented in Blender (Geometry Nodes) and allows users to generate complex fortification elements—such as ramparts, towers, gates, and architectural details—based on simple input geometry and adjustable parameters.

## Contents

 - `parametric model fortifcation.rar` - a tool for generating and reconstructing fortifications based on measured values.
 -` Manual.docx` - detailed instructions for setting up the basic geometry, applying the parametric model, and a guide to the variables that need to be supplied for reconstruction.

---

##Features

### Parametric generation of fortifications

- Curtain walls (ramparts)
- Towers (circular and polygonal)

### Wide range of architectural elements

- Crenellations and parapets
- Loopholes and firing chambers
- Wall-walks (open, covered, wooden)
- Buttresses, arches, and structural supports
- Gates and gatehouses
- Oriel windows and bartizans

### Adaptation to terrain

- Variable wall height along segments

### Non-destructive workflow

- Parameters can be adjusted at any time before applying the model

---

## Basic Usage

- Open `parametric model fortifcation.blend` in Blender.
- Proceed with the parametric model according to the manual.

---
## Basic/Optional workflow (tutorial)

 - 1. Create simple input geometry (plane for walls, circle/polygon for towers)
 - 2. Adjust geometry to match the desired ground plan
 - 3. Apply the parametric model via Geometry Nodes
 - 4. Modify parameters to achieve the desired architectural form
 - 5. (Optional) Convert to mesh for export or further editing

---

## Limitations

- The model generates linear wall segments (complex layouts require duplication and composition)
- After applying the model, the result becomes a static mesh (no longer parametric)
- The system is designed for interpretative reconstruction, not exact replication of specific monuments

---

## Requirements

- Blender 4.2 or newer

---

## License

Released under the **CC BY 3.0 License**, encouraging modifications and adaptations for academic and research purposes.
