# Heart Disease Prediction Project

A machine learning-based web application for predicting heart disease risk using clinical parameters.

## Features

- Interactive web interface built with Streamlit
- Multiple machine learning algorithms (KNN, Decision Tree, Random Forest)
- Hyperparameter-tuned models for optimal performance
- Real-time predictions with confidence scores
- Comprehensive feature information and model documentation


## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

## Installation

### Step 1: Clone or Download the Repository

```bash
git clone <repository-url>
cd heart-disease-prediction
```

Or download and extract the ZIP file to your desired location.

### Step 2: Create a Virtual Environment (Recommended)

**On Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**On macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Required Dependencies

```bash
pip install -r requirements.txt
```

Execute all cells to train the model and generate the pickle files.

## Requirements.txt

Create a `requirements.txt` file with the following content:

```
pandas==2.1.4
numpy==1.26.3
scikit-learn==1.4.0
matplotlib==3.8.2
seaborn==0.13.1

```

## Troubleshooting

### Common Issues

**Issue**: ModuleNotFoundError
```
Solution: Ensure all dependencies are installed
pip install -r requirements.txt
```

**Issue**: Model file not found
```
Solution: Train the model using the Jupyter notebook
jupyter notebook HeartDiseasePredictionProject.ipynb
```
