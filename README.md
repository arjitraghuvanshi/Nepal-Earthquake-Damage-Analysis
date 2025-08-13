# Nepal Earthquake Damage Analysis

## 📌 Overview
This project analyzes and predicts building damage from the **2015 Nepal Earthquake** using real-world post-disaster survey data.  
It demonstrates **data wrangling**, **exploratory data analysis (EDA)**, and **machine learning modeling** with **Logistic Regression** and **Decision Trees**.

The project is organized into four Jupyter notebooks, each covering a different stage of the workflow.

---

## 📂 Project Structure

1. **`Data Wrangling with SQLite.ipynb`**
   - Loads and queries the raw Nepal Earthquake data using **SQLite**.
   - Performs table joins and extracts relevant features.
   - Cleans and structures the dataset for analysis.

2. **`Earthquake Damage in Kavrepalanchok.ipynb`**
   - Focuses on damage patterns in the Kavrepalanchok district.
   - Performs EDA with visualizations (histograms, bar charts, and heatmaps).
   - Identifies key factors correlated with damage severity.

3. **`Predicting Damage with Decision Tree.ipynb`**
   - Implements a **Decision Tree Classifier** for prediction.
   - Tunes hyperparameters (max depth, random state) for optimal performance.
   - Compares results with Logistic Regression.

4. ***`Predicting Damage with Logistic Regression.ipynb`**
   - Prepares the dataset with encoding and scaling.
   - Trains a **Logistic Regression** model to predict building damage levels.
   - Evaluates the model with accuracy, confusion matrix, and classification report.

---

## 🛠️ Tech Stack & Skills Demonstrated
- **Languages:** Python, SQL
- **Libraries & Tools:** 
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn` (Logistic Regression, Decision Tree Classifier, preprocessing)
  - `sqlite3`, `ipython-sql`
- **Data Skills:**
  - Data wrangling & cleaning
  - Exploratory Data Analysis (EDA)
  - Feature engineering
- **Machine Learning Skills:**
  - Classification modeling
  - Model evaluation (accuracy, precision, recall, F1-score)
  - Model interpretability
- **Other Skills:**
  - Writing clean, well-documented Jupyter notebooks
  - Reproducible analysis workflow

---

## 📊 Dataset
The dataset originates from post-earthquake surveys conducted in Nepal after the **2015 Gorkha earthquake**.  
It contains details about building structure, location, and observed damage level.


---

## 🚀 Results & Insights
- Both **Logistic Regression** and **Decision Tree** models were able to predict building damage levels with reasonable accuracy.
- Structural features (such as foundation type, building height, and roof material) had strong predictive power.
- The **Decision Tree** provided better interpretability, while Logistic Regression offered a more stable baseline.

---

## 📬 Author  
**Arjit Raghuvanshi**  
Data analytics, Data Science & Machine Learning Enthusiast  
[GitHub Profile](https://github.com/arjitraghuvanshi)  

