# Seasonal-Agriculture-Performance-Yield-Optimization-Analysis

End-to-end data analytics and statistical project investigating cross-seasonal agricultural performance across 4,000 multi-region farm records in India. Evaluates crop yields, profitability, irrigation efficiency, and pest risks to optimize seasonal farm outcomes.

## Project Objectives

* **Assess Seasonal Yields:** Compare Kharif, Rabi, and Zaid seasons to determine optimal planting cycles.
* **Analyze Irrigation Efficiency:** Evaluate water usage across Drip, Flood, Sprinkler, and Rainfed systems.
* **Evaluate Financial Viability:** Calculate total costs, revenue, and net profit across different crop types (e.g., Sugarcane, Wheat, Rice).
* **Identify Risk Factors:** Determine the mathematical correlation between rainfall, humidity, and disease/pest risk exposure.

## Technology Stack

* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy (Data Manipulation); Matplotlib, Seaborn (Data Visualization)
* **Environment:** Jupyter Notebook

## Key Insights

* **Seasonal Dominance:** The Kharif season demonstrates the highest average crop yield (5.63 t/ha) and farm profit (₹178,914), despite higher pest risks.
* **Irrigation Supremacy:** Drip irrigation achieves the highest water efficiency (6.27 tonnes/1,000m³) and peak mean profitability compared to traditional flood methods.
* **Crop Economics:** Cash crops like Sugarcane and Chilli drive maximum profit margins, whereas staple grains (Wheat, Rice) operate at average net losses under standard pricing models.
* **Feature Correlations:** A strong positive linear relationship exists between crop yield and water efficiency ($r = 0.92$), as well as total revenue and net profit ($r = 0.89$).

## Repository Structure

* `seasonal_agriculture_performance_dataset.ipynb`: Main Jupyter Notebook containing data cleaning, outlier treatment (IQR method), EDA, and statistical analysis.
* `seasonal_agriculture_performance_dataset.csv`: Raw dataset containing 4,000 multi-region farm records.
* `Seasonal_Agriculture_Performance_Analysis.pptx`: Final presentation deck summarizing business insights.
* `*.png`: Exported data visualization highlights (Correlation Heatmaps, Seasonal Profitability, etc.).

## How to Run

1. Clone the repository: `git clone [https://github.com/shaik-awaz-ali/Seasonal-Agriculture-Performance-Yield-Optimization-Analysis.git](https://github.com/shaik-awaz-ali/Seasonal-Agriculture-Performance-Yield-Optimization-Analysis.git)`
2. Install required dependencies: `pip install pandas numpy matplotlib seaborn`
3. Launch the notebook environment: `jupyter notebook seasonal_agriculture_performance_dataset.ipynb`
4. Execute all cells to reproduce the exploratory data analysis and generate the visual charts.

**Author:** Shaik Awaz Ali
