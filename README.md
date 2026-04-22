# Alzheimer-s-Disease-Detection
Cross-attentional CNN-Transformer fusion network (CAC-TFNet) for multi-stage Alzheimer's detection from MRI, combining MobileViT, TransUNet, and CvT for improved classification performance.

##  Introduction / Objective

Alzheimer’s disease is a progressive neurological disorder that affects memory and cognitive function. Early diagnosis is essential for effective treatment and patient care.

The objective of this project is to develop a deep learning-based system to automatically detect and classify different stages of Alzheimer’s disease from MRI brain scan images.



##  Dataset

The dataset consists of MRI brain images categorized into the following classes:

- Non Demented  
- Very Mild Demented  
- Mild Demented  
- Moderate Demented  

The dataset is divided into training and testing sets for model development and evaluation.



##  Model / Methodology

This project uses a Cross-Attentional CNN-Transformer Fusion Network (CAC-TFNet) for accurate classification of MRI images.

The model combines:

- **MobileViT** – Lightweight Vision Transformer for feature extraction  
- **TransUNet** – Captures local and global features  
- **CvT (Convolutional Vision Transformer)** – Learns rich image representations  
- **Cross-Attention Mechanism** – Fuses features effectively for final prediction  

Workflow:

1. Image preprocessing and resizing  
2. Feature extraction using deep learning models  
3. Feature fusion using cross-attention  
4. Classification into Alzheimer’s stages  
5. Performance evaluation using metrics and graphs  



##  Results

### Accuracy Graph
![Accuracy](results/accuracy.png)

### Loss Graph
![Loss](results/loss.png)

### Confusion Matrix
![Confusion Matrix](results/confusion_matrix.png)

The proposed model achieved strong classification performance with high accuracy and reliable predictions across all classes.



##  Technologies Used

- Python  
- Pytorch 
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- OpenCV  
- Jupyter Notebook  



##  How to Run

1. git clone https://github.com/your-username/Alzheimer-s-Disease-Detection.git
2. Install required libraries:
3. pip install tensorflow numpy pandas matplotlib scikit-learn opencv-python jupyter
4. -Launch Jupyter Notebook:
5. jupyter notebook
6. Open the notebook file and run all cells.
