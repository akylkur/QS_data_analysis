# 🎓 QS World Top 1500 Universities Analysis (2026)

## 📌 Project Overview
This project is an **Exploratory Data Analysis (EDA)** of the QS World University Rankings 2026. It explores global academic trends, institutional performance, and regional dominance across 1,500+ universities.

---

## 📊 Dataset Information
The dataset is sourced from [Kaggle](https://www.kaggle.com/code/akylkurmanaliev/qs-world-top-1500-universities/notebook).

* **File name:** `2026_QS_World_University_Rankings.csv`
* **Institutions:** 1,500+
* **Key Metrics:** Academic Reputation, Employer Reputation, Faculty-Student Ratio, and Sustainability.

---

## 🚀 How to Run the Project

### **Step 1: Download the Data**
Before running the analysis, you must have the dataset. 
1. Download `2026_QS_World_University_Rankings.csv` from this repository.
2. If running locally, ensure this file is placed in the **same folder** as your notebook.

### **Option 1: Google Colab (Recommended)**
1. Open [Google Colab](https://colab.research.google.com/).
2. Click on the **GitHub** tab and paste the link to this repository.
3. Open `QS_world_top_1500_universities.ipynb`.
4. **Important:** Upload the `.csv` file to the Colab session storage (folder icon on the left) OR use the **Raw GitHub Link** to load it directly:

```python
import pandas as pd
# Replace with your actual username
url = '[https://raw.githubusercontent.com/YOUR_USERNAME/QS_data_analysis/main/2026_QS_World_University_Rankings.csv](https://raw.githubusercontent.com/YOUR_USERNAME/QS_data_analysis/main/2026_QS_World_University_Rankings.csv)'
df = pd.read_csv(url)
