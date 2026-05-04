# spam Email classifier
This project classifies messages as spam or not spam using Machine Learning
---

## 📌 Problem Statement
Detect whether a message is spam or not spam using CountVectorizer
---

##⚙️Approach
-Converted text to numerical data using CountVectorizer
-Used Multinomial Naive Bayes model
-Trained model on labeled dataset

---

## 🧠 Key Concept
Text cannot be used directly in ML,so it is covered into numerical vectors based on word frequesncy

---

## 🚀 Example Predictions
| Input | Output |
|------|--------|
"win money now" | Spam |
"let's meet tomorrow" | Not Spam |

---


## 🛠️ Tools Used
-Python
-Pandas
-Scikit-learn
---
## ⚠️ Limitations
- Small dataset
- No train/test split
- Accuracy is not realistic

---

## 🔮 Future Improvements
- Use real dataset
- Add train/test split
- Improve preprocessing
