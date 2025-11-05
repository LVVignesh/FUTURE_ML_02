🧠 FUTURE_ML_02 – Churn Prediction System  
🚀 Future Interns Machine Learning Internship Task 2  

---

📄 **About the Project**  

This project is part of the Future Interns Machine Learning Internship (Task 2).  
The goal is to develop a **Customer Churn Prediction System** that identifies customers who are likely to stop using a service.  
Customer retention is a major business priority, and churn prediction helps companies take proactive actions to retain users.

---

🎯 **Objective**  

- Build a machine learning model that predicts the probability of customer churn.  
- Visualize key churn factors through a **data-driven dashboard** using Matplotlib.  
- (Optional) Provide an **interactive interface** using **Streamlit or Gradio** for live predictions.

---

🧰 **Tools & Technologies Used**  

- 🐍 Python – Core programming language  
- 🧮 Pandas & NumPy – Data analysis and preprocessing  
- ⚙️ Scikit-learn – Model training and evaluation  
- 🌲 XGBoost & RandomForest – Advanced classification models  
- 📊 Matplotlib – Visualization and dashboard creation  
- 🌐 Streamlit / Gradio – Interactive web app for live predictions  

---

📁 **Dataset**  

- **Telco Customer Churn Dataset** – (Kaggle / Provided by Future Interns)  
- Contains customer demographics, account details, and service usage patterns to predict churn behavior.

---

🧹 **Steps Performed**  

1. **Data Exploration & Cleaning**  
   - Handled missing values in `TotalCharges`  
   - Encoded target variable `Churn` (Yes = 1, No = 0)  
   - Dropped unnecessary columns like `customerID`  

2. **Feature Engineering**  
   - Separated numerical and categorical columns  
   - Applied scaling and one-hot encoding using `ColumnTransformer`  

3. **Model Training**  
   - Trained **Logistic Regression**, **Random Forest**, and **XGBoost** models  

4. **Model Evaluation**  
   - Compared **accuracy, precision, recall, F1-score, and ROC-AUC metrics**  
   - Generated **confusion matrix** and ROC curves  

5. **Visualization**  
   - Created a **4-in-1 Matplotlib dashboard** showing:  
     - Churn distribution  
     - Top feature importances  
     - ROC curve  
     - Confusion matrix  

6. **Prediction & Interactive App**  
   - Calculated **churn probabilities** for each customer record  
   - Built a **Streamlit/Gradio app** (`app.py` or notebook cell) to allow:  
     - Uploading customer data  
     - Viewing predicted churn probability  
     - Displaying feature importance and model insights interactively  

---

📈 **Results & Insights**  

- The **XGBoost model** achieved the best overall performance.  
- Key churn drivers included:  
  - Contract type  
  - Tenure length  
  - Monthly charges  
  - Internet service category  
- The Matplotlib dashboard summarizes all major metrics and visuals.  

---

🖼️ **Dashboard Preview**  

- `Churn_Dashboard_Matplotlib.png`  
- Provides a business-ready visualization summarizing churn insights and model results.  

---

🧩 **Deliverables**  

| File | Description |
|------|-------------|
| FUTURE_ML_02_ChurnPrediction.ipynb | Complete code notebook with Step 12 (interactive app included) |
| Churn_Dashboard_Matplotlib.png | Final dashboard visualization |
| churn_model.pkl | Trained model file |
| README.md | Project documentation |
| app.py *(optional if separated from notebook)* | Interactive Streamlit/Gradio app for live predictions |

---

👨‍💻 **Intern**  

Vignesh L V  
Machine Learning Intern – Future Interns  

📍 Task 2 – Churn Prediction System  
📧 contact@futureinterns.com | 🌐 [Future Interns](https://futureinterns.com)
