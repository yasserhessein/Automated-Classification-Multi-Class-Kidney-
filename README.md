# 📊 **Automated Detection of Chronic Kidney Disease (CKD)**  
### 🔬 Using CNN-BiLSTM for Accurate and Early Diagnosis  
---

> **Authors**: Yasir Hussein Shakir  
> **Affiliation**: College of Graduate Studies (COGS), Universiti Tenaga Nasional (UNITEIN), Kajang, Malaysia  
> **Date**: 12-20-2024

---
Compute ROC curve and AUC for each class
💡 *"Early diagnosis can save lives—our proposed system leverages advanced machine learning models to assist in CKD classification."*

*"Chronic Kidney Disease (CKD) can result from various factors, including tumors, cysts, and kidney stones. Tumors have the potential to cause significant harm to essential organs, while kidney stones develop from solid deposits in the digestive tract. Early and precise diagnosis is crucial to prevent damage to glands, spinal cells, and other vital organs. This paper introduces an automated system for CKD detection utilizing a CNN-BiLSTM model. The CNN component extracts deep features from CT images, while the BiLSTM leverages its temporal sequence learning capabilities, employing four optimizers: Adam, Adamax, SGD, and RMSprop. During implementation, the proposed system achieved a test accuracy, precision, recall, and F1 score of 99.84% using the Adam optimizer. Experimental results demonstrate the system's potential to assist doctors in diagnosing CKD accurately and determining appropriate treatments to reduce patient mortality rates. Although the current dataset has validated the system's effectiveness, incorporating a larger and more diverse dataset in the future could enhance its performance. This research signifies a promising step toward advancing automated CKD diagnosis."*

### Table of Contents:



1. Import library
2. Dataset path and parameters
3. Normalize and one-hot encode
4. Split the dataset
5. CNN with BiLSTM model
6. Train the model
7. Evaluate the model
8. Evaluate the model on the test data
9. Compute ROC curve and AUC for each class
10. Load and preprocess the image to testing model

<h2 align="center">🧠 Model Architecture Summary</h2>

<div align="center">

<pre>
+---------------------+
|   Input CT Image    |
+----------+----------+
|
v
+---------------------+
|   CNN Layers        |
| Feature Extraction  |
+----------+----------+
|
v
+---------------------+
|  Bidirectional LSTM |
+----------+----------+
|
v
+---------------------+
| Fully Connected     |
+----------+----------+
|
v
+---------------------+
|   Softmax Layer     |
+----------+----------+
|
v
+---------------------+
|  Classification     |
| Normal | Cyst |     |
| Tumor  | Stone      |
+---------------------+
</pre>

</div>

### How to Run the Project
🔹 Step 1: Download Required Files

* Download the following files from this repository:

* cnn_bilstm_kidney_classification Adam.h5


🔹 Step 2: Install Required Libraries

* Run the following command:

* pip install tensorflow keras numpy matplotlib scikit-learn opencv-python

Recommended:

* Python 3.8 or higher

* Jupyter Notebook / Anaconda


🔹 Step 3: Open the Notebook

* Launch Jupyter:

* jupyter notebook

* Open:

5.AI with Chronic Kidney Disease.ipynb

🔹 Step 4: Run Code Cell #2

* Execute Code Cell Number 2 to load libraries and configurations.

* If prompted for a password, use:

*  yasir
  
🔹 Step 5: Test with New CT Image

* Navigate to:

* Load and preprocess the image to testing model




💾 **Dataset Used**:  
[CT Kidney Dataset - Normal, Cyst, Tumor, and Stone](https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone)

### 📫 **How to Contact Me**:
- **Kaggle**: [Yasir Hussein](https://www.kaggle.com/yasserhessein)  
- **GitHub**: [Yasir Hussein](https://github.com/yasserhessein)  
- **LinkedIn**: [Yasir Hussein](https://www.linkedin.com/in/yasir-hussein-314a65201/)  
- **Email**: [yasserhesseinshakir@yahoo.com](mailto:yasserhesseinshakir@yahoo.com) 
