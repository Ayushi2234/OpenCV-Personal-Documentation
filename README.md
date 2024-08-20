# OpenCV Personal Documentation

Welcome to my personal documentation for OpenCV! This repository is a collection of my notes, tutorials, and projects related to OpenCV, a powerful open-source library for computer vision and image processing. This documentation aims to help me (and others) understand and utilize OpenCV effectively.

## 📋 Table of Contents

- [Introduction](#introduction)
- [OpenCV Tutorials](#opencv-tutorials)
- [NumPy Tutorials](#numpy-tutorials)
- [Core OpenCV Modules](#core-opencv-modules)
- [OpenCV.js Tutorials](#opencvjs-tutorials)
- [Tutorials for Contrib Modules](#tutorials-for-contrib-modules)
- [Projects and Examples](#projects-and-examples)
- [Community and Contributions](#community-and-contributions)
- [Contact](#contact)
- [Numpy](https://github.com/shyama7004/OpenCV-Personal-Documentation/tree/main/Numpy)

## 📖 Introduction

Welcome to my OpenCV documentation repository! Here you'll find a comprehensive collection of tutorials, projects, and notes aimed at mastering OpenCV for computer vision and image processing.

## 🖥️ OpenCV Tutorials

### Core Learning (Month 1)
1. **Introduction to OpenCV**
   - [Overview of OpenCV](https://opencv.org/about/)
   - [Installation and Setup](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Quick%20Start.md)
   - [Basic Structures (Mat, Scalar, Point, etc.)](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Basic%20Structures.md)
   - [Convolution](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Convolution.md)
   - **Revision Tips**: Practice by writing small programs to load, display, and manipulate images.

2. **Core Operations**
   <!-- [Basic Operations on Images](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Basic%20Operations%20on%20Images.md)
   - [Pixel Manipulation](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Changing%20Colorspaces.md)
   - [Arithmetic Operations](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Arithmetic%20Operations.md)
   - [Logic Operations](https://docs.opencv.org/5.x/d0/d86/tutorial_py_image_arithmetics.html#image-blending-using-pyramids)
   - [Geometric Transformations](https://docs.opencv.org/5.x/da/d6e/tutorial_py_geometric_transformations.html)-->
 
  - **Basic Operations on Images**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Basic%20Operations%20on%20Images.md)   |   [OpenCV Docs](https://docs.opencv.org/5.x/d3/df2/tutorial_py_basic_ops.html)
  - **Pixel Manipulation**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Changing%20Colorspaces.md)   |   [OpenCV Docs](https://docs.opencv.org/5.x/df/d9d/tutorial_py_colorspaces.html)
  - **Arithmetic Operations**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Arithmetic%20Operations.md)   |   [OpenCV Docs](https://docs.opencv.org/5.x/d0/d86/tutorial_py_image_arithmetics.html)
  - **Image Pyramids**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Image%20Blending%20using%20Pyramids.md) |   [OpenCV Docs](https://docs.opencv.org/5.x/dc/dff/tutorial_py_pyramids.html#autotoc_md1437)
  - **Geometric Transformations**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Geometric%20Transformations%20of%20Images.md)   |   [OpenCv Docs](https://docs.opencv.org/5.x/da/d6e/tutorial_py_geometric_transformations.html)

  - **Revision Tips**: Implement small projects like image filters, blending, and basic transformations.

### Advanced Topics and Projects (Month 2)
3. **Image Processing**
   - **Smoothing and Blurring**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Smoothing%20and%20Blurring.md)   |   [OpenCV](https://docs.opencv.org/5.x/d4/d13/tutorial_py_filtering.html)
   - **Image Thresholding**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Image%20Thresholding.md) |   [OpenCV Docs](https://docs.opencv.org/5.x/d7/d4d/tutorial_py_thresholding.html)
   - **Morphological Operations**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Morphological%20Transformations.md)   |   [OpenCV Docs](https://docs.opencv.org/5.x/d9/d61/tutorial_py_morphological_ops.html)
   - **Canny Edge Detection**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Canny%20Edge%20Detection.md)   |   [OpenCV Docs](https://docs.opencv.org/5.x/da/d22/tutorial_py_canny.html)
   - **Image Gradients** : [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Image%20Gradients.md)   |   [OpenCv](https://docs.opencv.org/4.x/d5/d0f/tutorial_py_gradients.html)
   - **Advanced Image Processing Techniques**:

#### Restoration
1. **Wiener Filtering**:
   - [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Wiener%20Filtering.md)   |   [SciPy Docs](https://scipy-cookbook.readthedocs.io/items/SignalSmooth.html)

2. **Richardson-Lucy Deconvolution**:
   - [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Richardson-Lucy%20Deconvolution.md)   |   [Scikit Docs](https://scikit-image.org/docs/stable/auto_examples/filters/plot_deconvolution.html)

3. **Total Variation Denoising**:
   - [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Denoising%20a%20Picture.md)   |   [Scikit Docs](https://scikit-image.org/docs/stable/auto_examples/filters/plot_denoise.html)

#### Denoising
1. **Gaussian Blurring**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Smoothing%20Images.md)   |   [OpenCV Docs](https://docs.opencv.org/5.x/dc/dd3/tutorial_gausian_median_blur_bilateral_filter.html)
2. **Bilateral Filtering**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Bilateral%20Filtering.md)   |   [OpenCV Docs](https://homepages.inf.ed.ac.uk/rbf/CVonline/LOCAL_COPIES/MANDUCHI1/Bilateral_Filtering.html)
3. **Non-Local Means Denoising**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Image%20Denoising.md)   |   [OpenCV Docs](https://docs.opencv.org/5.x/d5/d69/tutorial_py_non_local_means.html)

#### Segmentation
1. **Watershed Algorithm** :[My docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Image%20Segmentation%20with%20Watershed%20Algorithm.md)   |   [OpenCV Docs](https://docs.opencv.org/5.x/d3/db4/tutorial_py_watershed.html)
2. [Graph-Based Segmentation (PyTorch Geometric)](https://pytorch-geometric.readthedocs.io/en/latest/notes/segmentation.html)
   - **Revision Tips**: Create an image processing pipeline that includes smoothing, thresholding, edge detection, and advanced techniques.

4. **Feature Detection and Description**
   - **Feature Detection and Description** :[My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Feature%20Detection%20and%20Description.md)	|	[OpenCv Docs](https://docs.opencv.org/5.x/dc/dc3/tutorial_py_matcher.html)
   - [Feature Matching](https://docs.opencv.org/5.x/dc/dc3/tutorial_py_matcher.html)
   - [Cascade Classifiers](https://docs.opencv.org/5.x/d7/d8b/tutorial_py_face_detection.html)
   - **Revision Tips**: Develop a simple application for detecting and matching features in images.

5. **Video Analysis**
   - [Video Capture](https://docs.opencv.org/5.x/dd/d43/tutorial_py_video_display.html)
   - [Background Subtraction](https://docs.opencv.org/5.x/d1/dc5/tutorial_background_subtraction.html)
   - [Motion Detection](https://docs.opencv.org/5.x/df/d9d/tutorial_py_colorspaces.html)
   - [Object Tracking](https://docs.opencv.org/5.x/d7/d00/tutorial_meanshift.html)
   - [Optical Flow](https://aiida.readthedocs.io/projects/aiida-core/en/latest/topics/cli.html)
- [Motion Analysis and Object Tracking](https://docs.opencv.org/5.x/d7/df3/group__imgproc__motion.html)

   - **Revision Tips**: Create a program that captures video and implements background subtraction and object tracking.

### Specialization and Contributions (Month 3)
6. **Core Computer Vision Concepts**
   - [Camera Calibration with OpenCV](https://docs.opencv.org/5.x/dc/dbb/tutorial_py_calibration.html)
   - [Depth Map from Stereo Images](https://docs.opencv.org/5.x/dd/d53/tutorial_py_depthmap.html)
   - [3D Reconstruction from Stereo Images](https://docs.opencv.org/5.x/da/de9/tutorial_py_epipolar_geometry.html)

7. **Machine Learning with OpenCV**
   - [KNN](https://docs.opencv.org/5.x/d5/d26/tutorial_py_knn_understanding.html)
   - [SVM](https://docs.opencv.org/5.x/d1/d73/tutorial_introduction_to_svm.html)
   - [Decision Trees](https://docs.opencv.org/5.x/d3/dc0/group__ml.html)
   - [K-means Clustering](https://docs.opencv.org/5.x/d1/d5c/tutorial_py_kmeans_opencv.html)
   - **Hyperparameter Tuning**: [Hyperparameter Tuning Techniques](https://machinelearningmastery.com/hyperparameter-optimization-with-random-search-and-grid-search/)
   - **Model Evaluation**: [Metrics and Methods for Model Evaluation](https://scikit-learn.org/stable/modules/model_evaluation.html)
   - **Deployment**: [Strategies for Deploying Machine Learning Models](https://www.tensorflow.org/tfx/guide/serving)
   - **Revision Tips**: Implement machine learning models to classify images or perform clustering.

8. **Deep Learning with OpenCV**
   - [Deep Learning with OpenCV](https://docs.opencv.org/5.x/d5/de7/tutorial_dnn_googlenet.html)
   - [Training Models](https://docs.opencv.org/5.x/d2/dc0/tutorial_introduction_to_traincascade.html)
   - [Image Classification](https://docs.opencv.org/5.x/d5/de7/tutorial_dnn_googlenet.html)
   - [YOLO, SSD](https://docs.opencv.org/5.x/d5/de7/tutorial_dnn_googlenet.html)
   - [Semantic Segmentation](https://docs.opencv.org/5.x/da/d60/tutorial_bounding_boxes.html)
   - **Revision Tips**: Develop applications that use pre-trained models for image classification and object detection.

### Additional Focus Areas (Throughout the Preparation)
9. **OpenCV Contrib Modules**
   - [Extended Image Processing (ximgproc)](https://docs.opencv.org/5.x/df/d2d/group__ximgproc.html)

	1.	**Edge Detection** [Structured forests, EdgeBoxes](https://docs.opencv.org/5.x/de/d51/group__ximgproc__edge.html)
	2.	**Filters** [e.g., Guided Filter, Bilateral Filter](https://docs.opencv.org/5.x/da/d17/group__ximgproc__filters.html)
	3.	**Superpixels** [e.g., SLIC](https://docs.opencv.org/5.x/df/d6c/group__ximgproc__superpixel.html)
	4.	**Image Segmentation** :[Image Segmentation](https://docs.opencv.org/5.x/d5/df0/group__ximgproc__segmentation.html)
	5.	**Fast Line Detector** :[Fast Line Detector](https://docs.opencv.org/5.x/df/ded/group__ximgproc__fast__line__detector.html)

   - [Advanced Calibration Techniques and 3D Data Handling (calib3d)](https://docs.opencv.org/4.x/d9/d0c/group__calib3d.html)
   - [2D Features Framework (features2d)](https://docs.opencv.org/5.x/d7/dff/tutorial_feature_homography.html)

10. **Computational Photography**
   - [HDR Imaging with OpenCV](https://docs.opencv.org/5.x/d3/db7/tutorial_hdr_imaging.html)
   - [Image Stitching with OpenCV](https://docs.opencv.org/5.x/d8/d19/tutorial_stitcher.html)
   - [Photogrammetry Techniques](https://www.opencv-srf.com/2018/01/introduction-to-photogrammetry.html)
   - **Additional Advanced Techniques**:
      - **Image Inpainting**: [Image Inpainting (OpenCV)](https://docs.opencv.org/5.x/df/d3d/tutorial_py_inpainting.html)
      - **Light Field Imaging**: [Light Field Imaging](https://www.openlightfield.org/)


## 📦 Core OpenCV Modules

### 11. Features Detection and Description

1. **Understanding Features**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Understanding%20Features.md)	|	[OpenCV Docs](https://docs.opencv.org/4.x/db/d27/tutorial_py_table_of_contents_feature2d.html)
2. **Harris Corner Detection**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/Harris%20Corner%20Detection.md)	|	[OpenCv Docs](https://docs.opencv.org/4.x/dc/d0d/tutorial_py_features_harris.html)
3. **SIFT (Scale-Invariant Feature Transform)**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/SIFT.md)	|	[OpenCV Docs](https://docs.opencv.org/4.x/da/df5/tutorial_py_sift_intro.html)
4. **SURF (Speeded-Up Robust Features)**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/SURF.md)	|	[OpenCV Docs](https://docs.opencv.org/4.x/df/dd2/tutorial_py_surf_intro.html)
5. **FAST (Features from Accelerated Segment Test)**: [My Docs](https://github.com/shyama7004/OpenCV-Personal-Documentation/blob/main/Main-Concepts/FAST%20Algorithm%20for%20Corner%20Detection.md)	|	[OpenCV Docs](https://docs.opencv.org/4.x/df/d0c/tutorial_py_fast.html)
6. **BRIEF (Binary Robust Independent Elementary Features)**: [BRIEF](https://docs.opencv.org/4.x/dc/d7d/tutorial_py_brief.html)
7. **ORB (Oriented FAST and Rotated BRIEF)**: [ORB](https://docs.opencv.org/4.x/d1/d89/tutorial_py_orb.html) 


## 🔄 Tutorials for Contrib Modules

- **xfeatures2d**: [Link](https://docs.opencv.org/5.x/d5/d39/group__xfeatures2d.html)
- **Tracking**: [Link](https://docs.opencv.org/5.x/d9/df8/group__tracking.html)
- **Text**: [Link](https://docs.opencv.org/5.x/d7/d1f/group__text.html)
- **Surface Matching**: [Link](https://docs.opencv.org/5.x/d5/d1d/group__surface__matching.html)
- **Structured Light**: [Link](https://docs.opencv.org/5.x/d9/d25/group__structured__light.html)
- **SFM (Structure from Motion)**: [Link](https://docs.opencv.org/5.x/d2/d3a/group__sfm.html)
- **Fuzzy Logic**: [Link](https://docs.opencv.org/5.x/d8/d58/group__fuzzy.html)
- **Text Detection**: [Link](https://docs.opencv.org/5.x/d0/d0a/group__text__detect.html)

# ⛓️ Additional Resources

- **OpenCV Official Documentation**: [OpenCV Official Documentation](https://docs.opencv.org/5.x/)
- **OpenCV Forum**: [Forum](https://forum.opencv.org/)
- **OpenCV GitHub Repository**: [Repo](https://github.com/opencv/opencv)
- **OpenCV Python Tutorials**: [Tutorials](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_tutorials.html)
- **OpenCV YouTube Channel**: [Link](https://www.youtube.com/channel/UC6uUvV3n-bEsg5k8J0Fqvhg)

# 🧑‍🏫 Contributors and Community

- **OpenCV Team**: The dedicated team behind OpenCV.
- **Community Contributions**: Contributions from developers and researchers around the world.
- **Your Contributions**: Feel free to contribute by adding tutorials, examples, or improving the documentation.


## 🚀 Start Your OpenCV Journey Now!

Visit the [OpenCV GitHub Repository](https://github.com/opencv/opencv) to get started. Join the [OpenCV Forum](https://forum.opencv.org/) to discuss and share your projects, and don't forget to check out the latest updates on the # OpenCV Personal Documentation
