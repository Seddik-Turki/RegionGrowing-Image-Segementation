# Image Segmentations: Region Growing
This repository demonstrates Region Growing to segment an image.

## Project Description
Region growing is a simple region-based image segmentation method.
It is also classified as a pixel-based image segmentation method since it involves the selection of initial seed points.

This approach to segmentation examines neighboring pixels of initial seed points and determines whether the pixel neighbors 
should be added to the region. The process is iterated on, in the same manner as general data clustering algorithms.
![Source](https://en.wikipedia.org/wiki/Region_growing)

This method is detailed in the Jupyter notebook `RegionGrowing.ipynb`
 

### Example Output
![region](/images/RegionGrowing.png)
