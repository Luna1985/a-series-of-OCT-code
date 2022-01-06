 Automated retinal layer segmentation algorithm based on improved Canny operator


This method adds a multi-point boundary search step on the basis of the traditional Canny operator and adjusts the convolution kernel function. First, Image enhancement, this section includes image denoising, gradient calculation and non-maximum suppression, which are similar to but slightly different from the first three steps of Canny operator. Second, boundary search, multiple gradient peak points are selected as seed points to search the retinal boundaries and superimpose the obtained boundaries together. The third, Boundary selection, the number of superposed boundaries is converted into probabilities, and the double threshold method in Canny operator is used to select and connect the edges. This method can accurately distinguish eleven retinal boundaries without additional intervention such as A-lines alignment, manual initialization, parameter adjustment or search space restriction. 

The data is in another branch
