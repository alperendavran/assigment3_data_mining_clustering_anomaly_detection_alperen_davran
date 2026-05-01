# Data Mining Assignment 3 — Clustering & Anomaly Detection

**Student:** Alperen Davran  

**Course report (PDF):** `Data_Mining_Assignment_3_Report.pdf`  

**Repository:** https://github.com/alperendavran/assigment3_data_mining_clustering_anomaly_detection_alperen_davran  

## Contents

| Item | Description |
|------|-------------|
| `Data_Mining_Assignment_3_Report.pdf` | Written report (Blackboard submission) |
| `notebooks/` | Decision-log Jupyter notebooks (exploration → clustering → anomaly → optional advanced) |
| `clusters.csv` | Cluster label per document (same row order as `articles.csv`) |
| `anomalies.csv` | Exactly 50 anomaly document IDs |
| `articles.csv` | Assignment dataset (required to re-run notebooks from the project root) |
| `requirements.txt` | Python dependencies |

## Re-running notebooks

From the repository root (where `articles.csv` lives):

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

Open notebooks in numeric order (`01_` … `04_`). Notebook `ROOT` logic expects `articles.csv` in the current working directory or one level above `notebooks/`.
