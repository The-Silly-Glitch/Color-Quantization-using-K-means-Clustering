# K-Means Color Quantization

This project implements **K-Means Clustering** for color quantization in images, allowing you to reduce the number of colors while preserving visual quality. The implementation is currently in **NumPy**, and a CUDA-accelerated version is in progress.

## Features
- Perform **K-Means clustering** on images to reduce colors.
- Adjustable **number of clusters (K)**.
- Supports **custom images** via GUI.
- Tracks **execution time** for performance evaluation.
- CUDA acceleration (WIP) to improve performance on large images.

## Installation

### 1. Clone the Repository
```sh
git clone https://github.com/The-Silly-Glitch/Color-Quantization-using-K-means-Clustering.git
cd Color-Quantization-using-K-means-Clustering
```

## Usage
### Run the GUI
```sh
python main.py
```
- Load an image.
- Set the number of clusters (K).
- Click **Quantize** to apply K-Means color reduction.

## Example Output
| Original Image | Quantized Image (K=10) |
|---------------|-----------------------|
| ![Original](Color-Quantization-using-K-means-Clustering\assets\Original.jpg) | ![Quantized](Color-Quantization-using-K-means-Clustering\assets\Quantized.jpg) |

## CUDA Acceleration (WIP)
- The CUDA implementation is under development using **CuPy**.
- Future improvements include **faster distance calculations** and **parallel K-Means iterations**.



