# Feature Extraction and Object Recognition

Classical computer vision feature extraction: edges, corners, and scale/rotation-invariant keypoints, built from scratch and compared against reference implementations.

- [Notebook](Feature_Extraction_and_Object_Recognition.ipynb)
- [Paper](<Feature Extraction and Object Recognition.pdf>)
- Datasets: [Data set 1](<Image Data/data set 1>), [Data set 2](<Image Data/data set 2>)

## Approach

**Part 1: Edges and corners**
- Detected edges with Sobel and Canny, and improved edge definition by Gaussian-blurring the image first to reduce noise before detection
- Implemented a Harris corner detector from scratch and compared its output against a reference implementation
- Tested the custom Harris detector for scale and rotation invariance on a generated set of resized and rotated versions of the same image

**Part 2: Keypoint matching**
- Ran the SIFT algorithm to detect scale/rotation-invariant interest points on a custom image dataset
