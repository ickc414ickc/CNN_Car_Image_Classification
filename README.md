# Multi-Class Car Image Classification with a CNN

### [View the Full Project Report (PDF)](Car_Classification_Report.pdf) | [View the Jupyter Notebook](Car_Classification_Notebook.ipynb)

---

## 1. Project Goal

The objective of this project was to develop a high-accuracy Convolutional Neural Network (CNN) to classify vehicle images from a dataset of over 4,700 photos across five distinct classes (Bus, Car, Motorcycle, Truck, Van). The initial success metric was to achieve a validation accuracy of over 70%.

**Final Result:** The systematically optimized model achieved a **final validation accuracy of 92.7%**, significantly exceeding the initial target.

---

## 2. Skills & Tools Used

*   **Frameworks & Libraries:** Python, TensorFlow, Keras, Scikit-learn, LIME (Local Interpretable Model-agnostic Explanations)
*   **Deep Learning:** Convolutional Neural Networks (CNNs), Model Architecture Design
*   **Optimization Techniques:** L2 Regularization, Dynamic Learning Rates, Dropout, Batch Normalization
*   **Data Processing:** Data Cleaning, Image Augmentation, Handling Class Imbalance
*   **Explainable AI (XAI):** Using LIME to interpret and validate model decisions.

---

## 3. Analytical Process

The final high-performance model was developed through a systematic, iterative process:

1.  **Baseline Model:** Established an initial AlexNet-inspired CNN architecture to serve as a performance baseline.
2.  **Data Preprocessing & Augmentation:** Performed rigorous data cleaning to remove duplicates and misclassified images. The dataset was then balanced and expanded to 5,000 images per class using image augmentation to create a robust training set and prevent data leakage.
3.  **Systematic Optimization:** Iteratively improved the model by testing and implementing several key techniques:
    *   **Dropout layers** to reduce overfitting.
    *   **Increased model depth** with additional convolutional blocks.
    *   **L2 regularization** to improve generalization.
    *   **Dynamic learning rate scheduling** for faster convergence and finer-tuning.
4.  **Model Explainability (XAI):** Employed LIME to look "inside the black box" of the CNN. This step was crucial for validating that the model was learning relevant features (like wheels and windows) rather than relying on irrelevant background artifacts.

---
