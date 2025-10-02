# 📧 Spam Detection 

This project implements a simple **spam classifier** using **Naive Bayes** and **CountVectorizer** in Python.  
It trains on the popular **SMS Spam Collection Dataset** and allows you to test custom messages.

---

## 🚀 Features
- Preprocesses and cleans the dataset  
- Splits data into training and test sets  
- Uses **Bag-of-Words** with `CountVectorizer`  
- Trains a **Multinomial Naive Bayes classifier**  
- Tests accuracy on unseen data  
- Allows custom text input for spam detection  

---

## 📂 Project Structure
```
spam_classifier/
│── spam.csv              # Dataset file
│── app.py                # Main Python script
│── README.md             # Project documentation
```

---

## ⚙️ Installation

1. Clone this repository or download the code.  
2. Make sure you have **Python 3.8+** installed.  
3. Install required libraries:  

```bash
pip install pandas scikit-learn
```

---

## ▶️ Usage

1. Place the dataset (`spam.csv`) in the project folder.  
   - The dataset can be found at: [Kaggle - SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)  
2. Run the script:  

```bash
python app.py
```

3. Enter a message when prompted to check if it is **Spam** or **Ham (Not Spam)**.

---

## 📝 Example

```bash
Accuracy: 0.98
enter text to check: Congratulations! You've won a free lottery ticket
Its: spam
```

```bash
Accuracy: 0.98
enter text to check: Hey, are we meeting tomorrow?
Its: ham
```

---

## 📊 Accuracy
With the provided dataset, the model achieves around **97–99% accuracy** depending on the train-test split.  

---

## 📜 License
This project is open-source and free to use for learning purposes.  
