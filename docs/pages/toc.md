---
title: Course syllabus
cover-img: /aux_assets/FedTech-ComputerVision.jpg
---

## **Intro to CV and Python** [(slides)](/pages/c_01_intro_to_CV_and_Python/class_slides/)

- [Python, VSCode & packages installation guide](/pages/python_vscode_installation/python_vscode_installation/)
- Course details
- What is computer vision (CV)?
- Course outline
- Intro to Python
  - [Basic python tutorial notebook- part 1](/pages/c_01_intro_to_CV_and_Python/basic_python_tutorial_nb/)
  - [Basic python tutorial notebook- part 2](/pages/c_01_intro_to_CV_and_Python/basic_python_tutorial_part_2_nb/)
  - [NumPy tutorial notebook](/pages/c_01_intro_to_CV_and_Python/NumPy_tutorial_nb/)
  - [Matplotlib tutorial notebook](/pages/c_01_intro_to_CV_and_Python/Matplotlib_tutorial_nb/)
  - [OpenCV tutorial notebook](/pages/c_01_intro_to_CV_and_Python/OpenCV_tutorial_nb/)
- [Ex1: basic python, numpy & matplotlib, opencv](/pages/c_01_intro_to_CV_and_Python/ex1/)


## **Basic image processing** [(slides)](/pages/c_02a_basic_image_processing/class_slides/)

- Image representation
- Pixel-wise operations
- Histogram equalization [(notebook)](/pages/c_02a_basic_image_processing/histogram_equalization_nb/)
- Template matching
- Morphology operators
- Connected components
- Color space [(notebook)](/pages/c_02a_basic_image_processing/hsv_nb/)
- [Ex2: morphological operators and friends](/pages/c_02a_basic_image_processing/ex2/)


## **Filtering and resampling** [(slides)](/pages/c_02b_filtering_and_resampling/class_slides/)

- Noise and filtering [(notebook)](/pages/c_02b_filtering_and_resampling/noise_and_filtering_nb/)
- Frequency representation
- Decimation
- Interpolation 



## **Edge Detection** [(slides)](/pages/c_03_edge_detection/class_slides/)
- Intro to edges
- Basic edge image [(gradient filters notebook)](/pages/c_03_edge_detection/gradient_filters_nb/)
- Edge thinning
  - LoG
  - NMS
- Edge mask
- Canny edge detector [(edge detection notebook)](/pages/c_03_edge_detection/edge_detection_nb/)
- Other edge related topics
  - Frequency representation
  - Unsharp filter
- [Ex3: Bilateral filter](/pages/c_03_edge_detection/ex3/)

## **Curve fitting** [(slides)](/pages/c_04a_curve_fitting/class_slides/)
- Least squares
- Total least squares
- RANSAC [(LS, TLS & RANSAC notebook)](/pages/c_04a_curve_fitting/least_squares_nb/)
- [Ex4a: vignetting](/pages/c_04a_curve_fitting/ex4a/)

## **Hough transform** [(slides)](/pages/c_04b_hough_transform/class_slides/)
- Hough transform [(Hough transform notebook)](/pages/c_04b_hough_transform/hough_transform_nb/)
  - $(m,b)$ parameter space
  - $(\rho,\theta)$ parameter space
- [Ex4b: Hough circles](/pages/c_04b_hough_transform/ex4b/)



## **Image formation** [(slides)](/pages/c_05_image_formation/class_slides/)

- BRDF
- Pinhole camera
- Digital camera
- The human eye


## **Geometric transformation** [(slides)](/pages/c_06_geometric_transformation/class_slides/)

- 2D->2D transformations [(notebook)](/pages/c_06_geometric_transformation/image_transformation_nb/)
- 3D->3D transformations
- 3D->2D transformations (3D projections)
  - Perspective projection
  - Orthographic projection


## **Camera calibration** [(slides)](/pages/c_07_camera_calibration/class_slides/)

- What is camera calibration?
- Camera extrinsics
- Perspective projection
- Camera intrinsics
- Full camera matrix
- Calibration methods and distortions [(notebook)](/pages/c_07_camera_calibration/multi_plane_calib_nb/)



## **Features** [(slides)](/pages/c_08_features/class_slides/)

- What and why we need features detection?
- Feature detection
  - Blob detection
  - Harris corner detection [(Harris notebook)](/pages/c_08_features/harris_nb/)
  - SIFT detector 
- Feature description
  - Template matching
  - HOG
  - SIFT descriptor
- SIFT feature matching [(SIFT notebook)](/pages/c_08_features/sift_nb/)
- Panoramas



## **Stereo** [(slides)](/pages/c_09_stereo/class_slides/)

- Structure from motion
- Triangulation
- Stereo matching
- Camera rectification
- Epipolar geometry
     - Essential matrix
     - Fundamental matrix
     - Estimating the fundamental matrix
- Other 3D sensors





## **Neural networks basics** [(slides)](/pages/c_10_neural_networks_basics/class_slides/)

- The classification problem- again
- NN history
- Perceptron
  - Hyperplanes 
  - Activation
- Dense layer
- Multi-layer perceptron (MLP)
- Optimization
  - Softmax + cross entropy + loss
  - Gradient descent
- Basic data preprocessing
  - Data normalization
  - Train, validation and test splits
- [Fully connected net](/pages/c_10_neural_networks_basics/fully_connected_nb/)


## **Neural networks 2** [(slides)](/pages/c_11_neural_networks_2/class_slides/)

- [ConvNets](/pages/c_11_neural_networks_2/conv_nn_nb/)
  - Convolution layer
  - Pooling layer
- Overfitting
- Architectures
  - Alexnet (dropout)
  - VGG
  - ResNet (batch norm)

