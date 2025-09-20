# Marketing Campaign Analysis

This project analyzes the effectiveness of marketing campaigns using Python.  
The focus is on daily and campaign-level metrics, identifying relationships between key metrics, and visualizing trends and variability.

## Analysis Steps

### 1. Daily Metrics
- Group data by day and calculate:
  - **Daily Advertising Spend**
  - **Daily ROMI (Return on Marketing Investment)**
- Calculate **7-day moving averages** to smooth trends:
  - Ad spend: gray line = daily, blue line = 7-day MA
  - ROMI: gray line = daily, blue line = 7-day MA

### 2. Campaign-Level Metrics
- Group data by **campaign name** and calculate:
  - Total advertising expenses per campaign
  - Average ROMI per campaign
- Insights:
  - Brand campaign has the lowest expenses; Expansion has the highest, suggesting market expansion.
  - Promos and Trendy campaigns show the highest ROMI (~2), indicating higher profitability but also higher risk.

### 3. Distribution Analysis
- **Boxplot** and **histogram** of ROMI:
  - Most days have ROMI between 1–1.5 (successful range).
  - Promos and Trendy campaigns show higher variability.

### 4. Correlation Analysis
- Calculate correlation between key metrics:
  - **Highest correlation:** ad spend and revenue (~0.98) → strong linear relationship.
  - **Lowest positive correlation:** ad spend and CPC → increasing spend does not affect CPC.
  - Revenue moderately correlates with impressions, clicks, and CPM.
- Scatter plot of **ad spend vs revenue** confirms the linear relationship and absence of outliers.

## Technologies Used
- **Python** (**pandas** — data processing, **matplotlib** and **seaborn** — visualizations (line plots, scatter plot, heatmap, boxplot))
- **Jupyter Notebook**
- 
## General Conclusions
- Marketing campaigns are generally effective: ad spend is strongly correlated with revenue.  
- Moving averages help identify trends and smooth out daily fluctuations.  
- Some campaigns (Promos, Trendy) are more profitable but riskier, while others (Wholesale) are more stable and predictable.  
- Simply increasing impressions and clicks is insufficient; campaigns and content need optimization.

## How to Run

**1. Clone the repository:**
git clone https://github.com/OlenaRyzuk/Python-projects.git

**2. Install required Python packages (manually if needed):**
pip install pandas matplotlib seaborn

**3. Run the analysis in Jupyter Notebook:**
jupyter notebook "Marketing Campaigns Effectiveness.ipynb"
