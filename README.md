**🖼️ Digital Image Processing – Lab Tasks**








This repository contains Digital Image Processing (DIP) lab tasks implemented in Python using OpenCV, NumPy, Matplotlib, Scikit-learn, and Scikit-image.
Each task demonstrates a core concept of image processing with clear visual results.

📁 Repository Structure
├── Task01/
├── Task02/
├── Task03_04/
├── Task05/
├── Task08/
├── Task09/
├── Task10/
├── Task11/
├── Task12/
├── README.md


Note: Task 03 & Task 04 are combined into a single implementation as required.

🔹 **Task 01 – RGB Components, Grayscale & Binary Image**
📌 Description

Basic image preprocessing and color channel analysis.

✅ Key Operations

Load color image

Convert BGR → RGB

Extract R, G, B channels

Convert to grayscale

Apply binary thresholding

Visualize results using subplots

🎯 Learning Outcome

Understanding image color representation and basic preprocessing.

🔹**** Task 02 ****– Connected Component Labeling****
📌 Description

Object detection using region-based segmentation.

✅ Key Operations

RGB component analysis

Grayscale & binary conversion

Connected component labeling

Object counting

Random color labeling for visualization

🎯 Learning Outcome

Understanding object detection and region labeling.

🔹** Task 03 & Task 04 – Image Enhancement Techniques**
📌 Description

Contrast enhancement using intensity transformation methods.

✅ Key Operations

Grayscale conversion

Histogram Equalization:

Built-in (OpenCV)

Manual (CDF-based)

Contrast Stretching

Log Transformation

Gamma Correction

Visual comparison

🎯 Learning Outcome

Improving image quality using enhancement techniques.

🔹** Task 05 – Spatial Filtering & Convolution**
📌 Description

Noise removal and image sharpening using spatial filters.

✅ Key Operations

Mean, Median, Gaussian filtering

Laplacian sharpening

Custom 3×3 convolution kernel

Salt & Pepper noise handling

Gaussian noise handling

Filter comparison

🎯 Learning Outcome

Choosing appropriate filters for different noise types.

🔹** Task 08 – Motion Blur Restoration**
📌 Description

Restoration of motion-blurred images using multiple approaches.

✅ Key Operations

Unsharp masking

Simple deconvolution

Bilateral filtering + sharpening

Adaptive sharpening

Frequency domain enhancement

Sharpness evaluation (Laplacian variance)

Before vs After comparison

🎯 Learning Outcome

Practical motion blur restoration techniques.

**🔹 Task 09 – Color Models & Color-Based Segmentation**
📌 Description

Analysis of different color spaces for segmentation.

✅ Key Operations

RGB channel extraction

Conversion to HSV, YCbCr, Lab

White balance correction (Gray World)

HSV color masking

Segmentation comparison across color spaces

🎯 Learning Outcome

Understanding the importance of color spaces in segmentation.

**🔹 Task 10 – Image Compression Techniques**
📌 Description

Lossless and lossy image compression analysis.

✅ Key Operations

Huffman Coding (lossless)

JPEG-like compression using:

DCT

Quantization

Inverse DCT

Performance metrics:

MSE

PSNR

Compression Ratio

Rate Distortion

🎯 Learning Outcome

Understanding compression trade-offs between quality and size.

**🔹 Task 11 – Morphological Operations**
📌 Description

Binary image analysis using morphology.

✅ Key Operations

Erosion

Dilation

Opening

Closing

Boundary extraction

Hole filling

Noise removal

Shape detection

🎯 Learning Outcome

Understanding shape-based image processing.

**🔹** Task 12 – Image Segmentation Techniques****
📌 Description

Comparison of classical and clustering-based segmentation methods.

✅ Key Operations

Global thresholding

Local thresholding

Adaptive thresholding

K-Means segmentation (k = 2, 3, 4)

Mean Shift segmentation

Visual comparison of results

🎯 Learning Outcome

Understanding segmentation strategies under different conditions.

🛠️ Technologies Used

Python 3

OpenCV

NumPy

Matplotlib

Scikit-learn

Scikit-image

Google Colab / Jupyter Notebook

🚀 How to Run
pip install opencv-python numpy matplotlib scikit-learn scikit-image


Upload images in the working directory or Google Colab

Run task notebooks/scripts sequentially

📌 Conclusion

This repository provides a complete hands-on implementation of Digital Image Processing concepts, covering:

Enhancement

Filtering

Restoration

Segmentation

Compression

Morphological processing
