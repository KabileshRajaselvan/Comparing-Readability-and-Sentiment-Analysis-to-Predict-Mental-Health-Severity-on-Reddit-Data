
# 📊 Exploratory Data Analysis (EDA) for Comparing Readability and Sentiment Analysis to Predict Mental Health Severity on Reddit Data
**Author:** A. Kabilesh Rajaselvan  
**Reg. No:** 21MIA1132  
**Institution:** VIT Chennai – SCOPE School  

---

## 🧠 Objective  
To perform comprehensive Exploratory Data Analysis (EDA) using R to understand data distributions, detect missing values, identify outliers, visualize relationships between variables, and generate insights for informed decision-making.

---

## 🎯 Key Concepts  

- Data Cleaning and Pre-processing  
- Descriptive Statistics  
- Data Visualization  
- Correlation Analysis  
- Handling Missing Values  
- Outlier Detection  

---

## 🛠️ Tools & Libraries Used  

- **R**
- **RStudio**
- **tidyverse**
- **ggplot2**
- **dplyr**
- **corrplot**
- **skimr**
- **readr**
- **ggcorrplot**
- **knitr**

---

## 📁 File Structure  

📦 EDA_Project  
 ┣ 📜 eda.Rmd   # Main R Markdown notebook for EDA  
 ┗ 📜 README.md            # Project documentation  

---

## 🚀 How to Run  

1️⃣ **Clone the repository:**  
```bash
git clone https://github.com/yourusername/EDA_Project.git
cd EDA_Project
```

2️⃣ **Install Dependencies in R:**  
```R
install.packages(c("tidyverse", "ggplot2", "dplyr", "readr", "corrplot", "skimr", "ggcorrplot", "knitr"))
```

3️⃣ **Open the RMarkdown file:**  
- Open `final_try_eda.Rmd` in **RStudio**

4️⃣ **Run the EDA Report:**  
- Click `Knit` to render the analysis report in **HTML** or **PDF** format  
OR  
- Run the code chunk by chunk to observe results interactively  

---

## 🔍 Implementation Overview  

- **Load Dataset:** Read dataset into R using `readr`  
- **Data Cleaning:** Handle missing values, check data types  
- **Descriptive Statistics:** Use `summary()` and `skim()` for variable summaries  
- **Visualizations:**  
  - Histograms for distribution  
  - Boxplots for outlier detection  
  - Correlation matrices with `corrplot` and `ggcorrplot`  
- **Insights Generation:** Identify trends, relationships, and data quality issues  

---

## 🧪 Output  

- Cleaned dataset  
- Summary tables  
- Various plots: histograms, boxplots, scatterplots, correlation heatmaps  
- EDA insights for further analysis or modeling  

---

## 💡 Applications  

- Initial data understanding in any data science project  
- Feature engineering guidance  
- Data quality assessment  
- Preparing reports for stakeholders  

---

## 📝 Notes  

- Ensure all R packages are installed before running the notebook  
- Customize file paths in the RMarkdown if needed  
- Large datasets may require increased memory or processing time  
- For more advanced EDA, consider using `DataExplorer` or `inspectdf` packages  
