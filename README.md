<center><img width="800" src="Images/CB_UFRN.jpeg"></center>

# Federal University of Rio Grande do Norte  
## Bioscience Center  
### Graduate Program in Ecology  
#### ECL0045 - Tópicos Especiais em Ecologia IV: Machine Learning for Life Sciences

---

## 🧭 Course Overview

This course introduces the fundamentals of **Machine Learning (ML)** with a focus on real-world applications in the **life sciences**. The content includes theoretical concepts, hands-on notebooks, and use cases based on recent research. Classes are structured to gradually introduce students to both basic and advanced topics.

---

## 📚 Class 01 – Course Outline  

### 1. Introduction  
- What are AI, ML, and DL?  
- Real-world applications in life sciences  

### 2. ML Fundamentals  
- Visualization and Exploratory Data Analysis (EDA)  
- Features, distance, and neighborhood  
- Dimensionality Reduction  
- Unsupervised ML  
- Supervised ML – Classification  

### 3. Applications  
- Ovitrap Data Analysis  
- Fish Choruses  
- Shrimp Feeding Sound Detection  
- Marine Species Identification  
- Cyclic Voltammetry for Syphilis/HIV Detection  
- DNA Sequence Analysis for Virus Classification

### Materials

[class01 ![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/igendriz/ml-for-life-sciences/blob/main/Class01/class01.pdf)

## 📘 Class 02 – Python Essentials and Intro to Data Analysis

This notebook is part of the crash course **"Machine Learning in Life Sciences"**, aimed at graduate students in the biological sciences.

The class is divided into two parts:

### 🧩 Part I: Python Foundations  
Introduction to core Python programming concepts, including:
- Variables and data types  
- Conditional statements and loops  
- Functions and modular code  

### 📊 Part II: Introduction to Data Analysis with Python  
Basic techniques for data manipulation and visualization using:
- **NumPy** for numerical operations  
- **Pandas** for tabular data analysis  
- **Matplotlib** and **Seaborn** for plotting and exploration  
- First steps in **Exploratory Data Analysis (EDA)**

### Materials

💻 Notebook: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1WqcwTfefs4T9jeByWvqRWyS3NJHvW1Gi?authuser=1#scrollTo=KChSJz_kGN6l)

## 📘 Class 03 – Dimensionality Reduction, Clustering & Intro to Classification

The class is divided into three parts:

### 🔻 Part I: Dimensionality Reduction  
- Understanding the **curse of dimensionality**  
- Overview of **feature selection** and **feature extraction**  
- Introduction to **Principal Component Analysis (PCA)**

### 🧭 Part II: Clustering  
- Key concepts and goals of clustering  
- Methods: **K-means**, **Hierarchical Clustering**, and **DBSCAN**  
- Practical examples using synthetic and real-world data

### 🧩 Part III: Introduction to Classification  
- Fundamentals of classification tasks  
- Focus on the **K-Nearest Neighbors (KNN)** algorithm  
- Implementation and evaluation with simple datasets

### Materials

💻 Notebook: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eW9E22ixTmgAh1jC6ux-5VHno-mBsDl-?authuser=1)

## 📘 Class 04 – Classification Models & Model Validation

This class covers the fundamentals of classification algorithms and how to properly evaluate them.

### 🧠 1. Classification Tasks  
- Understanding classification problems and how they differ from other ML tasks

### ⚙️ 2. Machine Learning Classifiers  
- Overview of classical ML classifiers (e.g., Decision Trees, SVMs, Logistic Regression)  
- Introduction to **Artificial Neural Networks (ANNs)**  
- Overview of the **ANN ecosystem** and its relevance to life sciences

### 🧪 3. Overfitting & Underfitting  
- Key concepts to understand model generalization  
- How to identify and mitigate underfitting and overfitting in practice

### 📏 4. Validating ML Classifiers  
- Evaluation metrics for classification (accuracy, precision, recall, F1-score)  
- Introduction to **cross-validation techniques**

### Materials 

📄 [class4.pdf](https://github.com/igendriz/ml-for-life-sciences/blob/main/Class04/class4.pdf)

---

## 📁 Repository Structure

```plaintext
ml-for-life-sciences/
│
├── README.md                  ← This file
├── requirements.txt           ← Notebooks dependencies (optional)
│
├── Images/                    ← Images used in the README or presentations
│   └── CB_UFRN.jpeg
│
├── Dataset/                   ← Datasets used in the notebooks
│   └── LBW_Data.csv           ← Accessible via direct GitHub URL for Colab
│
├── Class01/                   ← Week 1 materials
│   ├── class01.pdf            ← Slides
│   └── notebook_01.ipynb
│
├── Class02/
├── Class03/
├── Class04/
├── Class05/
├── Class06/
```

> 💡 Notebooks are designed to be run in [Google Colab](https://colab.research.google.com/).  
> Datasets are referenced via **raw GitHub links** and loaded directly using `pandas.read_csv(...)`.

---

## 📖 Learning Resources

- [Kaggle Python Course](https://www.kaggle.com/learn/python) – A quick-start track to strengthen Python skills.
- [AI Python for Beginners (Andrew Ng)](https://www.deeplearning.ai/short-courses/ai-python-for-beginners/) – Learn Python basics and AI tools for data analysis.

---

## 📑 Referenced Publications

The following papers were used to illustrate real ML applications in life sciences during the course:

- **Dengue Forecasting (Sci Rep, 2022)**  
  *Data-driven computational intelligence applied to dengue outbreak forecasting: a case study at the scale of the city of Natal, RN-Brazil*  
  [DOI: 10.1038/s41598-022-10512-5](https://doi.org/10.1038/s41598-022-10512-5)

- **Ovitrap Dynamics (CBIC, 2023)**  
  *Deep Learning-Based Ovitrap Spatial Dynamics Analysis for Arbovirus Vector Monitoring*  
  [DOI: 10.21528/CBIC2023-056](https://doi.org/10.21528/CBIC2023-056)

- **Fish Choruses (Frontiers in Antennas and Propagation, 2024)**  
  *Exploring fish choruses: patterns revealed through PCA computed from daily spectrograms*  
  [DOI: 10.3389/fanpr.2024.1400382](https://doi.org/10.3389/fanpr.2024.1400382)

- **Shrimp Feeding Detection (Aquaculture, 2025)**  
  *Python-based acoustic detection of Penaeus vannamei feeding behavior*  
  [DOI: 10.1016/j.aquaculture.2024.741645](https://doi.org/10.1016/j.aquaculture.2024.741645)

- **DNA Virus Classification (bioRxiv, 2024)**  
  *Gene Sequence to 2D Vector Transformation for Virus Classification*  
  [DOI: 10.1101/2024.03.12.24304158](https://doi.org/10.1101/2024.03.12.24304158)

- **Syphilis/HIV Detection (Computers in Biology and Medicine, 2024)**  
  *Digital dual test syphilis/HIV detection based on Fourier Descriptors of Cyclic Voltammetry curves*  
  [DOI: 10.1016/j.compbiomed.2024.108454](https://doi.org/10.1016/j.compbiomed.2024.108454)

---

## 🧪 Developed by  
**Prof. Ignacio Sánchez-Gendriz**  
Machine Learning & Signal Processing for Life Sciences  
Federal University of Rio Grande do Norte (UFRN)  
