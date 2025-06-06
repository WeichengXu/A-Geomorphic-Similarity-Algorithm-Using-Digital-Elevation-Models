# TIFF Similarity Analysis Tool

This Python project analyzes grayscale TIFF images using a block-wise similarity approach. It uses a custom Wave Hedges similarity metric to evaluate visual similarity between blocks in an image. The result is a heatmap-style overlay indicating regions of similarity, saved as a new TIFF image.

## 🔧 Features

- 🔲 Crop TIFF images to specific regions.
- 🧮 Analyze cell neighborhood relationships.
- 📊 Count squared-sum values of neighboring cells.
- 🧬 Compare blocks using Wave Hedges similarity index.
- 🖼️ Overlay similarity map on original image.
- 📉 Downscale TIFF images for efficiency.

## 📦 Requirements

Install dependencies using pip:

```bash
pip install pillow numpy matplotlib rasterio
