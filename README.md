\# Phishing Email Classification



This project studies how machine learning can distinguish phishing emails from legitimate emails. It was developed for the Research Methodology course at Bina Nusantara University.



The study uses the CEAS 2008 Phishing Email Dataset. Email bodies were converted into TF-IDF features, while email length was added as a structural feature. Five models were compared: Logistic Regression, Support Vector Machine, Random Forest, Decision Tree, and Naive Bayes. SMOTE was applied only to the training data to address class imbalance.



Random Forest achieved the strongest overall result, with 99.45% accuracy, 99.52% recall, and a 0.9997 ROC-AUC score. The results also showed that TF-IDF provided most of the predictive value, while email length gave a smaller improvement for selected models.



\## Google Colab



\[Open the research notebook in Google Colab](https://colab.research.google.com/github/stevensukmadjaja/phising-email-classification/blob/main/Research%20Code%20-%20Kelompok%2016%20-%20LC01.ipynb)



\## Tools



Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, imbalanced-learn, and Google Colab.



\## Author



Nickholas Steven Sukmadjaja  

Computer Science Department, Bina Nusantara University

