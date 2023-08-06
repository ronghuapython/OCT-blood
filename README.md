# OCT-blood
Analysis of OCTA Images Using Python

Introduction:
This research involves the analysis of OCTA (Optical Coherence Tomography Angiography) images using Python (version 3.7.9, The Python Software Foundation, USA). The goal of this analysis is to calculate the relative blood flow in the retinal choroidal region based on pixel intensity differences in the OCTA images.

Steps of Analysis:

Pixel Matrix Extraction: Firstly, the OCTA images are processed to extract their pixel matrices. The pixel matrices represent the color information (RGB) of each pixel in the images.

Calculation of Blood Flow Pixels (M): Next, the pixel matrices are analyzed to compute the number of pixels (M) representing blood flow. This is done based on the differences in RGB values, identifying regions associated with blood flow.

Conversion to Grayscale: The images are then converted to grayscale mode to facilitate further processing.

Gaussian Denoising: A Gaussian denoising algorithm is applied to the images for noise reduction, improving the accuracy of subsequent calculations.

Calculation of Retinal Choroidal Region Pixels (N): Using the grayscale images, the number of pixels (N) within the retinal choroidal region is computed based on their grayscale differences.

Calculation of Relative Blood Flow (α): Finally, the individual relative blood flow (α) is obtained by dividing the number of blood flow pixels (M) by the number of pixels in the retinal choroidal region (N).

Python Version and Libraries:
This analysis was conducted using Python version 3.7.9, along with various Python libraries for image processing and analysis.

Important Note:
The analysis pipeline described in this readme is a summary of the methods used to calculate the relative blood flow from OCTA images. The actual implementation and code details are available in the Python script associated with this research.

Citation:
If you use this analysis pipeline or code for your research, please consider citing our paper and acknowledging the use of Python and relevant libraries.

Disclaimer:
This research readme provides an overview of the analysis approach and Python version used, but it does not cover the full details of the research methodology or results. For a comprehensive understanding of the research, please refer to the original research article associated with this readme.
