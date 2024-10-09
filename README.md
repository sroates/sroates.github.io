# Does Money Buy Happiness?

## Analyzing the Most Influential Factors in Determining Happiness

**Collaborators:** Grace Koerner, Samuel Oates, Sudharma Bhat  
**View the full report:** [Report Link](https://sroates.github.io/)

---

### Project Overview

This project explores the key factors that contribute to happiness on a global scale. By leveraging data from the **World Happiness Report** and performing a full data science pipeline—data collection, processing, exploratory analysis, and machine learning—we aim to address the long-debated question: _"Does money buy happiness?"_

### Data Science Pipeline

1. **Data Collection:**  
   Data was procured from various sources, including CSV files and web scraping using `BeautifulSoup` and `requests`.

2. **Data Processing:**  
   We processed the data using `pandas` and `numpy`, cleaning and transforming it for analysis.

3. **Exploratory Data Analysis & Visualization:**  
   Using `seaborn` and `matplotlib`, we explored the relationships between happiness and variables like GDP per capita, social support, and life expectancy.

4. **Machine Learning & Analysis:**  
   We employed models such as `RandomForestRegressor` and `LinearRegression` to predict happiness scores based on different factors. `PCA` and `StandardScaler` were used for dimensionality reduction and normalization. The performance of these models was evaluated using metrics like `mean_squared_error`.

### Data Sources

The primary dataset is from the **World Happiness Report**, a collaborative project involving Gallup, the UN Sustainable Development Solutions Network, and other global institutions. It ranks countries based on variables such as:

- GDP per capita
- Social support
- Healthy life expectancy
- Freedom
- Generosity
- Perceptions of corruption

### Key Insights

Happiness is more than a subjective feeling—it has a profound impact on health, social connection, and well-being. Our analysis highlights significant factors influencing happiness globally, offering insights that may help individuals make life decisions to enhance their own happiness.

> **Note:** Due to the global COVID-19 pandemic, data from 2022 has been excluded from the analysis as it drastically differs from other years.

---

### Libraries Used

- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **seaborn & matplotlib**: Data visualization
- **BeautifulSoup & requests**: Web scraping
- **sklearn (RandomForestRegressor, LinearRegression, PCA, StandardScaler)**: Machine learning models and data preprocessing

### Conclusion

By analyzing worldwide happiness data, we hope to provide valuable insights into what truly contributes to happiness. Our findings can help policymakers and individuals alike better understand the global happiness landscape.
