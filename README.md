
# 🏡 Min-Max Normalization Workshop

## 📘 Course: Foundations of Machine Learning Programming
**Lab:** Manual Normalization and Feature Scaling  
**Team Number:** 7  
**Team Members:**  
- Krishna  
- Fenil  
- Preetpal  

---

##  Project Overview

This project applies **Min-Max normalization** manually to a real housing dataset to prepare it for machine learning models.  
It includes:

- Data loading and inspection  
- Quality checks (missing values, duplicates, zeroes)  
- Outlier detection  
- Manual normalization using formula  
- Side-by-side visual and numeric comparisons  
- Final conclusion with real-world ML context  

---

##  Why Normalize?

Features like `Price`, `Area`, and `Lot_Size` have large numeric ranges, while others like `Num_Bedrooms` range from 1–5.  
This imbalance can confuse models like:

- K-Nearest Neighbors (distance-based)
- Linear Regression (gradient updates)
- Neural Networks (activation impact)

 **Min-Max normalization** ensures fair contribution from each feature by scaling everything between 0 and 1.

---

##  Technologies Used

- Python 3  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

##  Folder Structure

```
min-max-normalization-workshop/
│
├── data/
│   └── housing_data.csv
│
├── MinMax_Normalization_Workshop.ipynb
├── README.md
└── requirements.txt  (optional)
```

---

## ▶ Running the Project

1. Clone the repo:
   ```bash
   git clone https://github.com/kittuai/min-max-normalization-workshop.git
   cd min-max-normalization-workshop
   ```

2. (Optional) Create virtual environment:
   ```bash
   python -m venv env
   env\Scripts\activate  # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the notebook:
   ```bash
   jupyter notebook
   ```

---

##  Output Highlights

- Manual normalization formula applied
- Visual comparison before and after
- Data integrity maintained
- Outliers analyzed but preserved
- Ready for next ML steps

---

##  Conclusion

This clean preprocessing step ensures **machine learning models** perform efficiently without being biased toward high-magnitude features.  
The dataset is now ready for:

- KNN
- Regression models
- Deep learning

---

## 🔗 GitHub Repo

[https://github.com/kittuai/min-max-normalization-workshop](https://github.com/kittuai/min-max-normalization-workshop)
