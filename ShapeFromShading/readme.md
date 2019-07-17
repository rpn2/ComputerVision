Photometric stereo and Shape from shading

Image source: 64 images each of 4 subjects from Yale Face database http://www.cad.zju.edu.cn/home/dengcai/Data/FaceData.html


Step 1: Estimation of  albedo and surface normals for a given set of images using Photometric stereo

Step 2: Estimation of surface height map by integration uisng below techniques and comparison of results

		1) Integrating rows before columns
		2) Integarting columns before rows
		3) Average of first two options
		4) Average of multiple random paths

Code is in ipython notebook and report is in .pdf