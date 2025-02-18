# Combined Cycle Power Plant Data Analysis

This repository contains a Jupyter Notebook (`Combined_cycle_Power_Plant.ipynb`) that performs an analysis on the **Combined Cycle Power Plant dataset**. The dataset is fetched from the **UCI Machine Learning Repository** and includes various features related to power plant operations.

---

## 📂 Dataset Description

The dataset contains **9568 data points** collected from a Combined Cycle Power Plant over **6 years (2006-2011)**. The features include:

1. **AT (Ambient Temperature)**: Hourly average ambient temperature (1.81°C to 37.11°C).
2. **V (Exhaust Vacuum)**: Hourly average exhaust vacuum pressure (25.36-81.56 cm Hg).
3. **AP (Ambient Pressure)**: Hourly average ambient pressure (992.89-1033.30 milibar).
4. **RH (Relative Humidity)**: Hourly average relative humidity (25.56% to 100.16%).
5. **PE (Net hourly electrical energy output)**: Net hourly energy output (420.26-495.76 MW).

---

## 📑 Notebook Overview

The notebook performs the following tasks:

1. **Data Download**: The dataset is fetched using the `ucimlrepo` package.
2. **Data Exploration**: The dataset is explored to understand its structure and features.
3. **Pairwise Scatterplots**: Scatterplots are created to visualize the relationships between the predictors and the target variable.
4. **Model Training and Evaluation**: Various machine learning models are trained and evaluated using **R² score, Mean Absolute Error (MAE), and Mean Squared Error (MSE)**.
5. **Data Visualization**: Data distributions and relationships are explored using `matplotlib` and `seaborn`.

---

## 🔧 Requirements

To run the notebook, you need the following Python libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `statsmodels`
- `ucimlrepo`

### **Installation**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn statsmodels ucimlrepo
```

---

## 🚀 Usage

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/combined-cycle-power-plant-analysis.git
```

### **2️⃣ Navigate to the Repository Directory**
```bash
cd combined-cycle-power-plant-analysis
```

### **3️⃣ Open the Jupyter Notebook**
```bash
jupyter notebook Combined_cycle_Power_Plant.ipynb
```
Run the cells in the notebook to perform the analysis.

---

## 📜 License

This project is licensed under the **MIT License**. See the **LICENSE** file for details.

---

## 🙌 Acknowledgments

- The dataset is sourced from the **UCI Machine Learning Repository**.
- The analysis is based on the work by **Pinar Tüfekci and Heysem Kaya**.

---

## 📬 Contact

For any **questions** or **suggestions**, please feel free to **open an issue** or contact the repository owner.

📌 _If you find this project useful, please ⭐ star the repository to support it!_
