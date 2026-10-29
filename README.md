# Box Mockup Generator — Free Beta

**Create packaging mockups in five straightforward steps.** Box Mockup Generator is a free Windows desktop application for designers who work in CorelDRAW, Illustrator, or another vector editor.

This is a **free-to-use, proprietary beta**. The program is not open source. The public repository is for documentation, releases, and issue reports; the application source code is not distributed here.

[**Download the Windows version from Releases**](https://github.com/vizisiklo/Box-Mockup-Generator/releases)

> **Availability:** The Windows executable is published separately as a GitHub Release asset. If the Releases page has no executable yet, a downloadable build has not been attached. Do not download unverified copies from third-party sites.

## What can it do?

- Generate a dimensionally accurate rectangular box from **X × Y × Z** measurements in millimetres.
- Apply subtle rounded edges and preview the model in 3D.
- Export a six-panel, actual-size vector **PDF or SVG template** for CorelDRAW.
- Import PNG/JPG artwork exported from the vector editor; show the texture on the model and in the UV-layout preview.
- Choose a camera, lighting, shadows, background, and material finish.
- Export a **1440 × 1440 px PNG** packaging mockup, with framing assistance and a 5% safe margin.
- Optional advanced functions in this beta include OBJ/MTL export and multiple camera views.

## The five-step workflow

1. **Enter the box dimensions.** Supply width (X), height (Y), and depth (Z) in mm. The 3D preview updates automatically.
2. **Save a CorelDRAW template.** Export a scale-accurate SVG or PDF. The suggested filename includes the measurements (e.g. `Box_UV_Contour_320x240x60mm.svg`).
3. **Apply your graphic design.** Open the template in CorelDRAW at 100% size. Design on the six touching rectangles. Hide the guide strokes and export the *whole page* as a PNG, preserving its proportions. Load that image back into the app.
4. **Set up the mockup.** Adjust the camera, material, studio lights, background and shadows. Standard preview is the startup mode; studio rendering is enabled when required.
5. **Save the PNG render.** Export the result at 1440 × 1440 pixels.

### CorelDRAW and UV layout tips

The guide is an **UV texture atlas**, *not* a manufacturing dieline: it does not contain glue tabs, bleed or cutting tolerances. Do not separate, resize, or reflow its six rectangles. Portrait and landscape box layouts can differ; use the application's layout/help view to check the panel positions before exporting a texture. For best results export the whole design at high resolution and keep the original page aspect ratio.

## Requirements and installation

- Windows 10/11, 64-bit.
- Obtain **BoxMockupGenerator.exe** from the official [GitHub Releases](https://github.com/vizisiklo/Box-Mockup-Generator/releases).
- Download the executable to a local folder and run it. This beta is distributed as a portable Windows program; no CorelDRAW installation is required to run it.
- CorelDRAW or any SVG/PDF-capable graphics editor is required only for editing the print artwork.
- A few advanced rendering effects are approximate rather than physically accurate; the beta may contain defects.

## Languages

The application offers 24 official EU languages and attempts to select the Windows UI language on first launch. Some advanced labels may use English fallback.

## Freeware usage and rights

The executable is intended to be **free for personal and commercial design work**, including mockups for client presentations. The application itself is proprietary, and unauthorized redistribution, modification and derivative applications are **not permitted** under the current terms. Read [Terms of Use](TERMS_OF_USE.md) before using it. Your own artwork and exported mockup images are not transferred to the software publisher by these terms.

The fact that this GitHub repository is public **does not** make the program open source. Earlier versions that were lawfully received under GPL-3.0 remain subject to their original grants; those rights are not revoked by this new distribution policy.

## Support and feedback

Please use [GitHub Issues](https://github.com/vizisiklo/Box-Mockup-Generator/issues) to report problems. Include the Free Beta version, Windows version, box dimensions, steps to reproduce and (if possible) a screenshot. **Do not attach confidential client packaging artwork to public issues.**

See the [Hungarian user guide](README_HU.md) and [release notes](RELEASE_NOTES.md).

Copyright © 2026 vizisiklo. All rights reserved.
