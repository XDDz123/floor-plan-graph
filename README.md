# Floor Plan Graph Converter
This project can convert images of floor plans to graphs that retain room adjacency/connectivity information. </br>
Created to help out some UCL Bartlett students. </br>

# Libraries
* numpy
* cv2
* skimage
* matplotlib
* scipy.ndimage

# Implementation Outline
1. The program performs edge detection to obtain a contour of each room within the layout. </br>
2. The edges of each room contour is checked for overlap. Overlapping edges indicate adjacency/connectivity. </br>
3. Each room is connected based on their adjacency/connectivity, thus producing the graph.

# Sample Output
(Left: Output, Right: Input) </br></br>
![image](https://github.com/XDDz123/floor-plan-graph/assets/20507222/48803385-de8c-4d44-a5dc-3fbf440ea538)
