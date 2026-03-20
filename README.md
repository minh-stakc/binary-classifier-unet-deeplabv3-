# Binary Landslide Classifier (UNet + DeepLabV3)

Detects landslide-affected regions in satellite imagery using binary semantic segmentation.

## Model

Ensemble of UNet and DeepLabV3+ architectures for pixel-wise binary classification — **landslide** vs. **non-landslide** — trained on labeled satellite imagery.

## Setup

```bash
pip install -r requirements.txt
```

## Stack

Python, PyTorch, NumPy, rasterio
