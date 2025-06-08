# 💡 Wafer Fault Detection System

### 📑 Project Overview
In electronics manufacturing, a **wafer** (also known as a slice or substrate) is a thin layer of semiconductor material like crystalline silicon (c-Si), used as the foundation for building integrated circuits (ICs) and solar cells. These wafers undergo complex microfabrication processes such as doping, ion implantation, etching, thin-film deposition, and photolithographic patterning. After fabrication, the wafers are diced into individual chips and packaged.

This project focuses on **automated wafer fault detection** using machine learning to identify defective wafers in the manufacturing process. The model predicts whether a wafer is faulty (`-1`) or normal (`1`).

---

### 📂 Dataset
The dataset is sourced from **Kaggle** and stored in a **MongoDB** database for efficient access and scalability.

---

### 🔧 Technologies Used
- **Python 3.8**
- **Flask** (Web framework)
- **Scikit-learn** (Machine learning)
- **MongoDB** (Database)
- **HTML/CSS** (Frontend design)

---

### ⚙️ Installation and Setup

1. **Clone the repository**
*git clone https://github.com/vishwakarma9470/Machine-Learning.git*
*cd Machine-Learning*
2. **Create Python Environment**
*conda create --prefix venv python=3.8 -y*
*conda activate venv/*

3. **Install Dependencies**
*pip install -r requirements.txt*

4. **Run the Application**
*python app.py*


### 🚀 How to Use 
- Upload your wafer data file using the input field.
- Click on Custom File Predict to use your file or use Default File Predict.
- The system will return predictions as a JSON-like structure.

### 🖥️ Output Screenshot
- Below is an example output after running a wafer prediction:
![Screenshot](result.jpg)

### 🏭 Industrial Applications
- Semiconductor Manufacturing
- Quality Control in Electronics
- Solar Cell Fabrication

#### By automating fault detection, industries can:

- Reduce waste
- Improve product quality
- Save manual inspection time
