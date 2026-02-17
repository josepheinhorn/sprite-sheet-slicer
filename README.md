# 🎞️ Sprite Sheet Slicer (Day 2)

<p align="center">
  <img src="./header.gif" width="300" style="image-rendering: pixelated;" alt="Character Running">
</p>

> **The Problem:** Game engines like Unity and Godot require animations to be formatted as single sprite sheets, but many AI tools and artists export them as individual PNG frames.
> **The Solution:** A browser-native tool that stitches individual animation frames into a perfectly aligned horizontal sprite sheet in seconds.

### 🚀 Live Demo
**[→ Launch Sprite Sheet Slicer ←](https://josepheinhorn.github.io/sprite-sheet-slicer/)**

---

### ⚡ Key Features
* **Browser-Level Processing:** Uses the Canvas API to stitch images locally on your Mac. No data is ever uploaded to a server.
* **Automatic Alignment:** Detects frame dimensions and ensures every sprite is perfectly centered for your game engine.
* **Instant Export:** One-click download of the final `.png` sprite sheet.
* **Pixel-Art Preview:** Features a built-in animation loop preview, styled with the theme of our upcoming 2D side-scroller.

### 📖 How to Use
1. Open the [Live Demo](https://josepheinhorn.github.io/sprite-sheet-slicer/).
2. Select the folder containing your animation PNGs (e.g., your character's punch or kick sequence).
3. Preview the animation in the tool to ensure it looks fluid.
4. Click **"Export Sprite Sheet"** to download the final asset.
