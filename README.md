## 📌 Project Title:
**Exploratory Data Analysis and Machine Learning on Lung Cancer Dataset**

---

## 📝 Project Description:
This project aims to perform an in-depth **Exploratory Data Analysis (EDA)** on a lung cancer dataset to uncover patterns, relationships, and insights that may contribute to better understanding of the factors associated with lung cancer occurrence.

Additionally, machine learning models are built to predict the likelihood of lung cancer based on the dataset features, demonstrating practical applications of the analysis.

---

## 📂 Dataset Information:

- **File Name**: `Lung cancer data.xlsx`
- **Source**: Provided for academic purposes.
- **Description**: This dataset contains information about various symptoms and behavioral patterns of individuals and their corresponding lung cancer status.

### 📊 Columns Description:
| Column Name | Description |
|-------------|-------------|
| `GENDER` | Gender of the individual (Male/Female) |
| `AGE` | Age in years |
| `SMOKING` | Smoking habit (Yes/No) |
| `YELLOW_FINGERS` | Presence of yellow fingers due to smoking (Yes/No) |
| `ANXIETY` | Anxiety level (Yes/No) |
| `PEER_PRESSURE` | Influence from peers (Yes/No) |
| `CHRONIC DISEASE` | Existing chronic disease (Yes/No) |
| `FATIGUE` | Fatigue level (Yes/No) |
| `ALLERGY` | Presence of allergies (Yes/No) |
| `WHEEZING` | Wheezing occurrence (Yes/No) |
| `ALCOHOL CONSUMING` | Alcohol consumption (Yes/No) |
| `COUGHING` | Frequency of coughing (Yes/No) |
| `SHORTNESS OF BREATH` | Presence of shortness of breath (Yes/No) |
| `SWALLOWING DIFFICULTY` | Difficulty while swallowing (Yes/No) |
| `CHEST PAIN` | Presence of chest pain (Yes/No) |
| `LUNG_CANCER` | Lung cancer status (Yes/No) |

---

## ⚙️ Technologies Used:

- **Python 3**
- **Jupyter Notebook**
- **Pandas** (Data manipulation)
- **NumPy** (Numerical computation)
- **Matplotlib / Seaborn** (Visualization)
- **Scikit-learn** (Machine Learning)

---

## 🔍 EDA Process Overview:

1. **Data Loading**: Loaded the Excel file using Pandas.
2. **Data Inspection**: 
   - Checked shape, data types, and initial rows.
   - Verified missing values.
3. **Data Cleaning**: 
   - Converted categorical features.
   - Handled any inconsistencies or typos if found.
4. **Univariate Analysis**:
   - Plotted bar charts, countplots for categorical features.
   - Histogram for age distribution.
5. **Bivariate Analysis**:
   - Cross-tabulation between features and lung cancer status.
   - Heatmap to show feature correlation.
6. **Multivariate Analysis**:
   - Pairplots and correlation matrices to check feature relationships.
7. **Insights and Observations**:
   - Smoking, alcohol, yellow fingers, fatigue, and wheezing show strong association with lung cancer.
   - Certain symptoms like chest pain and coughing are more frequent in lung cancer patients.

---

## 🤖 Machine Learning Model Building:

1. **Data Preprocessing:**
   - Encoding categorical variables.
   - Splitting the data into training and testing sets.

2. **Model Training:**
   - **Logistic Regression** used as baseline classifier.
   - **Random Forest Classifier** applied for better performance.

3. **Evaluation Metrics:**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

4. **Results:**
   - Logistic Regression Accuracy

---

## 📌 Key Findings:

- Majority of lung cancer cases are associated with **fatigue, yellow fingers, and alcohol consumption**.
- Features like **wheezing, coughing, and chest pain** appear prominently in positive lung cancer cases.

---

