
Part 1: Create Hybrid images, Hybrid images are static images with two interpretations, which changes as a function of the viewing distance. 


Part 2: Scale-space blob detection

Algorithm outline

a) Generate a Laplacian of Gaussian filter.
b) Build a Laplacian scale space, starting with some initial scale and going for n iterations:
	1)Filter image with scale-normalized Laplacian at current scale.
	2)Save square of Laplacian response for current level of scale space.
	3)Increase scale by a factor k.
c)Perform non-maximum suppression in scale space.
d)Display resulting circles at their characteristic scales

Codes are in respective ipython notebook

Ipython outputs are captured in *_output.pdf

Report and analysis of results in *report.pdf