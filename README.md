# 🏃 Exploratory Data Analysis: Two Centuries of UM Races

This project performs an in-depth exploratory data analysis (EDA) on the **"Two Centuries of UM Races"** dataset. The dataset, originally published on Kaggle, spans more than 200 years (1798–2022) of ultramarathon events held globally, featuring over 7 million race records.

---

## 📌 Objectives
- Explore patterns and trends in ultramarathon participation and performance.
- Understand how race distance, gender, and age affect outcomes.
- Filter, clean, and transform raw data for insight extraction.
- Visualize and interpret performance metrics over time and geography.

---

## 🗃️ Dataset
**Source**: [Kaggle - Two Centuries of UM Races](https://www.kaggle.com/datasets/fatihyavuzz/two-centuries-of-um-races)

**Key Features:**
- Event date, name, country, distance
- Athlete age, gender, country, club
- Average speed, finish time, number of finishers

---

## 🔧 Operations Performed

### Data Preprocessing
- Removed unnecessary columns and null entries
- Handled duplicates and reset index
- Converted data types for analysis

### Feature Engineering
- Extracted **event country** from event names
- Calculated **athlete age** from birth year
- Parsed performance time and cleaned average speed

### Filtering
- Focused on races with distance `50km` or `50mi`
- Analyzed year `2020` and country `USA` specifically

### Visual Analysis
- Bar plots, histograms, line plots, heatmaps

---

## 💻 Technologies Used

- Python (Jupyter Notebook)
- Pandas, NumPy
- Seaborn

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/EDA-UM-Races.git
cd EDA-UM-Races
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Open the notebook
```bash
jupyter notebook main.ipynb
```

---

## 📎 File Structure

```
Exploratory Data Analysis/
│
├── main.ipynb              # Jupyter notebook with full analysis
├── requirements.txt        # Dependencies
└── README.md               # Project overview
```

---

## 📌 License
This project is licensed for educational and research purposes.
