# Earthquake Magnitude Prediction

This project uses machine learning (Random Forest Classifier) to predict earthquake magnitudes based on location and depth data.

## 📂 Dataset

The dataset includes the following features:
- **Latitude**
- **Longitude**
- **Depth**
- **Magnitude (Target)**

> The data is preprocessed and converted into numerical format before training.

## 🧠 Model

We use a **Random Forest Classifier** to train the model. The model learns to predict the magnitude of earthquakes based on input features.

Libraries used:
- `numpy`
- `pandas`
- `scikit-learn`
- `pickle` (for saving the model)

## 🔧 How to Run

1. Clone the repository.
2. Make sure you have Python and required libraries installed.
3. Place your dataset in the `data/` folder.
4. Run the main script
