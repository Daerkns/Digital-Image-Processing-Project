# Digital Image Processing — Histogram Equalization

A Digital Image Processing project that implements **grayscale histogram equalization from scratch** using Python. The project demonstrates how pixel-intensity distributions can be analyzed and transformed to improve image contrast.

## Overview

The program takes an image as input, converts it to grayscale, calculates its pixel-intensity histogram, constructs the cumulative distribution function (CDF), and uses the CDF to perform histogram equalization.

The equalized image and its resulting intensity distribution are then visualized alongside the original image.

## Processing Pipeline

1. Load an image from a user-provided filename
2. Convert the image to grayscale
3. Flatten the image into a one-dimensional array
4. Calculate the **pixel-intensity histogram manually**
5. Construct the **cumulative distribution function (CDF)**
6. Normalize the CDF according to a user-defined upper intensity bound
7. Map the original pixel values to their equalized values
8. Reshape the result back into its original image dimensions
9. Calculate and visualize the normalized histogram
10. Save and display the original and equalized images
11. Compare the original color image with the grayscale equalized result

## Key Concepts

- Grayscale image processing
- Pixel-intensity histograms
- Cumulative distribution functions (CDF)
- Histogram equalization
- Contrast enhancement
- Pixel-value transformation
- Image visualization

The histogram and CDF calculations are implemented manually rather than relying on a built-in histogram-equalization function.

## Technologies

- Python
- NumPy
- Pillow (PIL)
- Matplotlib
- Google Colab / Jupyter Notebook

## Usage

Run the notebook and provide the image filename when prompted:

```text
Enter the filename of the image: image4.jpg
Enter the upper bound for white intensity: 255
```

The input image must be uploaded to the notebook environment before execution.

The program generates:

```text
before_equalization.jpg
after_equalization.jpg
```

and displays comparisons of the original and equalized images.

## Project Structure

```text
Digital-Image-Processing/
├── DIP Project Code.ipynb
├── before_equalization.jpg
├── after_equalization.jpg
└── README.md
```

## Authors

- **Souvik Ahmed**
- **Muhesena Nasiha Syeda**
- **Sanjida Tasnim Oishi**
