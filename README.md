# Extrovert-introvert prediction 🧠🔍

A supervised ML project focused on predicting personality type (introvert or extrovert) using various social and behavioral features, trained with XGBoost.

---

📌 **Problem Statement**  
Understanding whether a person is an introvert or extrovert based on behavioral data can help in personalized recommendations, social planning, and psychological insights.

---

📁 **Project Steps**

- **Data Preprocessing**  
  Loaded and explored the dataset.  
  Cleaned column names and handled missing values with personalized imputation based on personality type.

- **Feature Engineering**  
  Converted categorical variables to numeric labels.  
  Visualized distributions by personality type.

- **Model Training**  
  Used XGBoost classifier with label encoding.  
  Split data into training and validation sets.

- **Model Evaluation**  
  Evaluated using:  
  - Accuracy  
  - Classification Report (Precision, Recall, F1-Score)  
  - Cross-Validation Accuracy  

---

📊 **Dataset**  
The dataset contains personality-labeled records with features such as:

- Drained after socializing (Yes/No)  
- Stage fear (Yes/No)  
- Time spent alone  
- Social event attendance  
- Going outside frequency  
- Friends circle size  
- Post frequency  
- Personality label (introvert/extrovert)

---

🧠 **Handling Missing Values**  
Missing values were filled using probability-based imputation informed by the personality class distribution for categorical features, and random uniform distributions for numeric features.

---

📈 **Final Model Performance**  
After training and cross-validation:

- Validation Accuracy: ~95%  
- Classification report shows balanced precision and recall between introverts and extroverts.

Cross-validation confirms model robustness with an average accuracy around 95%.

---

🛠️ **Tools Used**

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- scikit-learn  
- XGBoost  
- Google Colab / Jupyter Notebook

---

🗂️ **File Structure**

📬 **Contact**  
For questions or collaboration:

Mohamed Tamer  
[LinkedIn](www.linkedin.com/in/mohamed-tamer-673ba82a9
)  
mohamedtamerr04@gmail.com

