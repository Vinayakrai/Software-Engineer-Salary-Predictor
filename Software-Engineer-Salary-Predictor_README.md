# Software-Engineer-Salary-Predictor

**Software-Engineer-Salary-Predictor** is a Python-based machine learning application that predicts a software engineer's salary based on their experience, country, and education level. The project utilizes a trained model to provide accurate salary estimations.

## 🚀 Features

- **User Input**: Accepts user inputs for experience, country, and education level.
- **Salary Prediction**: Predicts salary based on the provided inputs using a trained machine learning model.
- **Interactive Interface**: Offers an interactive interface for users to input data and receive predictions.

## 🛠️ Prerequisites

- **Python 3.x**: Ensure Python is installed on your system.
- **Required Libraries**:
  - `streamlit`
  - `scikit-learn`
  - `pandas`
  - `numpy`
  - `matplotlib`

## 📦 Installation

1. **Clone the Repository**:

```bash
git clone https://github.com/Vinayakrai/Software-Engineer-Salary-Predictor.git
cd Software-Engineer-Salary-Predictor
```

2. **Install Required Packages**:

It's recommended to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Then install the dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Run the Streamlit application:

```bash
streamlit run app.py
```

The application will launch in your default web browser, where you can input your experience, country, and education level to receive a predicted salary.

## 📁 Project Structure

```
Software-Engineer-Salary-Predictor/
├── app.py
├── explore_page.py
├── predict_page.py
├── requirements.txt
├── saved_steps.pkl
├── SalaryPrediction.ipynb
└── README.md
```

- `app.py`: Main application script.
- `explore_page.py`: Script for data exploration.
- `predict_page.py`: Script for handling predictions.
- `requirements.txt`: Lists all required Python packages.
- `saved_steps.pkl`: Serialized trained model.
- `SalaryPrediction.ipynb`: Jupyter notebook for model training and evaluation.


