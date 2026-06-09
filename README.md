# 🛡 AI-Enhanced Intrusion Detection System (IDS)

## Cybersecurity Threat Detection Using Machine Learning

## 📌 Project Description

In an increasingly interconnected digital landscape, the security of organizational networks and sensitive data is of paramount importance. This project focuses on the development of an **AI-Enhanced Intrusion Detection System (IDS)** that leverages machine learning to detect, classify, and respond to network intrusions with high accuracy.

By combining advanced **Random Forest Classification** with cybersecurity domain knowledge, the system empowers organizations to proactively combat evolving threats.

---

## 🛠 Technologies Used

* Python 3.10+
* Flask (Backend Web Framework)
* HTML / CSS (Frontend UI)
* Pandas / NumPy (Data Manipulation)
* Scikit-learn (Machine Learning)
* Imbalanced-learn (SMOTE for Class Balancing)
* Joblib (Model Serialization)

---

## 🧠 Model Details

The Intrusion Detection System uses a **Random Forest Classifier** trained on a preprocessed and balanced network intrusion dataset. The model is enhanced with **SMOTE** to handle class imbalance.

The final model is saved as:

```bash
random_forest_model_4_features.joblib
```

---

## 🗂 Project Directory Structure

```text
AI-ENHANCED-INTRUSION-DETECTION/
├── CYBER_PROJECT/
│   ├── templates/
│   │   └── index.html
│   ├── app.py
│   ├── random_forest_model_4_features.joblib
│   ├── web_attacks_balanced.csv
│   ├── requirment.txt
│   ├── Untitled.ipynb
│   └── README.md
├── Documentation...
└── README.md
```

---

## ⚙ Installation & Setup

### Using Conda (Recommended)

```bash
conda create -n cyber_ids python=3.10
conda activate cyber_ids

git clone https://github.com/YOUR_USERNAME/AI-Enhanced-Intrusion-Detection-System.git

cd CYBER_PROJECT

pip install -r requirment.txt
```

### Using Python venv

```bash
python -m venv ids_env
```

#### Windows

```bash
ids_env\Scripts\activate
```

#### macOS/Linux

```bash
source ids_env/bin/activate
```

```bash
pip install -r requirment.txt
```

---

## ▶ Running the Application

```bash
python app.py
```

Open your browser and navigate to:

```text
http://127.0.0.1:5000/
```

---

## 📊 Dataset Overview

The `web_attacks_balanced.csv` dataset includes labeled network traffic data categorized into different types of intrusions and normal behavior. The dataset is preprocessed and balanced to improve model performance and classification accuracy.

---

## 🎯 Features

* Real-time intrusion detection
* Machine learning-powered threat classification
* Random Forest-based prediction model
* Balanced dataset using SMOTE
* User-friendly web interface with Flask
* Fast and accurate network threat analysis

---

## 📈 Future Enhancements

* Deep Learning-based intrusion detection
* Real-time packet capture integration
* Cloud deployment support
* Advanced threat visualization dashboard
* Multi-class attack categorization

---

## ✅ Conclusion

This project showcases how Artificial Intelligence and Machine Learning can be effectively applied to cybersecurity for real-time intrusion detection and network threat mitigation. With high accuracy and automation, this AI-powered IDS reduces response time and enhances the overall security posture of an organization.

---

### 👨‍💻 Author

**Priya Patil**

MCA Student | Data Analyst | Python Developer

Passionate about Cybersecurity, Machine Learning, Data Analytics, and Software Development.
