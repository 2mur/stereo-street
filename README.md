# Google StreetView Stereo Reconstruction Project

1. **Data Source:** Images for this process are collected using the Google StreetView API, particularly from panoramic viewpoints along a street.

2. **Image Pre-processing:** Initial image processing methods; histogram matching and rectification

3. **Depth Map Estimation:** The primary goal is to estimate depth maps (disparity) for a set of 2D images. This is achieved by matching pixels between pairs of images, using graph cut methods.

4. **Optimization Method:** The α-β swap and α expansion algorithms.
