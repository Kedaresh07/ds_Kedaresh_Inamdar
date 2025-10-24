# ds_Kedaresh_Inamdar
Trader Behavior vs Market Sentiment — Web3 Trading Team assignment

## Overview
This repository contains the analysis for the "Trader Behavior vs Market Sentiment" assignment. The work studies how trading metrics (profitability, leverage, trade size) change across Bitcoin market sentiment (Fear vs Greed).

## Contents
- `notebook_1.ipynb` : Google Colab notebook with data loading, preprocessing, analysis and visualizations.
- `csv_files/` :
  - `trader_data.csv` (downloaded raw)
  - `fear_greed.csv` (downloaded raw)
  - `merged_data.csv` (cleaned merged dataset)
  - `summary_stats.csv` (group-level summary)
  - `correlation_matrix.csv`
- `outputs/` :
  - `avg_pnl_by_sentiment.png`
  - `avg_leverage_by_sentiment.png`
  - `avg_trade_size_by_sentiment.png`
  - `correlation_heatmap.png`
- `ds_report.pdf` : One-page summarized insights (exported PDF).

## How to run
1. Open `notebook_1.ipynb` in Google Colab.
2. Ensure datasets are available in `/content/ds_Kedaresh_Inamdar/csv_files/` (the notebook attempts to download them automatically via `gdown`).
3. Run all cells top-to-bottom.
4. After execution, results are saved to:
   - `/content/ds_Kedaresh_Inamdar/csv_files/`
   - `/content/ds_Kedaresh_Inamdar/outputs/`
5. Save the notebook to GitHub via Colab: `File → Save a copy in GitHub` and set access to viewable.

## Notes
- The notebook is tolerant to minor column-name variations; if your dataset uses different names, adjust the mapping in the first cells.
- For final submission, confirm that Colab "Save a copy in GitHub" was used (share the GitHub repo and Colab link set to "Anyone with the link can view").

## Contact
Kedaresh Inamdar
