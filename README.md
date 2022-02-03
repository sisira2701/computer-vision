# computer-vision
Project on detection of cracks and potholes on roads. Sample images of road have been taken from by Brazilian National Department of Transport Infrastructure (NDTI).

Assumptions: The roads can have cracks, potholes and shadows. Additionally, vehicles and people are not on the road.

This project involves:
1. Preprocessing of sample images of road (removing additional information suck as trees, grass, etc.)
2. Algorithm 1: 
--> Removal of noice
--> Contrast enhancement
--> Canny edge detection
--> Post processing using morphological operations
3. Algorithm 2:
--> Removal of noice
--> Sobel and edge detection 
--> Post processing using morphological operations
4. Each algorithm finds different types of cracks and potholes and hence both the algorithms are combined for the final result.
5. Contour is drawn around the detected cracks and potholes by using appropriate parameters.
