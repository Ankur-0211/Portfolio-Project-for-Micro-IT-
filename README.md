#Portfolio Project for Micro IT 🎓

This project demonstrates how to build a machine learning model to predict student placement using academic, training, and project performance data.

## 📌 Features

- Data preprocessing with one-hot encoding
- Training a Random Forest classifier
- Saving the model using `joblib`

## 📁 Project Structure

- `preprocessing_and_model.py`: Core script for loading data, preprocessing, training, and saving the model.
- `dataset/placement_data.csv`: Dataset used for model training.
- `placement_model.pkl`: Trained model file (generated after running the script).
- `requirements.txt`: Python packages used.

## 📊 Dataset

The dataset includes features such as:
- Academic scores (10th, 12th, CGPA)
- Board type
- Internships, training, technical projects
- Communication level, stream, and backlog status

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/portfolio-project-micro-it.git
cd portfolio-project-micro-it
