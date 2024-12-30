# **Real Waste Image Classification**
A deep learning project aimed at classifying real waste with a focus on assessing model performance, improving accuracy, and offering recommendations for real-world applications.


## **Table of Contents**
1. [Introduction](#introduction)
2. [Data Overview](#data-overview)
3. [Deployment](#deployment)
4. [Methodology](#methodology)
5. [Conclusion](#conclusion)
6. [Recommendations](#recommendations)
7. [About Me](#about-me)


## **Introduction**
Waste is a major issue faced by many countries worldwide. The process required to manage and process waste varies significantly depending on the type of waste. Each waste category may require distinct handling methods, such as recycling, composting, or disposal, which makes accurate classification crucial. To address this challenge, Convolutional Neural Networks (CNNs) can be employed to automatically detect and classify different types of waste, ensuring that each type is processed using the most appropriate and efficient method. This technology can streamline the waste management process, reduce human error, and enhance overall efficiency.


## **Data Overview**
This dataset obtained from [Kaggle](https://www.kaggle.com/datasets/joebeachcapital/realwaste/) and contains labeled real waste images for training and testing.


## **Deployment**
The deployed model can be accessed at [HuggingFace](https://huggingface.co/spaces/abdul-aziz/waste-classification ).


## **Methodology**  
The methodology consists of the following steps:

1. **Data Loading**: Load and preprocess the dataset to ensure proper formatting.
2. **Exploratory Data Analysis**: Analyze the dataset to understand its distribution, identify patterns, and detect any data imbalances or anomalies.  
3. **Feature Engineering**: Extract relevant features from the images and apply techniques like augmentation to enhance model robustness.  
4. **CNN Training and Evaluation**: Train the Convolutional Neural Network on the dataset, using a suitable loss function and optimizer, and evaluate the model's performance using accuracy metrics.  
5. **CNN Optimization**: Fine-tune the model by adjusting hyperparameters, utilizing techniques like dropout or batch normalization to improve performance.  
6. **CNN Deployment**: Deploy the model to HuggingFace.


## **Conclusion**
The waste classification model was built using the Sequential API for its simplicity and clarity. Accuracy was chosen as the evaluation metric to ensure correct waste classification, as misclassifications can increase costs and reduce sorting efficiency.

Initially, a basic model with one convolutional layer achieved only 48% accuracy due to its inability to capture complex patterns. After enhancements, including additional layers, dropout, and ELU activation, the improved model reached 71% accuracy.

The model performed well in distinguishing visually distinct classes like food organics and glass but struggled with similar classes such as cardboard, metal, and plastic. 


## Recommendations
For further improvement, techniques such as transfer learning with a more complex pre-trained model or fine-tuning hyperparameters could be explored to achieve better performance.

## **About Me**
Abdul Aziz <br>
LinkedIn: [Abdul Aziz](https://www.linkedin.com/in/abdul-aziz-data-enthusiast/)


