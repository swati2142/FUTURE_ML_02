# Support Ticket Classification & Prioritization

## 📌 Internship Track
Machine Learning – Future Interns  
**Task 2 (2026): Support Ticket Classification & Prioritization**

---

## 📖 Project Overview
Customer support teams in real-world organizations handle a large volume of tickets daily, including technical issues, billing problems, and general queries. Manually categorizing and prioritizing these tickets is time-consuming and inefficient.

This project focuses on building a Machine Learning–based NLP system that automatically classifies customer support tickets into categories and assigns priority levels, helping businesses respond faster and improve operational efficiency.

---

## 🎯 Objective
- Automatically classify customer support tickets based on text content  
- Assign priority levels (High / Medium / Low) to tickets  
- Improve support response time and ticket handling efficiency  
- Demonstrate real-world application of NLP and Machine Learning  

---

## 📊 Dataset
**Dataset Used:** Customer Support Ticket Dataset  
**Source:** Kaggle  

The dataset contains real-world customer support ticket information, including ticket descriptions and ticket types.

### Key Columns Used
- `Ticket Description` – textual content of the support ticket  
- `Ticket Type` – category of the support ticket  

---

## 🧹 Data Preparation
The following preprocessing steps were performed:
- Selected relevant text and category columns  
- Converted all text to lowercase  
- Removed punctuation, numbers, and stopwords  
- Prepared clean text data suitable for NLP tasks  

---

## ⚙️ Feature Engineering
- Text data was converted into numerical features using **TF-IDF Vectorization**
- This approach captures the importance of words while reducing noise from commonly used terms

---

## 🤖 Model Used
**Logistic Regression**

A classification model was trained to predict the category of support tickets based on textual content.  
This model was chosen for its simplicity, efficiency, and interpretability in NLP-based classification tasks.

---

## 📈 Model Evaluation
The model was evaluated using standard classification metrics:
- Accuracy  
- Precision  
- Recall  
- F1-score  

A confusion matrix was also generated to analyze class-wise performance.

---

## 🚦 Priority Assignment Logic
Priority levels were assigned based on the predicted ticket category:

- **High Priority:** Technical issues, billing problems, payment failures  
- **Medium Priority:** Account-related and login issues  
- **Low Priority:** General queries and non-urgent requests  

This prioritization helps support teams focus on critical issues first.

---

## 🧠 Business Impact
- Automatically categorizes incoming support tickets  
- Identifies urgent issues early to reduce response delays  
- Improves customer satisfaction through faster resolution  
- Reduces manual workload for support teams  

The system can be confidently explained to a support manager, SaaS founder, or business client.

---

## 🛠️ Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- NLTK  
- Scikit-learn  
- TF-IDF Vectorizer  
- Google Colab  

---

## 📦 Project Structure
FUTURE_ML_02/
│
├── Support_Ticket_Classification_&_Prioritization.ipynb
│ └── Jupyter notebook containing NLP preprocessing, model training,
│ evaluation, priority assignment, and business demonstration
│
├── customer_support_tickets.csv
│ └── Dataset used for training and evaluation
│
├── README.md
│ └── Project documentation and explanation
│
└── requirements.txt
└── List of required Python libraries


---

## 🚀 Conclusion
This project demonstrates how Natural Language Processing and Machine Learning can be applied to real operational problems.  
By automating ticket classification and prioritization, businesses can improve efficiency, reduce response times, and enhance customer experience.

---

## 🔗 Acknowledgement
This project was completed as part of the **Future Interns – Machine Learning Internship (2026)**.


