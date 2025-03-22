# 📩 Spam SMS Detection  

## 📌 Overview  
This project focuses on detecting spam messages in SMS communication. It involves **data preprocessing, feature extraction, and machine learning classification** to distinguish spam from legitimate messages. Various models were tested to identify the most accurate classifier for spam detection.  

---

## 📂 Dataset  
The dataset consists of labeled SMS messages categorized as:  
- **📌 Spam** – Unwanted promotional or fraudulent messages  
- **📌 Ham** – Legitimate, non-spam messages  

The text data was processed using **TF-IDF vectorization** to convert it into numerical features for model training.  

---

## 🎯 Objective  
The goal of this project was to build a **spam filtering model** that accurately classifies SMS messages as spam or ham. Spam detection is essential for reducing scam and phishing attempts. Several **machine learning models** were tested, and the best-performing one was selected for final evaluation.  

---

## ⚙️ Implementation Details  
### 📝 Text Processing Techniques Used  
✔️ Stopword removal  
✔️ TF-IDF vectorization  

### 🚀 Machine Learning Models Tested  
✅ Logistic Regression  
✅ Naïve Bayes  
✅ Support Vector Machine (SVM)  
✅ Random Forest  
✅ Gradient Boosting  

After evaluation, **SVM achieved the highest accuracy of `97.7%`**, making it the best model for spam classification. The final model was tested using sample SMS messages.  

---

## 📊 Model Performance  

| Model                | Accuracy |  
|----------------------|----------|  
| **SVM (Best Model)** | `97.7%`  |  
| Logistic Regression  | `94.8%`  |  
| Naïve Bayes         | `97.0%`  |  
| Random Forest       | `97.5%`  |  
| Gradient Boosting   | `96.3%`  |  

---

## 🛠️ Technologies Used  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-Learn, NLTK  

---

## 🚀 How to Run  
To run this project, use **Jupyter Notebook** or **Google Colab**:  
1️⃣ Clone the repository:  
   ```sh
   git clone https://github.com/Pavani-Jyothirmai/Spam-SMS-Detection.git
   cd Spam-SMS-Detection
```
2️⃣ Open Spam_Detection.ipynb
3️⃣ Execute the cells sequentially to preprocess the data, train models, and test the best model
