# Brain Tumor Identification using Deep Learning

This repository contains the code and resources for the thesis project "Brain Tumor Identification using Deep Learning Models". The project focuses on the automatic detection of brain tumors from MRI scans by comparing the performance of two deep learning models: Convolutional Neural Network (CNN) and Visual Geometry Group-16 (VGG-16).

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Motivation](#-motivation)
- [Methodology](#-methodology)
- [Dataset](#-dataset)
- [Results](#-results)
- [How to Use](#-how-to-use)
- [Conclusion](#-conclusion)
- [Future Work](#-future-work)
- [Contributors](#-contributors)

## 📝 Project Overview

This project presents an automated system for identifying brain tumors from MRI images using deep learning techniques. The primary goal is to assist medical professionals in the early and accurate diagnosis of tumors, which is a critical yet challenging task. The study implements and evaluates two prominent models, CNN and VGG-16, to determine the most effective approach for this classification task.

## 💡 Motivation

Brain tumors are a significant cause of mortality worldwide, accounting for 85% to 90% of all primary central nervous system (CNS) tumors. Globally, it was anticipated that 308,102 people would be diagnosed with a primary brain or spinal cord tumor in 2020, with 251,329 deaths expected from the same causes. Early and accurate detection using non-invasive methods like MRI is crucial for effective treatment and improving patient survival rates. This project is motivated by the need for a reliable, automated system that can assist radiologists, reduce human error, and improve the efficiency of brain tumor diagnosis.

## ⚙️ Methodology

The methodology follows a structured pipeline from data collection to model evaluation, as illustrated in the flowchart below.


*A placeholder for Figure 3.6.10 from the report* 

1.  **Data Collection**: The dataset was acquired from Kaggle, a platform for data scientists.
2.  **Data Preparation**: This step involved cleaning and filtering the collected image data to make it suitable for the models.
3.  **Data Splitting**: The prepared dataset was split into training (80%) and testing (20%) sets.
4.  **Model Implementation**: Two deep learning models were applied:
    * **Convolutional Neural Network (CNN)**: A deep learning technique highly effective for image recognition and classification. The architecture involves convolutional layers for feature extraction, pooling layers for dimensionality reduction, and fully connected layers for classification.
    * **Visual Geometry Group-16 (VGG-16)**: A 16-layer CNN pre-trained on the ImageNet dataset, known for its high accuracy in image classification tasks.
5.  **Performance Analysis**: The models were evaluated using a confusion matrix and several key metrics to determine the best-performing algorithm.

## 🖼️ Dataset

The project utilizes a dataset of brain MRI scans collected from Kaggle. The dataset was carefully curated and preprocessed to ensure it was suitable for training and testing the deep learning models.

## 📊 Results

The performance of both the CNN and VGG-16 models was rigorously evaluated. The VGG-16 model demonstrated superior performance across most metrics.

| Model Name | Accuracy | Sensitivity | Specificity | Precision | F1-score |
| :--- | :---: | :---: | :---: | :---: | :---: |
| CNN | 92.02% | **93.64%** | 91.74% | 81.54% | 87.17% |
| **VGG-16** | **95.21%** | 93.22% | **96.02%** | **90.53%** | **91.85%** |
*[Source: Table 4.2.4: Performance evaluation]* 

The VGG-16 model achieved the highest accuracy at **95.21%**, specificity at **96.02%**, precision at **90.53%**, and F1-score at **91.85%**, making it the better-performing model for this dataset.

## 🚀 How to Use

To run this project, you will need Python 3.5+ and the necessary libraries installed.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/brain-tumor-identification.git](https://github.com/your-username/brain-tumor-identification.git)
    cd brain-tumor-identification
    ```
2.  **Install dependencies:**
    *(A `requirements.txt` file should be created for a real repository)*
    ```bash
    pip install tensorflow numpy pandas matplotlib scikit-learn
    ```
3.  **Prepare the dataset:**
    - Download the dataset from Kaggle.
    - Organize it into `train` and `test` directories.

4.  **Run the models:**
    - Execute the Python scripts for training the CNN and VGG-16 models.

## ✅ Conclusion

This study successfully demonstrates that deep learning models, particularly VGG-16, can be highly effective for the automated identification of brain tumors from MRI images. The proposed VGG-16 model provides a robust and accurate method that can significantly aid medical experts in making faster and more reliable diagnoses.

## 🔮 Future Work

Future research could explore several avenues to build upon this work:
* **Expand the dataset** to include more varied clinical cases.
* **Apply more algorithms** and optimization techniques to further enhance accuracy.
* Develop methods for **real-time image analysis**.
* Extend the methodology to identify other diseases in different parts of the body, such as the kidney, liver, or lungs.

## 👥 Contributors

This project was developed by:
* **Fahim Yusuf**

Under the supervision of:
* **Md. Sabab Zulfiker** (Supervisor) 
* **Tania Khatun** (Co-Supervisor) 

Department of Computer Science and Engineering
Daffodil International University
September 2022 
