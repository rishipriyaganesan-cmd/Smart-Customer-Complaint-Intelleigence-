# Smart Customer Complaint Intelligence System

## 📌 Project Overview
The **Smart Customer Complaint Intelligence System** is a data analytics and machine learning project designed to analyse customer complaints, identify complaint categories, understand customer sentiment, and highlight high-priority issues.

The project combines Python, Natural Language Processing (NLP), Machine Learning, SQL, and Power BI to transform customer feedback into meaningful business insights.

## 🎯 Problem Statement
Businesses receive customer complaints through multiple channels. Manually analysing large volumes of feedback can be time-consuming and make it difficult to identify recurring issues, understand customer sentiment, and prioritise complaints.

This project explores how data analytics and text classification can help organise complaint data and support better decision-making.

## 🎯 Project Objectives
- Clean and analyse customer complaint data.
- Perform Exploratory Data Analysis (EDA).
- Process customer feedback using NLP techniques.
- Extract text features using TF-IDF.
- Classify complaint categories using Logistic Regression.
- Evaluate the classification model.
- Analyse complaint patterns using SQL.
- Build an interactive Power BI dashboard.
- Generate insights to support customer service improvements.

## 🛠️ Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **Python** | Data processing and analysis |
| **Pandas** | Data cleaning and manipulation |
| **NumPy** | Numerical operations |
| **Matplotlib** | Data visualisation |
| **Seaborn** | Statistical visualisation |
| **NLP** | Customer complaint text processing |
| **TF-IDF** | Text feature extraction |
| **Logistic Regression** | Complaint category classification |
| **Scikit-learn** | Model training and evaluation |
| **SQL / SQLite** | Querying and summarising complaint data |
| **Power BI** | Interactive dashboard and reporting |
| **Excel** | Dataset storage and reporting data source |
| **Google Colab** | Development environment |

## 📂 Project Workflow
1. **Data Collection**: Prepared a customer complaint dataset.
2. **Data Cleaning**: Checked missing values, duplicates, data types, and consistency.
3. **Exploratory Data Analysis**: Analysed complaint categories, customer ratings, products, channels, sentiment, and priority.
4. **Text Preprocessing**: Processed complaint text for analysis.
5. **Feature Extraction**: Used TF-IDF to convert text into numerical features.
6. **Model Training**: Trained a Logistic Regression classifier to predict complaint categories.
7. **Model Evaluation**: Evaluated the model using classification metrics and a confusion matrix.
8. **SQL Analysis**: Used SQL queries to analyse complaint counts, average ratings, priority levels, and complaint categories.
9. **Power BI Dashboard**: Created KPI cards, charts, and interactive filters to explore complaint patterns.
10. **Business Insights**: Interpreted the analysis to identify areas that may need customer service attention.

## 📊 Power BI Dashboard
The dashboard presents complaint information through:
- Total complaints
- Average customer rating
- High-priority complaints
- Negative complaints
- Complaints by category
- Customer sentiment distribution
- Complaint priority distribution
- Complaints by product and channel
- Average rating by category
- Interactive slicers for exploring the data

> **Dashboard screenshot**: Add your Power BI dashboard image to this repository and display it here.  
> To display an uploaded image named `dashboard.png`, use:  
> `![Power BI Dashboard](dashboard.png)`

## 🧠 Machine Learning Approach

### TF-IDF
TF-IDF (Term Frequency–Inverse Document Frequency) converts complaint text into numerical features that can be used by a machine learning model.

### Logistic Regression
Logistic Regression is used as a classification algorithm to predict the category of a customer complaint based on its text features.

### Model Evaluation
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

*The actual evaluation results should be documented after running the final version of the notebook.*

## 🗄️ SQL Analysis
SQL was used to answer business questions such as:
- Which complaint categories occur most frequently?
- What is the average rating for each category?
- How many complaints have high priority?
- Which products receive the most complaints?
- How are complaints distributed across channels?
- How many complaints have negative sentiment?

## 🌍 Real-World Applications
This project demonstrates a workflow that could support:
- Customer support teams in organising complaint data.
- Businesses in identifying recurring customer issues.
- Managers in monitoring negative feedback and ratings.
- Support teams in reviewing potentially urgent complaints.
- Analysts in preparing reports for data-driven decisions.

*The current implementation is a prototype. Predictions and priority rules should be validated before being used in a production customer support system.*

## 📚 Key Learnings
- Data cleaning and exploratory data analysis.
- Text preprocessing and feature extraction.
- Machine learning classification and evaluation.
- SQL querying and aggregation.
- Interactive dashboard development using Power BI.
- Translating analytical results into business insights.

## 🚀 Future Improvements
- Test the model on a larger, more representative dataset.
- Improve generalisation through better data quality and model validation.
- Develop a simple interface for entering new complaints.
- Automate complaint classification and priority assessment.
- Connect the dashboard to a regularly updated data source.
- Evaluate model performance on unseen, real-world complaints.

## 👩‍💻 Author
**Rishipriya Ganesan**  
B.Tech – Artificial Intelligence and Data Science  
Interested in Data Analytics, SQL, Python, Data Visualisation, and business insights.  
- **LinkedIn**: [https://www.linkedin.com/in/rishipriya-ganesan](https://www.linkedin.com/in/rishipriya-ganesan)  
- **GitHub**: [https://github.com/rishipriyaganesan-cmd](https://github.com/rishipriyaganesan-cmd)

⭐ *If you find this project interesting, feel free to explore the repository and share feedback.*