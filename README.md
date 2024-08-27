# BRAIN-TUMOR-SEGMENTATION |  Image Processing, Machine Learning, MATLAB

Introduction:-

A tumor is an abnormal growth caused by uncontrolled cell division, with brain tumors being particularly dangerous. Brain tumors are classified into four grades, and their treatment depends on the tumor's type, grade, and location. Early detection is critical as these tumors can be fatal. MRI is commonly used for diagnosis, but manual segmentation is impractical due to the large data volume. We propose an automatic segmentation method using Convolutional Neural Networks (CNN) with small 3×3 kernels, enabling a deeper architecture and reducing overfitting. Data augmentation further enhances the accuracy of brain tumor segmentation in MRI images.

Prposed System:- 

In this project, MRI images are used to detect brain tumors using a D-planning technique involving preprocessing, segmentation, and classification. Preprocessing enhances images by adjusting brightness, contrast, and removing noise. Segmentation methods like K-means, ACM, and Watershed are applied to highlight affected areas. The image is then filtered using a median filter and segmented using Otsu’s thresholding. Features are extracted using Haar wavelet transform (HWT) and Histogram of Oriented Gradients (HOG). Finally, a CNN classifies the extracted features against a trained dataset to determine if a tumor is present.

The software used is MATLAB

Block Diagram:-

![Screenshot 2024-08-27 124530](https://github.com/user-attachments/assets/c3cb9671-8bbd-4c3a-92e0-499e9e9dc9bd)

MRI Images:-

![Screenshot 2024-08-27 124617](https://github.com/user-attachments/assets/5d048232-be26-4377-bedb-31e53a16bd11)

Results:-

![Screenshot 2024-08-27 124721](https://github.com/user-attachments/assets/988cd895-34e6-49f1-8324-a4c045d8e4f6)

![Screenshot 2024-08-27 124818](https://github.com/user-attachments/assets/9033a6aa-7b1a-4536-bf6f-7efac7ff32d9)

![Screenshot 2024-08-27 124835](https://github.com/user-attachments/assets/59cae25a-4f0f-4cb3-ae19-e410e62f6198)

![Screenshot 2024-08-27 124853](https://github.com/user-attachments/assets/276e450e-ef4f-4a15-a3e7-f8f1b6655a59)


