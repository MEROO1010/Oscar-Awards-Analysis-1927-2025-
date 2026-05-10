# 🎬 Oscar Awards Analysis (1927–2025)

---

## **📌 About the Project**

This project analyzes **98 years of Academy Awards (Oscars) data** to uncover trends, biases, and patterns in the film industry. It includes:

- **Data Cleaning**: Handling missing values, duplicates, and inconsistencies.
- **Exploratory Data Analysis (EDA)**: Visualizations to explore trends in categories, years, and films.
- **Machine Learning**: Predicting award winners based on nominations, categories, and release years.

Perfect for **data analysis portfolios** or showcasing skills in **Python, Pandas, and Scikit-learn**.

---

---

## **📂 Project Structure**

```
oscar-analysis/
├── data/
│   ├── the_oscar_award.csv      # Raw dataset from Kaggle
│   └── oscar_cleaned.csv        # Cleaned dataset (auto-generated)
├── notebooks/
│   └── oscar_analysis.ipynb     # Jupyter Notebook with full analysis
└── README.md                    # This file
```

---

## **📊 Dataset**

- **Source**: [Kaggle - The Oscar Award (1927–2025)](https://www.kaggle.com/code/ulrikeherold/the-oscar-award-1927-2025-all-about-movies)
- **Key Columns**:
  - `year_film`: Year the film was released.
  - `year_ceremony`: Year the ceremony was held.
  - `category`: Award category (e.g., Best Picture, Best Actor).
  - `film`: Title of the film.
  - `winner`: Whether the nominee won (1 = Yes, 0 = No).

---

## **🛠️ Tools & Libraries**


| Tool         | Purpose                          |
| ------------ | -------------------------------- |
| Python 3.10+ | Programming language             |
| Pandas       | Data cleaning and manipulation   |
| NumPy        | Numerical operations             |
| Matplotlib   | Static visualizations            |
| Seaborn      | Statistical visualizations       |
| Scikit-learn | Machine learning models          |
| Jupyter      | Interactive notebook environment |


---

## **🚀 How to Run the Project**

### **1. Set Up Your Environment**

#### **Option A: Using Anaconda (Recommended)**

1. Install [Anaconda](https://www.anaconda.com/products/distribution).
2. Open **Anaconda Prompt** and run:
  ```bash
   conda create -n oscar_env python=3.10 -y
   conda activate oscar_env
   conda install numpy=1.23.5 pandas=1.5.3 matplotlib seaborn scikit-learn jupyter -y
  ```

#### **Option B: Using pip**

1. Install Python 3.10+ from [python.org](https://www.python.org/downloads/).
2. Open a terminal and run:
  ```bash
   pip install numpy==1.23.5 pandas==1.5.3 matplotlib seaborn scikit-learn jupyter
  ```

---

### **2. Download the Dataset**

1. Download `the_oscar_award.csv` from [Kaggle](https://www.kaggle.com/code/ulrikeherold/the-oscar-award-1927-2025-all-about-movies).
2. Save it in the `data/` folder of your project.

---

### **3. Run the Jupyter Notebook**

1. Navigate to your project directory:
  ```bash
   cd path/to/oscar-analysis
  ```
2. Launch Jupyter Notebook:
  ```bash
   jupyter notebook
  ```
3. Open `notebooks/oscar_analysis.ipynb` and run the cells in order.

---

## **📈 Key Findings**

Here’s what the analysis reveals:

1. **Most Awarded Categories**:
  - **Best Picture**, **Best Actor**, and **Best Actress** dominate the awards.
2. **Trends Over Time**:
  - The number of awards per year has grown, reflecting the expansion of the film industry.
3. **Winner Distribution**:
  - Only a small percentage of nominees win, highlighting the competitiveness of the Oscars.
4. **Predictive Model**:
  - A **Random Forest Classifier** predicts winners with **~68% accuracy** (replace with your actual result) based on nominations, category, and release year.

---

## **📁 File Descriptions**


| File/Folder  | Description                              |
| ------------ | ---------------------------------------- |
| `data/`      | Contains raw and cleaned datasets.       |
| `notebooks/` | Jupyter Notebook with all analysis code. |
| `README.md`  | Project documentation (this file).       |


---

## **🔧 Troubleshooting**


| Issue                           | Solution                                                                                   |
| ------------------------------- | ------------------------------------------------------------------------------------------ |
| **FileNotFoundError**           | Ensure `the_oscar_award.csv` is in the `data/` folder.                                     |
| **Binary Incompatibility**      | Use compatible versions: `numpy=1.23.5`, `pandas=1.5.3`.                                   |
| **Missing Columns**             | Update the notebook to use the correct column names (e.g., `year_film` instead of `year`). |
| **Jupyter Notebook Won’t Open** | Ensure Jupyter is installed (`pip install jupyter` or `conda install jupyter`).            |


---

## **📜 License**

This project is open-source under the **[MIT License](LICENSE)**.

---

## **🙏 Acknowledgments**

- Data provided by [Kaggle](https://www.kaggle.com/).
- Inspired by the global community of data analysts and film enthusiasts.
