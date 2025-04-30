# Fetal AI Health Care Prediction

A machine learning project utilizing classification algorithms to predict fetal health status based on cardiotocographic (CTG) measurements. This tool aims to assist healthcare professionals in early detection of abnormal fetal conditions through AI-driven insights.

## 🧠 Project Overview

This project analyzes CTG data to classify fetal health into three categories:
- **Normal (1)**
- **Suspect (2)**
- **Pathological (3)**

The workflow encompasses data preprocessing, feature selection, model training, evaluation, and deployment via a Flask web application.

## 📁 Repository Structure

```
├── app.py                   # Flask application script
├── Main Code.ipynb          # Jupyter Notebook with data analysis and model training
├── fetal_health.csv         # Dataset containing CTG measurements
├── fetal_health.pkl         # Serialized machine learning model
├── templates/
│   └── index.html           # HTML template for the web interface
├── static/
│   └── css/
│       └── style.css        # CSS styling for the web interface
└── README.md                # Project documentation
```

## 📊 Dataset

- **Source**: [Kaggle - Fetal Health Classification](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)
- **Description**: The dataset comprises 21 numerical features extracted from CTG examinations, each labeled by expert obstetricians into one of the three health categories.

## 🛠️ Technologies Used

- **Programming Language**: Python 3.x
- **Libraries**:
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
  - Web Framework: `Flask`
- **Model Serialization**: `pickle`

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- pip (Python package installer)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Rakesh-012/new.git
   cd new
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

   *Note: If `requirements.txt` is not present, you can install packages manually:*
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn flask
   ```

### Running the Application

1. **Start the Flask server**:
   ```bash
   python app.py
   ```

2. **Access the web interface**:
   Open your browser and navigate to `http://127.0.0.1:5000/`

## 🧪 Model Training and Evaluation

The Jupyter Notebook `Main Code.ipynb` includes:
- Data preprocessing steps
- Exploratory Data Analysis (EDA)
- Model training using classification algorithms
- Evaluation metrics such as accuracy, precision, recall, and F1-score

## 📈 Visualizations

The project includes various plots to aid in understanding the data and model performance:
- Correlation heatmaps
- Distribution plots
- Confusion matrices

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Acknowledgments

- Dataset provided by [Kaggle - Fetal Health Classification](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)
- Inspired by the need for early detection tools in prenatal care
