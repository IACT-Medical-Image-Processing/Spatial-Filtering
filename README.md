# Spatial-Filtering
Spatial Filtering including using Gaussian Blur and Laplacian

Output1 directory has the following settings: sigma = 1, window size = 3x3, c (laplacian constant) = 0.1

Output2 directory has the following settings: sigma = 1, window size = 3x3, c (laplacian constant) = 1

We can see that when c is higher it introduces more noise to the image since the noise are being sharpened. One way to reduce this is to first pass it through a Gaussian filter to smooth the image, thus reducing the noise, before sharpening it.
