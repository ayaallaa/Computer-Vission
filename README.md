

### Computer Vision Functions

1. Add additive noise to the image.
    *  Uniform, Gaussian and salt & pepper noise.
2. Filter the noisy image using the following low pass filters.
    * Average, Gaussian and median filters.
3. Detect edges in the image using the following masks
    * Sobel, Roberts , Prewitt and canny edge detectors.
4. Draw histogram and distribution curve.
5. Equalize the image.
6. Normalize the image.
7. Local and global thresholding.
8. Transformation from color image to gray scale image and plot of R, G, and B histograms with its distribution function (cumulative curve that you use it for mapping and histogram equalization).
9. Frequency domain filters (high pass and low pass).
10. Hybrid images.
11. Detect edges using Canny edge detector, detect lines and circles located in these images (if any). Superimpose the detected shapes on the images.
12. Detect corners using Harris operator and experiment with different techniques to extract the real corners (e.g experiment with thresholding, local thresholding, non-maxima supression, local maxima extraction).
13. Initialize the contour for a given object and evolve the Active Contour Model (snake) using the greedy algorithm. Represent the output as chain code and compute the perimeter and the area inside these contours
14. Match the image set features using:
    1. Correlation
    2. Zero-mean correlation
    3. Sum of squared differences (SSD)
    4. and normalized cross correlations. Then **report matching computation time in the GUI**.
15. Generate feature descriptors using scale invariant features (SIFT). **Report computation time in the GUI**
