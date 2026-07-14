# Credit Card Approval Prediction using Machine Learning

## Project Documentation

---

## 1. Introduction

The Credit Card Approval Prediction System is a Machine Learning-based web application developed to predict whether a customer's credit card application will be approved or rejected. The system analyzes applicant information such as income, education, employment status, family status, and credit history to generate accurate predictions.

This project helps automate the traditional credit approval process, reducing manual effort and improving decision-making efficiency.

---

## 2. Problem Statement

Banks and financial institutions receive numerous credit card applications every day. Manual verification of these applications is time-consuming, expensive, and prone to human error. There is a need for an intelligent system that can quickly evaluate applications and assist in making reliable approval decisions.

---

## 3. Objectives

- Automate the credit card approval process.
- Improve prediction accuracy using Machine Learning.
- Reduce manual verification time.
- Develop a user-friendly web application.
- Provide quick and reliable approval predictions.

---

## 4. Scope

This project can be used by:

- Banks
- Financial Institutions
- Credit Card Companies
- Loan Processing Organizations

The system supports faster and more efficient decision-making while reducing operational workload.

---

## 5. Technologies Used

### Programming Language

- Python

### Machine Learning Libraries

- Scikit-learn
- Pandas
- NumPy
- Matplotlib

### Web Framework

- Flask

### Frontend

- HTML
- CSS
- Bootstrap

### Database

- SQLite

### Development Tools

- Jupyter Notebook
- Visual Studio Code
- Git & GitHub

---

## 6. Dataset

The project uses the **Application_Data.csv** dataset containing applicant information.

The dataset includes features such as:

- Gender
- Married Status
- Number of Dependents
- Education
- Self Employment
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area
- Loan Status

---

## 7. Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Model Saving
8. Flask Application Development
9. Prediction Generation

---

## 8. Machine Learning Process

### Data Collection

The dataset containing applicant information is collected for training and testing.

### Data Preprocessing

- Missing values are handled.
- Categorical values are encoded.
- Data is cleaned before model training.

### Model Training

Multiple Machine Learning algorithms are trained and evaluated to identify the best-performing model.

### Model Evaluation

Performance metrics are compared to select the most accurate model.

### Prediction

The trained model predicts whether the credit card application is approved or rejected.

---

## 9. Features

- Machine Learning based prediction
- User-friendly Flask interface
- Fast approval prediction
- High prediction accuracy
- Easy deployment
- Simple input form
- Instant prediction results

---

## 10. Advantages

- Reduces manual effort
- Saves processing time
- Improves decision consistency
- Easy to use
- Scalable solution
- Cost-effective

---

## 11. Limitations

- Prediction depends on dataset quality.
- Requires historical applicant data.
- Cannot replace human financial judgment completely.

---

## 12. Future Enhancements

- Cloud deployment
- Mobile application support
- Real-time database integration
- Explainable AI features
- Improved model accuracy
- API integration with banking systems

---

## 13. Project Structure

```
Credit-Card-Approval-Prediction-ML
│
├── .github
├── catboost_info
├── templates
├── tests
├── app.py
├── database_creation.py
├── retrain.py
├── test.py
├── Application_Data.csv
├── pipeline.pkl
├── backup_pipeline.pkl
├── credit_card_application.db
├── requirements.txt
├── Dockerfile
├── Credit Card Approval Prediction.ipynb
├── README.md
├── Documentation.md
└── LICENSE
```

---

## 14. Installation

Clone the repository:

```bash
git clone https://github.com/pavi15-koduru/Credit-Card-Approval-Prediction-ML.git
```

Navigate to the project folder:

```bash
cd Credit-Card-Approval-Prediction-ML
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open your browser:

```
http://127.0.0.1:5000/
```

---

## 15. Testing

- Launch the application.
- Enter applicant details.
- Submit the form.
- Verify the prediction result.
- Test different input combinations.

---

## 16. Results

The developed Machine Learning model successfully predicts whether a credit card application is approved or rejected. The Flask application provides an easy-to-use interface for entering applicant information and receiving instant predictions.

---

## 17. Conclusion

The Credit Card Approval Prediction System demonstrates how Machine Learning can improve the efficiency of the credit approval process. By automating application evaluation, the system reduces manual effort, speeds up decision-making, and assists financial institutions in making consistent and data-driven decisions.

---

## 18. References

- https://scikit-learn.org/
- https://flask.palletsprojects.com/
- https://pandas.pydata.org/
- https://numpy.org/
- https://www.python.org/

---


## Team Members

- Md Arshad (Team Lead)
- Koduru Pavithra
- Mudimelapu Parvathi
- Chirra Karthik Reddy
- Pranathi Karyamsetty


## 19. Author

**Koduru Pavithra**

B.Tech – Artificial Intelligence and Data Science

Kallam Haranadh Reddy Institute of Technology

GitHub: https://github.com/pavi15-koduru
