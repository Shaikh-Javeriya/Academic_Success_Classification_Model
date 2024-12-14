# Academic Success Classification Model

## Overview
Welcome to the 2024 Kaggle Playground Series! This repository showcases the end-to-end pipeline for predicting academic risk in higher education students, leveraging a clean and comprehensive machine learning approach.

This project aims to classify students into categories (`Graduate`, `Dropout`, or `Enrolled`) based on their academic, demographic, and socioeconomic data.

---

## **Goal**
To predict the academic risk of students in higher education and submit predictions with the highest possible accuracy, evaluated using the **accuracy score**.

---

## **Repository Structure**
The repository is organized into the following directories:

### 1. **Project_Documents**
Contains textual documents describing the dataset, columns, and project overview:
- `Column_names.txt`: Describes the columns in the dataset.
- `Dataset_Description.txt`: Provides details about the dataset.
- `ProjectOverview.txt`: Summarizes the project goals and objectives.

### 2. **Data Files**
Contains the raw dataset and submission template:
- `train.csv`: Training dataset with labeled data.
- `test.csv`: Test dataset without labels.
- `sample_submission.csv`: Submission format example.

### 3. **Understanding_Data**
Contains Jupyter notebooks and documents for understanding the dataset:
- `Academic_Success_UnderstandingData.ipynb`: Notebook exploring the dataset structure.
- `Academic_Success_UnderstandingData.pdf`: PDF version of the notebook.
- `Analysis of Training and Test Data.docx`: Detailed analysis summary of the dataset.

### 4. **Exploratory_Data_Analysis**
Contains visualizations and insights derived during EDA:
- `Academic_Success_EDA.ipynb`: Notebook showcasing exploratory data analysis.
- `Academic_Success_EDA.pdf`: PDF version of the EDA notebook.
- `Exploratory Data Analysis for Academic Success Classification Model.docx`: Comprehensive EDA analysis document.

### 5. **Predictive_Modeling**
Contains the predictive modeling workflow, results, and submissions:
- `Academic_Success_Classification_Model.ipynb`: Notebook implementing CatBoost, XGBoost, and HistGradientBoostingClassifier.
- `Academic_Success_Classification_Model.pdf`: PDF version of the notebook.
- `Predictive Modeling Analysis for Academic Success Classification Model.docx`: Detailed analysis of model performances and insights.
- `submission.csv`: Final submission file with predicted labels.

---

## **Evaluation**
Submissions are evaluated using the **accuracy score**. For each `id` row in the test set, the predicted `Target` (categorical academic risk assessment) is required. The submission format must include a header:

```csv
id,Target
76518,Graduate
76519,Graduate
76520,Graduate
```

---

## **Technologies and Tools Used**
- **Python Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, CatBoost, XGBoost
- **Data Visualization**: Seaborn and Matplotlib
- **Machine Learning Models**: CatBoost, XGBoost, and HistGradientBoostingClassifier
- **Jupyter Notebooks**: Used for data exploration, EDA, and modeling
- **Documentation**: Microsoft Word for detailed explanations

---

## **Key Steps in the Pipeline**
1. **Understanding Data**:
   - Dataset overview and distribution analysis.
   - Observed class imbalance and ensured no missing values.

2. **Exploratory Data Analysis**:
   - Visualized trends and relationships in features such as `Gender`, `Course`, `Grades`, `Parental Occupation`, `GDP`, and `Inflation Rate`.
   - Derived insights to support feature engineering and predictive modeling.

3. **Predictive Modeling**:
   - Implemented CatBoost, XGBoost, and HistGradientBoostingClassifier.
   - Evaluated models on validation data using accuracy, precision, recall, and F1-score.
   - Selected **CatBoost** as the best-performing model with an accuracy of 83.11%.

4. **Submission**:
   - Generated predictions for the test set using the selected model.
   - Prepared the final `submission.csv` file.

---

## **Instructions for Use**
1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/Academic_Success_Classification_Model.git
   ```

2. Navigate to the directory:
   ```bash
   cd Academic_Success_Classification_Model
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Explore the notebooks:
   - Open `Understanding_Data/Academic_Success_UnderstandingData.ipynb` for dataset analysis.
   - Open `Exploratory_Data_Analysis/Academic_Success_EDA.ipynb` for EDA insights.
   - Open `Predictive_Modeling/Academic_Success_Classification_Model.ipynb` for modeling workflows.

5. Generate predictions:
   - Run the `Predictive_Modeling/Academic_Success_Classification_Model.ipynb` notebook.
   - Save predictions in `submission.csv` format.

---

## **Conclusion**
This repository provides a comprehensive framework for analyzing academic risk in higher education. The approach integrates data understanding, EDA, and state-of-the-art machine learning techniques to deliver actionable insights and accurate predictions.

Feel free to explore the repository, and contributions are welcome to enhance this project further!

---

## **Author**
**Javeriya Shaikh**
- linkedin: [Your Kaggle Profile](https://kaggle.com/yourprofile)
- GitHub: [Your GitHub Profile](https://github.com/your_username)

For any questions or suggestions, feel free to reach out!

