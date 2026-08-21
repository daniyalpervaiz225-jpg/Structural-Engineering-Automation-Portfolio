# Structural Engineering Automation Suite

A collection of proprietary automation tools designed to eliminate repetitive drafting tasks, accelerate structural workflows, and bridge the gap between AutoCAD detailing and ETABS analysis. 

> 🔒 **Code Privacy Notice:** The source code for these tools is proprietary. This repository serves as a portfolio showcase of the features, logic, and visual outputs. For a live demo or licensing inquiries, please contact me directly.

---

## 🚀 Featured Tools

### 1. Automated Bar Bending Schedule (BBS) Generator
Extracts reinforcement details directly from existing AutoCAD beam and slab drawings to generate complete, error-free Bar Bending Schedules.
* **Auto-Extraction:** Reads rebar marks, diameters, spacings, and layout spans instantly.
* **Shape Matching:** Automatically identifies and draws exact bar shapes based on standard bending codes.
* **Format:** Outputs clean, production-ready tables directly inside AutoCAD or exported data sheets.

### 2. Beam Elevation & Detailing Tool
Generates individual, fully-detailed beam elevation drawings automatically.
* **Smart Input processing:** Converts beam framing plan into individual beam reinforcement elevation.
* **Rebar Placement:** Automatically draws top/bottom main bars, stirrup zones, and curtailment setups according to pattern which structural engineer then modifies according to design report.

### 3. Slab Reinforcement Automation Tool
Automates the tedious task of drawing and calling out slab reinforcement across complex floor plans.
* **Layout Generation:** Lays out top and bottom meshes or discrete rebar runs over slabs.
* **Annotation:** Auto-generates clear bar calls, spacing annotations, and scheduling tags.

### 4. AutoCAD-to-ETABS Model Preparation Engine
Converts standard structural drafting layouts into perfect, error-free analytical centerlines for ETABS import in Revit.
* **Beam Splitting:** Automatically splits continuous beams right at the column centerlines.
* **Column Alignment:** Snaps and centers structural columns perfectly to the intersection grids.
* **Beam-Column Centering:** Automatically shifts and aligns beam centerlines directly to the column nodes to ensure proper analytical connectivity.
* **Export Ready:** Import cad drawing into Revit, automate the process of converting cad elements into Revit elements using free Bimify tool avialable on autodesk store, then prepare Revit model for export to etabs.

---

## 🛠️ Built With
* **Host Platform:** Autodesk AutoCAD
* **Development Language/APIs:** Python / AutoLISP / C#.NET.
* **CAD API:** AutoCAD .NET API (ObjectARX wrapper in C#)
* **BIM Environment:** pyRevit framework for structural integration

---

## 📊 Business Impact
* **Time Savings:** Reduces drawing-to-analysis model generation time by up to 80%.
* **Accuracy:** Eliminates human transfer errors between detailing drawings and ETABS modeling.
* **Standardization:** Ensures uniform, error-free BBS sheets that match construction codes perfectly.

---

## 📩 Contact & Demos
Interested in seeing a live demonstration of these tools or discussing custom structural automation workflows? 

* **Developer:** Daniyal Pervaiz
* **Inquiries:** Please reach out via GitHub message or email to schedule a private demo.
