## EN3160 Assignment 1 - Intensity Transformations and Neighborhood Filtering

This repository contains the implementation and results for Assignment 1 of **EN3160 - Image Processing and Machine Vision**.

### Assignment Topics

1. **Intensity Transformations**
   - Piecewise-linear intensity transformation
   - Experimentation with different breakpoints
   - Visualization of transformation functions and results

2. **Brain Image Intensity Enhancement**
   - Enhancement of white matter
   - Enhancement of gray matter
   - Piecewise intensity transformations

3. **Gamma Correction**
   - Conversion to the CIE L\*a\*b\* color space
   - Gamma correction of the L\* plane
   - Histogram comparison before and after correction

4. **Vibrance Enhancement**
   - HSV color-space decomposition
   - Saturation-plane intensity transformation
   - Parameter tuning for visually pleasing results
   - Reconstruction of the enhanced image

5. **Histogram Equalization**
   - Custom histogram equalization implementation
   - Histogram comparison before and after equalization

6. **Foreground Histogram Equalization**
   - HSV-plane analysis
   - Foreground extraction using thresholding
   - Histogram equalization of the foreground only
   - Background and foreground recombination

7. **Sobel Filtering**
   - Sobel filtering using OpenCV's `filter2D`
   - Custom Sobel filter implementation
   - Separable Sobel filtering using 1D kernels

8. **Image Zooming and Interpolation**
   - Nearest-neighbor interpolation
   - Bilinear interpolation
   - Image scaling by a given factor
   - Quantitative comparison using normalized SSD

9. **Foreground Segmentation and Background Blur**
   - GrabCut-based foreground segmentation
   - Foreground/background extraction
   - Background blurring
   - Analysis of edge effects in the enhanced image

10. **Bilateral Filtering**
    - OpenCV bilateral filtering
    - Custom bilateral filter implementation
    - Comparison with Gaussian filtering
    - Quantitative comparison between custom and OpenCV implementations
