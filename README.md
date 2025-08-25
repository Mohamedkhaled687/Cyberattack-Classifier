# ML Task NTI - Final Evaluation

## 🚀 Project Overview

This repository contains the final evaluation project for the **Machine Learning Task at NTI (National Telecommunication Institute)**, focusing on **Binary Cybersecurity Attack Detection** using the **UNSW-NB15 dataset**. The project demonstrates machine learning techniques for network intrusion detection by classifying network traffic as either **attack** or **normal**.

## 🎯 Project Objectives

- **Implement** a robust **binary classifier** for cyber attack detection
- **Analyze** network traffic patterns to identify malicious vs legitimate activities
- **Evaluate** model performance using comprehensive testing datasets
- **Demonstrate** practical application of ML in cybersecurity domain

## 🔍 What This Project Does

This project implements a **Binary Intrusion Detection System (IDS)** that can:
- **Classify** network traffic as either **ATTACK** or **NORMAL**
- **Analyze** network traffic patterns in real-time
- **Detect** the presence of malicious activities
- **Provide** binary security alerts (attack detected or not)

## 📁 Project Structure

```

├── CyberAttackClassifier.ipynb      # Jupyter notebook with comprehensive analysis
├── UNSW_NB15_training-set.csv    # Training dataset (31MB)
├── UNSW_NB15_testing-set.csv     # Testing dataset (15MB)
├── .gitignore            # Git ignore rules
└── README.md             # Project documentation
```

## 🗃️ Dataset Information

The **UNSW-NB15 dataset** is a comprehensive network traffic dataset specifically designed for intrusion detection research:

- **Source**: University of New South Wales
- **Purpose**: Network security analysis and ML model training
- **Features**: Network traffic features for binary classification
- **Applications**: IDS development, security research, academic studies

### Binary Classification Categories:
- **Normal Traffic**: Legitimate network communications (Class 0)
- **Attack Traffic**: Any type of malicious network activity (Class 1)

## 🛠️ Technologies & Tools

- **Programming Language**: Python 3.x
- **Machine Learning**: Scikit-learn for binary classification
- **Data Analysis**: Pandas, NumPy, Matplotlib
- **Development**: Jupyter Notebook, VS Code
- **Version Control**: Git & GitHub

## 🚀 Getting Started

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook
- Required ML libraries (see requirements.txt if available)

### Installation & Usage
1. **Clone** this repository
   ```bash
   git clone https://github.com/Mohamedkhaled687/Cyberattack-Classifier.git
   cd Cyberattack-Classifier
   ```

2. **Install** dependencies (if requirements.txt exists)
   ```bash
   pip install -r requirements.txt
   ```

3. **Run** the Jupyter notebook
   ```bash
   jupyter notebook final_eval.ipynb
   ```

4. **Execute** the main application
   ```bash
   python app.py
   ```

## 📊 Key Features

- **Binary Classification**: Detects attack vs no attack
- **Real-time Processing**: Handles network traffic streams
- **Performance Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC
- **Visualization**: Charts and graphs for analysis
- **Model Persistence**: Save and load trained models

## 🎓 Learning Outcomes

This project demonstrates:
- **Binary Classification** fundamentals in cybersecurity
- **Data Preprocessing** techniques for network data
- **Feature Engineering** for security applications
- **Model Evaluation** and performance optimization
- **Practical Implementation** of ML in real-world scenarios

## 🔬 Research Applications

- **Academic Research**: Network security studies
- **Industry Use**: Corporate security systems
- **Government**: National cybersecurity initiatives
- **Education**: ML and cybersecurity training

## 📈 Future Enhancements

- **Real-time API**: RESTful service for live traffic analysis
- **Web Interface**: User-friendly dashboard
- **Advanced Models**: Deep learning implementations
- **Cloud Deployment**: Scalable cloud-based solution
- **Mobile App**: Security monitoring on mobile devices

## 🤝 Contributing

This is an academic project for NTI evaluation. For educational purposes, feel free to:
- **Fork** the repository
- **Study** the implementation
- **Improve** the algorithms
- **Share** your findings

---