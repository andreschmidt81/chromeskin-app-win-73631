# Metal Effect v - Image Editing Tool 2026

> **Metal Effect is a client-side browser tool for applying chrome and gold finishes to images with canvas-based masking and adjustable visual controls.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Unreleased-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/andreschmidt81/chromeskin-app-win-73631?style=flat-square)](https://github.com/andreschmidt81/chromeskin-app-win-73631)

---

<p align="center">
  <a href="https://andreschmidt81.github.io/chromeskin-app-win-73631/">
    <img src="https://img.shields.io/badge/Download-Metal%20Effect%20Latest-brightgreen?style=for-the-badge" alt="Download Metal Effect">
  </a>
</p>

> **[Direct Download - Metal Effect](https://andreschmidt81.github.io/chromeskin-app-win-73631/)**

---

[Download Latest Build](https://andreschmidt81.github.io/chromeskin-app-win-73631/)

---

## About Metal Effect

Metal Effect is a browser-based image editing tool for giving selected areas a chrome or gold appearance. It uses canvas processing and polygon masks so you can define exactly which parts of an image receive the metallic treatment.

The editor is designed for focused, local image work without sending images to an upload service. Visual parameters such as sheen, contrast, brightness, tint, opacity, feathering, and blending can be refined interactively before exporting the finished image as a PNG.

---

## Features

- Apply chrome and gold metallic effects to images
- Create polygon masks with target and protect modes
- Tune opacity, sheen, contrast, brightness, and tint
- Feather mask edges for smoother transitions
- Blend the effect into the source image
- Undo edits or reset the current image
- Export and import masks as JSON files
- Download completed edits as PNG
- Process images locally in the browser without uploads

---

## Installation

### Use the hosted build

Open the [latest build](https://andreschmidt81.github.io/chromeskin-app-win-73631/) in a modern web browser.

### Run from a local checkout

```bash
git clone https://github.com/andreschmidt81/chromeskin-app-win-73631.git
cd REPO
```

Open the project's main HTML file in your browser, or serve the directory with any simple local web server if your browser requires one for local assets.

---

## Usage

1. Open Metal Effect and load an image into the editor.
2. Choose a chrome or gold effect.
3. Draw a polygon mask around the area to edit.
4. Select target mode to apply the effect inside the mask, or protect mode to preserve the selected area.
5. Adjust opacity, sheen, contrast, brightness, tint, feathering, and blending.
6. Use undo or reset when you need to revise the edit.
7. Export the mask as JSON if you want to reuse it later.
8. Download the finished image as a PNG.

---

## Configuration

Metal Effect is configured through its in-browser editing controls rather than a separate configuration file. Effect settings are adjusted directly in the interface, while reusable mask data can be saved and restored as JSON.

For local development, keep the project files together and launch the main HTML entry point through a browser or local web server.

---

## Requirements

- A modern web browser with canvas support
- JavaScript enabled
- Local browser access to the project files or the hosted build
- Sufficient browser memory for the image dimensions being edited
- No server-side image upload is required for the editing workflow

---

## FAQ

### Which browsers can run Metal Effect?

Use a modern browser with JavaScript and HTML canvas support. Chrome is suitable for the browser-based workflow.

### Can I apply both chrome and gold effects?

Yes. The editor provides chrome and gold metallic treatments that can be refined with the available adjustment controls.

### How do I control where the effect appears?

Draw a polygon mask and choose either target or protect mode. Edge feathering can help create a less abrupt transition around the mask.

### Can I reuse a mask?

Yes. Export the current mask as a JSON file, then import that file when you need to restore the mask data.

### How do I save the edited image?

Use the PNG download action after completing the adjustments.

### What should I do if the image does not process correctly?

Confirm that JavaScript is enabled, reload the page, and try resetting the image. For large images, reducing the image dimensions may also help browser processing.

### How are updates delivered?

Updates are made available through the hosted build and the project repository. Check the latest published version before starting a new editing session.

### Where should configuration changes be made?

Normal visual changes are made through the editor controls. Reusable mask information is handled through JSON export and import rather than a separate settings file.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
