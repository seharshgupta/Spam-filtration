# 📧 Spam Filtration using Machine Learning

This project implements a **Spam Detection System** using Natural Language Processing (NLP) and Machine Learning. It classifies messages as **Spam** or **Ham (Not Spam)** using **TF-IDF vectorization** and a **Logistic Regression** model.

---

## 🧠 Objective

To build an intelligent text classifier that can detect spam messages in emails or SMS using classical machine learning techniques.

---

## 🗂️ Dataset

- Format: CSV file (`mail_data.csv`)
- Columns:
  - `Category`: Label (`spam` or `ham`)
  - `Message`: Text message content

---

## 🛠️ Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| **Python** | Core programming language |
| **Pandas** | Data manipulation and loading |
| **Scikit-learn** | Model building, preprocessing, evaluation |
| **NumPy** | Numerical operations |
| **Matplotlib / Seaborn** | Visualizations (confusion matrix) |
| **Jupyter Notebook** | Interactive development |

---

## 🔍 Process Flow

1. **Load the dataset** using pandas  
2. **Clean the data** (handle missing values, convert labels)  
3. **Text preprocessing** using `TfidfVectorizer`  
4. **Split data** into training and test sets  
5. **Train model** using `LogisticRegression`  
6. **Evaluate** using accuracy, confusion matrix, and classification report  
7. **Predict** on custom inputs  

---

## 📈 Model Used

- **Logistic Regression**: A simple yet effective model for binary classification.  
- Input features are generated using **TF-IDF Vectorization**.

---

## 🧪 Evaluation

- **Accuracy**: Achieved high accuracy on test data.  
- **Classification Report**: Includes precision, recall, and F1-score.  
- **Confusion Matrix**: Visualized using Seaborn heatmap.

---

## 🔮 Example Predictions

```python
"Congratulations! You've won a $1,000 Walmart gift card." ➝ Spam  
"Hi John, just checking if you're available for tomorrow's meeting." ➝ Ham
```
