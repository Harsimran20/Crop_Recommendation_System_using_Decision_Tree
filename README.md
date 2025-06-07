# 🌾 Crop Recommendation System using Decision Tree

This project uses a **Decision Tree Classifier** to recommend the most suitable crop for cultivation based on environmental and soil conditions such as Nitrogen, Phosphorus, Potassium levels, temperature, humidity, pH, and rainfall.

---

## 📌 Objective

To assist farmers and agricultural planners in making informed decisions about **which crop to grow**, based on historical and scientific data using machine learning.

---

## 📁 Dataset

A sample dataset is included with the following features:

| Feature       | Description                        |
|---------------|------------------------------------|
| `N`           | Nitrogen content in soil           |
| `P`           | Phosphorus content in soil         |
| `K`           | Potassium content in soil          |
| `temperature` | Temperature in Celsius             |
| `humidity`    | Humidity in %                      |
| `ph`          | pH value of soil                   |
| `rainfall`    | Rainfall in mm                     |
| `label`       | Recommended crop (target class)    |

---

## ⚙️ Tech Stack

- **Language**: Python  
- **Libraries**:  
  - `pandas` for data handling  
  - `scikit-learn` for model building and evaluation  
  - `matplotlib` for visualization

---

## 🚀 How to Run

1. Clone the repository or download the code.
2. Install dependencies using:
   pip install pandas scikit-learn matplotlib
   
Run the script:

python crop_recommendation.py

🔍 Model Description

Algorithm: Decision Tree Classifier

Splitting Criterion: Entropy

Max Depth: 4

Evaluation: Accuracy Score, Classification Report

📊 Sample Output

Accuracy: 100.0%

Classification Report:
              precision    recall  f1-score   support

      barley       1.00      1.00      1.00         1
       maize       1.00      1.00      1.00         1
        rice       1.00      1.00      1.00         1
🌐 Real-World Applications

Personalized crop recommendations

Precision agriculture

Agricultural advisory systems

Policy-making for sustainable farming


📄 License
This project is licensed under the MIT License.
