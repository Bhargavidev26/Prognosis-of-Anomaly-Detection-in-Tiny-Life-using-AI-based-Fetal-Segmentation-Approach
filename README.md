# Prognosis-of-Anomaly-Detection-in-Tiny-Life-using-AI-based-Fetal-Segmentation-Approach
This project uses deep learning models like U-Net and SegNet for detecting fetal anomalies and brain tumors. It automates fetal head circumference measurement and brain tumor segmentation using ultrasound and MRI images, improving diagnostic accuracy in prenatal and neurological healthcare.

## Key Features
- **Fetal Head Circumference (HC) Segmentation:** Accurately segments and measures the fetal head circumference, a crucial biometric indicator of fetal development.
- **Deep Learning Architectures:** Implements U-Net and SegNet models, known for their exceptional performance in medical image segmentation.
- **Segmentation Accuracy:** Achieves high segmentation accuracy, helping clinicians detect potential abnormalities in fetal development.
- **Visualization:** Provides clear visualizations of both the original ultrasound image and the segmented output for better interpretation.

## Dataset
The dataset used for this project consists of a mixture of publicly available and hospital-collected fetal ultrasound images. It includes a variety of labeled ultrasound scans representing healthy and abnormal fetal growth patterns.

### Dataset Details:
- **Total Images:** 1998 images
  - 999 **Normal** fetal images
  - 999 **Annotated** images with fetal abnormalities
- **Data Split:** 
  - **Training Set:** 1598 images (80%)
  - **Validation Set:** 400 images (20%)
- **Image Format:** PNG, JPG, JPEG
- **Image Size:** Variable, resized during preprocessing for consistency.
  
## Installation Guide

### Prerequisites
Before running the project, ensure that you have the following tools and libraries installed:
- Python 3.x (recommended version: 3.7+)
- TensorFlow 2.x or higher
- Keras
- Numpy
- Matplotlib
- OpenCV
- Scikit-learn
- Other dependencies available in the `requirements.txt` file

### Installation Steps

Clone the repository:
  
   git clone https://github.com/yourusername/TinyLife-Fetal-Segmentation.git
   cd TinyLife-Fetal-Segmentation

Install Libraries
Run the code

Results:

U-Net Model:
Training Dice Score: 96.51%
Validation Dice Score: 95.29%
Training Loss: 648.65
Validation Loss: 1260.94

SegNet Model:
Training Dice Score: 91.24%
Validation Dice Score: 91.19%
Training Loss: 1754.22
Validation Loss: 1833.84

Future Directions
Expanded Datasets: Acquiring more labeled data, particularly from diverse populations and medical institutions, will improve model performance.
Improved Models: Experimenting with hybrid models or newer architectures, such as Mask R-CNN or attention-based networks, to enhance segmentation accuracy.
Real-time Integration: Building a real-time system that integrates with clinical ultrasound and MRI machines for immediate anomaly detection.

Feel free to contribute. Have a nice day.
