# -hack-Club-DA-Final-Project

# 📊 GPA and Lifestyle Analysis Using Python & Google Colab

This project explores the relationship between **GPA** and various lifestyle factors such as **exercise frequency** and **income levels**, using data visualization and statistical analysis techniques. The analysis was conducted in **Google Colab** using Python libraries like `pandas`, `seaborn`, and `matplotlib`.

---

## 📁 Dataset

The dataset used: `food_coded.csv`, uploaded via Google Colab.

---

## 🔧 Tools and Libraries

* Python 3
* Google Colab
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`

---

## 🧹 Data Cleaning Steps

* Replaced incorrect or placeholder entries (e.g., `"JA"`) with `NaN`.
* Handled missing values by filling them with 0 (note: see limitations).
* Removed duplicate entries.
* Converted relevant columns to appropriate data types (e.g., `float`, `category`).
* Recoded gender labels for clarity.

---

## 🔬 Research Questions

### 1. **Does a healthy lifestyle affect GPA?**

* Analyzed the relationship between **exercise frequency** and **GPA** using a bar plot.
* Found a positive visual trend: students who exercise more tend to have slightly higher GPAs.

### 2. **Is there a correlation between income and GPA?**

* Binned income into ranges and compared GPA scores.
* A heatmap of correlation values revealed a **moderate positive relationship** between **income** and **GPA**.

---

## 📊 Visualizations

* **Bar Plot:** GPA vs. Exercise Frequency
* **Heatmap:** Correlation between GPA and Income
* **Histograms:** Distribution of GPA and Income

> All visualizations were created using `matplotlib` and `seaborn` for clarity and aesthetics.

---

## 📌 Key Findings

1. **Exercise frequency** appears to positively correlate with higher GPA.
2. **Income** shows a moderate relationship with GPA; middle-income students tend to score higher.
3. Additional factors (e.g., diet, sleep, social support) might further explain GPA variation.

---

## 📈 Recommendations for Future Work

* Analyze the effect of **dietary habits** (fruit, soda, fast food) on GPA.
* Include **sleep duration** and **mental well-being** as variables.
* Perform a **multivariable regression analysis** to refine conclusions.

---

## ⚠️ Limitations

* **Missing values** were replaced with 0, potentially introducing bias.
* **Self-reported data** (e.g., GPA, exercise) may be unreliable.
* **Sample-specific data** limits generalization across diverse populations.

---

## ✅ How to Run

1. Open the notebook in **Google Colab**.
2. Upload `food_coded.csv` when prompted.
3. Run each cell step-by-step to follow the analysis pipeline and view visualizations.

---

## 📜 License

This project is for educational and research purposes. No commercial use is permitted without explicit consent.
