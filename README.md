# 🔐 Ransomware Detection Mechanism (RDM) - ML-Based Network Threat Analyzer

Ransomware Detection Mechanism (RDM) is a Machine Learning-based framework built to detect ransomware threats using bidirectional netflow data. Originally developed as an academic research project, RDM now serves as a real-world ready prototype that blends supervised learning techniques with real network traffic data to identify anomalies and potential ransomware indicators.

---

## 🚀 Project Highlights

- ⚡ **Machine Learning Powered**: Leverages supervised learning models (Random Forest, XGBoost, etc.) trained on real bidirectional netflow logs.
- 🔍 **Feature-Rich Data Pipeline**: Modular data preprocessing, transformation, and feature engineering for robust model performance.
- 📈 **Emotet IOC Analysis**: Visualizes and analyzes Indicators of Compromise (IOCs) from the Emotet malware family.
- 🧠 **Educational + Practical**: Built with research integrity and extendable into production scenarios.
- 🧪 **Automated Environment Setup**: Includes `Makefile` and `requirements.txt` for seamless experimentation and reproducibility.

---

## 🧠 Use Cases

- Network Security Education & Training
- Academic Research & Benchmarking
- Security Data Science Projects
- Proof-of-Concept for Enterprise Network Security Teams

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Libraries**: Scikit-learn, Pandas, XGBoost, Matplotlib, NumPy
- **Workflow Tools**: Make, PyLint, Travis CI
- **Data**: Netflow logs (binetflow), IOC feeds

---

## 🧪 How to Run This Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Ransomware-Detection-Mechanism.git
cd Ransomware-Detection-Mechanism
```

### 2. Set Up the Environment

We recommend using a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows

pip install -r requirements.txt
```

### 3. Run Data Preprocessing

```bash
make preprocess
```

### 4. Train the ML Model

```bash
make train
```

### 5. Validate and Evaluate

```bash
make validate
make evaluate
```

---

## 📁 Project Structure

```
├── data/
│   ├── raw/              <- Raw netflow and IOC data
│   ├── processed/        <- Cleaned and feature-engineered data
│   └── preprocessed/     <- Intermediate transformed data
├── models/               <- Saved ML models and training logs
├── notebooks/            <- Jupyter notebooks for exploratory analysis
├── src/                  <- Source code modules
├── test_environment.py   <- Script to test environment integrity
├── Makefile              <- Automates data/mode workflows
└── README.md             <- Project documentation (you are here)
```

---

## 🧩 Unique Features

* 🎯 Real-world dataset for high-quality threat detection
* 🛠️ Modular architecture for easy maintenance and scalability
* 📊 Included report for technical understanding and academic use

---

