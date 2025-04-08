# Computer_Vision_TA2

#### This project demonstrates the implementation of three popular algorithms in computer vision:

#### 1. **SIFT (Scale-Invariant Feature Transform)**
#### 2. **Harris Corner Detection**
#### 3. **Shi-Tomasi Corner Detection**

##### Algorithms Implemented

#### 1. SIFT (Scale-Invariant Feature Transform)
- Detects distinctive keypoints that are invariant to scale, rotation, and lighting.
- Widely used in image matching, object recognition, and structure-from-motion.

#### 2. Harris Corner Detection
- A traditional corner detector based on image gradients.
- Sensitive to noise and not scale-invariant, but computationally efficient.

#### 3. Shi-Tomasi Corner Detection
- An improvement over Harris, using the minimum eigenvalue instead of a corner response function.
- More stable and accurate corner detection.
  
#### Notebooks

##### Harris_Corner_Detection.ipynb: Implementation of the Harris Corner Detection algorithm.
##### Shi_Tomasi_Corner_Detection.ipynb: Implementation of the Shi-Tomasi Corner Detection algorithm.
##### SIFT.ipynb: Implementation of the Scale-Invariant Feature Transform (SIFT) algorithm.

#### Images
diamond.jpg: Example image used for corner detection.
image1.jpg, image2.jpg:image used for SIFT

#### Requirements
To run the notebooks, you need the following:

Python 3.x
Jupyter Notebook
OpenCV
NumPy

#### Usage
Clone the repository.
Open the desired notebook in Jupyter Notebook.
Run the cells to see the algorithm in action.
