# 🌍 Attitudes on Climate Change & Air Quality in European Cities

## 📌 Project Overview
This project analyzes **public attitudes toward climate change and air quality** across major European cities using survey data.  
The analysis aims to uncover **regional patterns**, identify **clusters of cities with similar perceptions**, and highlight the **socioeconomic and environmental factors** shaping public opinion.

---

## 🗂 Repository Structure
```
├── data/
│   └── climate_attitudes.csv   # Source dataset (or link to source)
├── notebooks/
│   └── Analysis.ipynb          # Data cleaning, EDA, clustering
├── docs/
│   └── cities_cluster_plot.png # Example visualization
├── report.pdf                  # Final summary report
└── requirements.txt            # Python dependencies
```

---

## 🔍 Analysis Steps

1. **Data Preparation**  
   - Load survey dataset and handle missing values  
   - Encode categorical variables  
   - Normalize features for clustering

2. **Exploratory Data Analysis**  
   - Regional breakdown of attitudes  
   - Correlation between attitudes and socioeconomic indicators  
   - Distribution of responses by city

3. **Clustering**  
   - Apply **K-Means** and compare different numbers of clusters  
   - Visualize city clusters in 2D using PCA

4. **Insights & Interpretation**  
   - Compare clusters by region, education level, and air quality index  
   - Identify high-concern vs low-concern city groups

---

## 📊 Key Insights
| Theme                  | Insight |
|----------------------|---------|
| Regional Variation   | Northern & Western Europe show higher concern levels than Eastern Europe. |
| Air Quality Perception | Strong correlation with measured PM2.5 pollution levels. |
| Socioeconomic Factors | Higher education levels → greater climate change concern. |

---


---

## 🛠 How to Run Locally

### 1. Clone this repository
```bash
git clone https://github.com/Mahmudul-Hasan-24/Attitudes-on-Climate-Change.git
cd Attitudes-on-Climate-Change
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook notebooks/Analysis.ipynb
```

---

## 📦 Dependencies
- pandas – Data manipulation  
- numpy – Numerical operations  
- matplotlib, seaborn – Data visualization  
- scikit-learn – Clustering and PCA  
- jupyter – Notebook interface  

---

## 🚀 Future Improvements
- Add **time-series data** to analyze change over multiple years.  
- Integrate **real-time air quality data** from APIs.  
- Deploy **interactive dashboard** using Streamlit or Power BI.

---

## 📜 License
This project is licensed under the MIT License – see [LICENSE](LICENSE) for details.

---

## 👤 Author
**Mahmudul Hasan**  
Master’s Computational Social System (Business Analytics) – Technical University of Graz and University of Graz
