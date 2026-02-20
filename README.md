# ML & Data Science Projects

[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A collection of machine learning and data science projects covering anomaly detection, statistical analysis, and data visualization.

## Projects Overview

| Project | Domain | Techniques | Status |
|---------|--------|------------|--------|
| [Credit Card Fraud Detection](#credit-card-fraud-detection) | Anomaly Detection | Isolation Forest, LOF, One-Class SVM | ✅ Complete |
| [Anomaly Detection Model](#anomaly-detection-model) | Unsupervised Learning | Custom anomaly detection pipeline | ✅ Complete |
| [Data Analysis Project](#data-analysis-project) | EDA & Visualization | Pandas, Matplotlib, Seaborn | ✅ Complete |
| [Demographic Data Analyzer](#demographic-data-analyzer) | Statistical Analysis | Descriptive statistics, Groupby operations | ✅ Complete |
| [Statistical Calculator](#statistical-calculator) | NumPy Operations | Mean, Variance, Standard Deviation | ✅ Complete |
| [Tip Calculator](#tip-calculator) | Basic Python | Functions, User input handling | ✅ Complete |

---

## Projects

### Credit Card Fraud Detection

**File**: `Anomaly_Detection_using_Isolation_Forest.ipynb`

Detect fraudulent credit card transactions using unsupervised learning on highly imbalanced data (0.172% fraud rate).

**Key Features**:
- Isolation Forest implementation
- Local Outlier Factor comparison
- One-Class SVM baseline
- Precision-Recall evaluation (appropriate for imbalanced data)

**Dataset**: Kaggle Credit Card Fraud Detection (284,807 transactions)

---

### Anomaly Detection Model

**File**: `AnomolyDetectionModel.ipynb`

Custom anomaly detection pipeline with train/test split and model evaluation.

**Key Features**:
- File upload interface for custom datasets
- Train/test split methodology
- Binary classification for anomaly detection
- Model performance metrics

---

### Data Analysis Project

**File**: `DataAnalysisProject_1.ipynb`

Comprehensive data analysis on demographic and economic datasets.

**Key Features**:
- Data cleaning and preprocessing
- Exploratory data analysis
- Statistical summaries
- Correlation analysis
- Visualization of key trends

---

### Demographic Data Analyzer

**File**: `Demographic_Data_Analyzer.ipynb`

Statistical analysis of demographic data with groupby operations and descriptive statistics.

**Key Features**:
- Demographic segmentation
- Statistical comparisons across groups
- Data aggregation techniques
- Insight extraction from census-style data

---

### Statistical Calculator

**File**: `Mean_Variance_Standard_Deviation_Calculator.ipynb`

Implementation of core statistical functions using NumPy.

**Key Features**:
- Mean calculation
- Variance computation
- Standard deviation
- Matrix operations on datasets

---

### Tip Calculator

**File**: `Project_Tip_Calculator.ipynb`

Simple Python project for calculating restaurant tips.

**Key Features**:
- User input handling
- Tip percentage calculation
- Bill splitting functionality
- Basic Python syntax demonstration

---

## Installation

```bash
# Clone the repository
git clone https://github.com/MusaBrown/Projects.git
cd Projects

# Install dependencies
pip install -r requirements.txt
```

## Dependencies

```
numpy>=1.19.0
pandas>=1.3.0
scikit-learn>=1.0.0
scipy>=1.7.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
```

## Usage

Each notebook is self-contained and can be run independently:

```bash
jupyter notebook
```

Then open any `.ipynb` file to explore the project.

## Project Structure

```
Projects/
├── README.md                                    # This file
├── requirements.txt                             # Python dependencies
├── Anomaly_Detection_using_Isolation_Forest.ipynb   # Fraud detection
├── AnomolyDetectionModel.ipynb                  # Custom anomaly detection
├── DataAnalysisProject_1.ipynb                  # Data analysis
├── Demographic_Data_Analyzer.ipynb              # Demographic statistics
├── Mean_Variance_Standard_Deviation_Calculator.ipynb  # Statistical calc
├── Project_Tip_Calculator.ipynb                 # Tip calculator
└── Untitled0.ipynb                              # Work in progress
```

## Skills Demonstrated

- **Machine Learning**: Unsupervised learning, anomaly detection, model evaluation
- **Data Analysis**: EDA, statistical analysis, data visualization
- **Python Programming**: NumPy, Pandas, Scikit-learn
- **Jupyter Notebooks**: Interactive data exploration and presentation

## Future Projects

- [ ] Deep learning anomaly detection (Autoencoders, VAEs)
- [ ] Time series forecasting
- [ ] Natural language processing project
- [ ] Computer vision classification
- [ ] End-to-end ML pipeline with deployment

## Notes

- Notebooks are designed to run in Google Colab (see Colab badges in individual notebooks)
- Some notebooks require uploading custom datasets
- All projects include detailed markdown explanations

## License

MIT License — see [LICENSE](LICENSE) for details.

## Author

Brown — [@MusaBrown](https://github.com/MusaBrown)

---

*Collection of projects for skill development in machine learning and data science.*
