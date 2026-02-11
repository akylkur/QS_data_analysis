# 🎓 QS World Top 1500 Universities Analysis (2026)

## 📌 Project Overview
This project is an **Exploratory Data Analysis (EDA)** of the QS World University Rankings 2026. It explores global academic trends, institutional performance, and regional dominance across 1,500+ universities.

---

## 📊 Dataset Information
The dataset is sourced from [Kaggle](https://www.kaggle.com/code/akylkurmanaliev/qs-world-top-1500-universities/notebook).

* **Institutions:** 1,500+
* **Key Metrics:** * Academic & Employer Reputation
    * Faculty-Student Ratio
    * Citations per Faculty
    * International Faculty/Student Ratio
    * Sustainability Scores

---

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:**
    * `Pandas`: Data manipulation
    * `Matplotlib` & `Seaborn`: Data visualization
    * `NumPy`: Numerical analysis

---

## 🚀 How to Run the Project

### **Option 1: Google Colab (Recommended)**
1. Open [Google Colab](https://colab.research.google.com/).
2. Click on the **GitHub** tab and paste the link to this repository.
3. Open `QS_world_top_1500_universities.ipynb`.
4. Use the **Raw GitHub Link** to load the data directly:

```python
import pandas as pd
url = '[https://raw.githubusercontent.com/YOUR_USERNAME/QS_data_analysis/main/2026_QS_World_University_Rankings.csv](https://raw.githubusercontent.com/YOUR_USERNAME/QS_data_analysis/main/2026_QS_World_University_Rankings.csv)'
df = pd.read_csv(url)
