# Rainfall Analysis and Planting Advisory

## Project Summary
A farmer-support NGO sends SMS planting advice to farmers in five Kenyan counties (Nairobi, Nakuru, Kisumu, Mombasa and Machakos). This project cleans a hand-typed Machakos rainfall record, analyses monthly rainfall for all five counties with NumPy (annual totals, monthly averages, wettest month, dry months and best two-month planting window), and writes the results to `rainfall_summary.csv`.

## How to Run the Notebook
1. Clone or download this repository.
2. Install the requirements: `pip install -r requirements.txt`
3. Open `rainfall_analysis.ipynb` in Jupyter Notebook, JupyterLab or Google Colab.
4. Choose **Restart kernel and run all cells** (Colab: Runtime > Restart and run all). The notebook recreates `rainfall_summary.csv` in the same folder.

## Planting Advisory
- Farmers in Nairobi, Nakuru, Kisumu and Mombasa should prepare land in March and plant at the start of the April-May rains, the wettest two-month window in all four counties.
- Machakos farmers should plan around the November-December short rains (278 mm) and use drought-tolerant crops and water harvesting, since it is the driest county with six dry months.
- Machakos April and September readings were missing and estimated at 68 mm, so Machakos figures are less certain and advice should be checked against local forecasts.

## Files
- `rainfall_analysis.ipynb`: cleaning, NumPy analysis, advisory and data quality notes
- `rainfall_summary.csv`: one row per county
- `requirements.txt`: Python libraries used
