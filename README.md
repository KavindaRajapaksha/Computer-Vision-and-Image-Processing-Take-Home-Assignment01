# Image Processing Assignment

This repository provides a Jupyter notebook that demonstrates fundamental image processing operations using OpenCV and Python. The notebook is part of the EC7212 – Computer Vision and Image Processing course assignment.

## Features

The notebook covers the following image processing operations:

- **Loading and Displaying Images:** Load images using OpenCV and display them with Matplotlib.
- **Reducing Intensity Levels:** Decrease the number of intensity levels in an image (128, 64, 16, 8, 2).
- **Spatial Averaging:** Apply various neighborhood sizes for blurring (3×3, 10×10, 20×20).
- **Image Rotation:** Rotate images by specific angles (45° and 90°).
- **Block Averaging:** Reduce spatial resolution using block averaging (3×3, 5×5, 7×7).

## Usage

1. Place the input image in the `InputImages` directory.
2. Open the Jupyter notebook: `Image_Processing_Take_home01.ipynb`.
3. Run the cells sequentially to view the results of each image processing technique.
4. Visualizations will display the original image alongside the processed versions for comparison.

## Implementation Details

Each operation is modularized as a separate function:

- `reduce_intensity_levels()`: Reduces color/intensity information.
- `spatial_average()`: Blurs the image using averaging kernels.
- `rotate_image()`: Rotates the image with proper boundary handling.
- `block_average()`: Averages pixel blocks to reduce resolution.

## Results

The notebook presents the results of each operation using Matplotlib subplots, making it easy to compare the original and processed images side by side.
