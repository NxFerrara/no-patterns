# No Patterns
## Purpose
This project is meant to solve custom-fit clothing generation from 3D body scans. There is documentation outlining the basic roadmap on how this problem can be solved. 
## Project Description
The present source code only covers increasing resolution of the mesh body scans (using my algorithm called MARBLE) and generating a sliced wireframe in an attempt to get the full silhoutte wireframe with landmarks (important points on the body such as the shoulder point and underarm point). The source code consists of computation and construction where computation is about supplementing the construction code with mesh metrics and mesh file conversion to enable the construction of slice wireframes (horizontal slices of the mesh body), landmark wireframes (wireframes connecting the landmark points), and high-resolution meshes (MARBLE).
## MARBLE (Mean Attributed Resolution Based on Local Estimation)
I created this algorithm to make meshes "smoother" so that walking along them becomes easier without the peaks and valleys that can occur from unclean point clouds. You can check out the results of my algorithm from the documentation. Specifically, `MARBLE_BASE` and `MARBLE_L2` show the result of applying the algorithm to the `MARBLE_BASE` mesh twice.
## Project State
This project is in progress and needs a complete update to not only organize the code but also organize the methodology since this was my work during high school with minimal project experience during the time period.
