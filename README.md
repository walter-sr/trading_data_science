# Trader Performance vs Market Sentiment

## Data Science Intern Assignment — Primetrade.ai

Analyzes how Bitcoin market sentiment (Fear/Greed Index) relates to trader behavior and performance on Hyperliquid across 211,224 trades by 32 traders in 2024.

---

# Project Structure

```text
project/
│
├── analysis.ipynb            # Main notebook (Parts A, B, C + Bonus)
├── historical_data.csv       # Hyperliquid trader data (2024)
├── fear_greed_index.csv      # Bitcoin Fear/Greed Index
├── README.md                 # This file
│
└── charts/
    ├── chart1_performance_fear_vs_greed.png
    ├── chart2_behavior_fear_vs_greed.png
    ├── chart3_pnl_size_segment.png
    ├── chart4_winrate_longratio_perf_segment.png
    ├── chart5_drawdown_freq_segment.png
    ├── bonus1_feature_importance.png
    ├── bonus2_confusion_matrix.png
```

---

# Setup

## 1. Clone / Download the Project

Place `historical_data.csv` and `fear_greed_index.csv` in the same folder as `analysis.ipynb`.

---

## 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
```

### macOS / Linux

```bash
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate
```

---

## 3. Install Dependencies

```bash
pip install jupyterlab pandas numpy matplotlib seaborn scipy scikit-learn
```

---

## 4. Launch JupyterLab

```bash
jupyter lab
```

Then open `analysis.ipynb` in the browser tab that appears.

---

# How to Run

Open `analysis.ipynb` and run all cells top to bottom using:

- **Kernel → Restart Kernel and Run All Cells**
- OR use **Shift + Enter** sequentially through each cell

All charts are saved automatically to the same directory as the notebook.

No internet connection is required — all data is local.

---

# Dependencies

| Library | Purpose |
|---|---|
| pandas | Data loading, cleaning, merging, aggregation |
| numpy | Numerical operations |
| matplotlib | Chart generation |
| seaborn | Chart styling |
| scipy | Statistical significance testing (t-tests) |
| scikit-learn | Random Forest classifier, KMeans clustering, PCA |

---

# Project Goals

This project explores:

- Relationship between Bitcoin market sentiment and trader performance
- Behavioral differences during Fear vs Greed market conditions
- Predictability of trader profitability using machine learning
- Trader segmentation using clustering techniques
- Visualization of trading patterns and risk behavior

---

# Outputs

The notebook generates:

- Statistical analysis tables
- Performance comparison charts
- Trader behavior visualizations
- Machine learning evaluation metrics
- Feature importance plots
- Confusion matrix and predictive analytics charts

