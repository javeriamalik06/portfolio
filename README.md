
# Javeria Malik - Data Analysis/Science Portfolio

Hi! I am Javeria, a data analyst and aspiring data scientist with a strong foundation in business.

I am currently pursuing my Masters in Business Analytics at the University of Illinois Urbana Champaign and have completed my Bachelors in Business Administration from IBA Karachi. My work experience includes a year as a Quantitative Insights Consultant at Oula (Kantar), where I strengthened my skills in data-driven insights generation, quantitative analysis and data storytelling. 


### Contents

1. [FIFA World Cup PowerBi Dashboard](#fifa-dashboard)
2. [Understanding the Effect of Economic Indicators on US Stock Market Returns](#understanding-economic-indicators)
3. [Predicting Customer Churn for Telecom Company](#telecom-customer-churn-prediction)
4. [Impact of Electric Vehicles Adoption on Automaker Stock Performance](#ev-auto-industry-impact)
5. [Uncovering Customer Preferences in Lutz's Restaurant Market Using Yelp Data](#restaurant-insights-lutz)
6. [Predicting Residential Property Values for Cook County](#cook-county-property-valuation)
7. [Chicago Traffic Accidents Analysis](#chicago-traffic-accidents-analysis)
8. [Stock Analysis for Burshane Private Limited (BPL)](#stock-analysis-for-burshane-private-limited-bpl)
9. [Portfolio Risk Analysis and Optimization for PKGS, PPP, BPL](#portfolio-risk-analysis-and-optimization-for-pkgs-ppp-bpl)
10. [Pokemon Exploratory Data Analysis](#pokedex-eda-analysis)
11. [Maven Movies Analysis-SQL](#maven-movies-analysis-sql)

---

## [FIFA World Cup PowerBi Dashboard](https://github.com/javeriamalik06/Adv-DS-and-Python-for-Finance)<a name="fifa-dashboard"></a>

![FIFA World Cup PowerBi Dashboard](https://github.com/javeriamalik06/portfolio/blob/main/FIFA%20World%20Cup.png)


---

## [Understanding the Effect of Economic Indicators on US Stock Market Returns](https://github.com/javeriamalik06/Adv-DS-and-Python-for-Finance)<a name="understanding-economic-indicators"></a>

#### Business Problem
The stock market is sensitive to various macroeconomic factors, influencing investor decisions and portfolio strategies. This project aims to analyze the impact of economic indicators—like GDP, CPI, unemployment rates, and money supply—on US stock market performance. By identifying correlations and relationships, the study provides insights for investors with different risk appetites to make informed decisions.

#### Technical Details
* Data Sources:
  1. Stock Data: Yahoo Finance
  2. Economic Data: Federal Reserve Economic Development (FRED)
* Analysis Workflow:
  1. Data Cleaning and Merging
  2. Correlation Analysis (Seaborn visualizations)
  3. Multiple Linear Regression for impact analysis
  4. Performance evaluation with metrics (Mean Squared Error and R-squared)
* Model Results:
  1. Strong Correlations: GDP and Personal Consumption Expenditure (PCE) positively influence stock returns.
  2. Weak Correlations: Unemployment and core inflation have limited short-term effects on market performance.
* Market Index Insights:
  1. S&P 500: Best overall fit, balanced metrics.
  2. Dow Jones: Strong predictive power but higher error rates.
  3. Russell 3000: Least volatile, suitable for risk-averse investors.
* [Code](https://github.com/javeriamalik06/Adv-DS-and-Python-for-Finance/blob/main/Advanced%20Python%20for%20Finance%20Project%20Team%207%20Code%20file.ipynb) and [Report](https://github.com/javeriamalik06/Adv-DS-and-Python-for-Finance/blob/main/Understanding%20effect%20of%20econ%20indicators%20on%20market%20returns%20-%20Team%207.pptx) available.
* Tools: Python (Pandas, NumPy, Seaborn, Scikit-learn)

#### Recommendations
For risk-averse individuals, ETFs tracking diversified indices like Russell 3000 are ideal, offering stability against economic fluctuations. Risk-tolerant investors might prefer Dow Jones due to its high sensitivity to economic activity, yielding potentially higher returns.

---

## [Predicting Customer Churn for Telecom Company](https://github.com/javeriamalik06/Telecom-Customer-Churn-Prediction) <a name="telecom-customer-churn-prediction"></a>

#### Business Problem
The telecom industry faces significant customer churn, threatening profitability and market share. This project identifies the customers at risk of churning in the company and recommends effective retention strategies to enhance customer satisfaction and drive long-term business growth. 

#### Technical Details
* Data was taken from Kaggle
* Machine Learning models: Logistic Regression and Decision Trees
* Logistic Regression was used to predict the churn and profitability
* Decision trees were used to identify customer segments and strategies to maximize satisfaction from each segment
* [Code](https://github.com/javeriamalik06/Telecom-Customer-Churn-Prediction/blob/main/Telecom%20Customer%20Churn%20Prediction%20Code.R) and [Final report](https://github.com/javeriamalik06/Telecom-Customer-Churn-Prediction/blob/main/Customer%20Churn%20Prediction%20Report.pdf) available
* Tools: **R** (dplyr, caret, PRROC, rpart, rpart.plot)

#### Recommendation
To reduce customer churn, the telecom company should implement targeted pricing strategies for price-sensitive customers, enhance DSL service reliability, and focus on personalized retention efforts for high-value customers. Continuous monitoring of customer feedback is essential to identify and address pain points. Additionally, investing in targeted marketing campaigns to highlight the company’s unique offerings and superior customer service can strengthen customer loyalty and satisfaction.

---

## [Impact of Electric Vehicles Adoption on Automaker Stock Performance](https://github.com/javeriamalik06/Data-Storytelling) <a name="ev-auto-industry-impact"></a>

#### Business Problem
The adoption of electric vehicles (EVs) is transforming the global auto industry. This project explores how significant EV-related events, such as Tesla's IPO and the Inflation Reduction Act, have impacted the stock prices of key automakers and evaluates their alignment with broader market trends.

#### Technical Details
* Companies analyzed: Tesla, Rivian, Ford, Ferrari, Toyota, Honda
* Events covered: Tesla IPO, COVID-19, Volkswagen Dieselgate, Inflation Reduction Act
* Data Sources: Finnhub Stock API, Nasdaq Data Link
* Techniques: Regression analysis, correlation metrics, stock performance benchmarking
* Tools: Mathematica
* [Code](https://github.com/javeriamalik06/Data-Storytelling/blob/main/Final_Project_Group%2013.nb) and [Presentation](https://github.com/javeriamalik06/Data-Storytelling/blob/main/Data%20Storytelling%20Presentation.pptx) available

#### Findings
* EV-focused companies (e.g., Tesla) often exhibit higher volatility but stronger growth trends.
* Events like COVID-19 and the Inflation Reduction Act highlighted the resilience of traditional automakers.
* Regression analysis revealed varying levels of market dependence among automakers.

#### Recommendations
To maximize growth, automakers should:
1. Align their strategies with evolving EV policies and incentives.
2. Invest in technological innovation to meet increasing EV demand.
3. Monitor market trends and external factors closely to stay ahead of industry shifts.

---

## [Uncovering Customer Preferences in Lutz's Restaurant Market Using Yelp Data](https://github.com/javeriamalik06/Enterprise-Data-Management/tree/main/Project%201) <a name="restaurant-insights-lutz"></a>

#### Business Problem
Understanding customer preferences is key to staying ahead in any restaurant market. This project aimed to analyze Yelp’s dataset to identify top-performing restaurants, preferred cuisines, and effective strategies to enhance customer satisfaction and engagement in the restaurant market of Lutz, FL.

#### Technical Details
* Data Source: Yelp API
* Database: Azure SQL
* Key Analyses:
  - Identified top-rated and most-reviewed restaurants.
  - Analyzed customer sentiments from reviews and tips.
  - Determined optimal restaurant types and postal codes for targeting based on review density.
  - Recommended strategies based on reviewer loyalty and feedback trends.
* Tools: Python (Pandas, SQLAlchemy), SQL, Azure SQL Database
* [Code and analysis](https://github.com/javeriamalik06/Enterprise-Data-Management/tree/main/Project%201) available

#### Recommendation
For restaurants in Lutz, leveraging insights from reviews to optimize menu offerings and providing incentives to loyal customers can significantly enhance customer satisfaction. Focusing on areas with high review densities and preferred cuisines, like fast food and pizza, can maximize initial impact for new entrants.

---

## [Predicting Residential Property Values for Cook County](https://github.com/javeriamalik06/BigDataAnalytics-for-Finance/tree/main/Project) <a name="cook-county-property-valuation"></a>

#### Business Problem
The Cook County Assessor’s Office faced significant challenges in determining fair market values for over 1.8 million properties annually. Historical valuation methods lacked transparency and precision, leading to public dissatisfaction. This project aims to improve residential property valuation using machine learning techniques, enhancing accuracy and public trust.

#### Technical Details
- **Data Source**: Historical property sales data from Cook County
- **Machine Learning Models Tested**: 
  - Linear Regression (Baseline Model)
  - Lasso Regression
  - Forward Stepwise Selection on Linear Regression
  - Random Forest
- **Best Performing Model**: Linear Regression with Forward Stepwise Selection
  - **CV MSE**: 15.88 billion
  - **R²**: ~83.23%
- **Technology**: Python (Pandas, NumPy, scikit-learn, Matplotlib, Seaborn)
- **Deliverables**: [Code](https://github.com/javeriamalik06/Cook-County-Property-Valuation/blob/main/code.py) and [Final Report](https://github.com/javeriamalik06/Cook-County-Property-Valuation/blob/main/report.pdf)

#### Recommendation
The Cook County Assessor’s Office should adopt a linear regression model with forward stepwise selection for property valuation. This approach minimizes error while maintaining model simplicity, making it interpretable for stakeholders. By addressing historical biases and inaccuracies, the office can ensure equitable taxation and foster public confidence in the assessment process.

---

## [Chicago Traffic Accidents Analysis](https://github.com/javeriamalik06/Topics-in-Business-Intelligence) <a name="chicago-traffic-accidents-analysis"></a>

#### Business Problem
Chicago experiences at least over 100k crashes annually, creating a pressing need for improved traffic safety. This project analyzes historical traffic data (2019–2024) to identify patterns, high-risk zones, and contributing factors, helping city planners and the public promote safer driving practices. Machine learning models predict crash fatality likelihood, showcasing the role of business intelligence in urban safety.

#### Technical Details
* **Data Source**: [City of Chicago Traffic Data](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if/about_data)
* **Machine Learning Models**: Logistic Regression, Random Forest
* **Key Features**: Weather Conditions, Road Defects, Surface Conditions, Speed Limits
* **Tools**: Python (pandas, scikit-learn, matplotlib), Tableau
* **Focus Areas**:
  - High-risk crash zones in downtown Chicago
  - Timing analysis for peak accident periods
  - Role of road conditions and weather
* [Code](https://github.com/javeriamalik06/Topics-in-Business-Intelligence/blob/main/Chicago_Crash_EDA_areas_high_risk.ipynb) and [Report](https://github.com/javeriamalik06/Topics-in-Business-Intelligence/blob/main/Group%2016_%20Bilal%2C%20Agha%2C%20Malik%2C%20Abdalla%2C%20Tan.pptx) available
* [Tableau dashboard](https://public.tableau.com/app/profile/damario.abdalla7630/viz/ChicagoCrashes_17331017996030/FactorsContribute?publish=yes) available

#### Recommendations
To reduce crashes:
- Improve signage and road design in high-risk areas.
- Increase awareness campaigns for drivers about common crash factors.
- Deploy targeted interventions during peak crash times.
- Monitor clear-weather crash trends and promote better driving practices.

---

## [Stock Analysis for Burshane Private Limited (BPL)](https://github.com/javeriamalik06/Stock-and-Portfolio-Analysis-and-Prediction/tree/main/Project%201) <a name="stock-analysis-for-burshane-private-limited-bpl"></a>

#### Business Problem
Burshane Private Limited is a Pakistani company specializing in the distribution and marketing of liquefied petroleum gas (LPG). This project leverages time series forecasting and rolling regression to predict stock trends and assess financial risks, ultimately providing recommendations to investors on whether to buy BPL stock.

#### Technical Details
* Real-life stock data used through Yahoo Finance library
* Programming language used: Python
* Important tech concepts used: Prophet (time series forecasting), RollingOLS (Rolling Regression), Backtesting
  1. Prophet is used for time series forecasting of stock prices
  2. RollingOLS is used to calculate beta in a rolling window for Cost of Capital calculation
  3. Backtesting is used to test strategies on historical data
* [Code](https://github.com/javeriamalik06/Stock-and-Portfolio-Analysis-and-Prediction/tree/main/Project%201) and [Final report](https://github.com/javeriamalik06/Stock-and-Portfolio-Analysis-and-Prediction/blob/main/Project%201/Project%201%20-%20Javeria%20Malik%20-%20BPL.pdf) available
* Technology: **Python** (pandas, matplotlib, seaborn, talib, prophet, backtesting, psx, numpy)

#### Stock Recommendation
BPL stock is currently not a viable investment due to its poor performance and declining trends, with forecasts predicting a gradual drop in stock prices and consistently negative cash flows. Technical indicators reveal weak performance, while high VaR and cVaR values indicate significant risk for investors. Low Pitroski’s F-score and Graham value suggest an overvalued stock and a weak financial position.

---

## [Portfolio Risk Analysis and Optimization for PKGS, PPP, BPL](https://github.com/javeriamalik06/Stock-and-Portfolio-Analysis-and-Prediction/tree/main/Project%202) <a name="portfolio-risk-analysis-and-optimization-for-pkgs-ppp-bpl"></a>

#### Business Problem
This report assesses the historical performance and risk of a stock portfolio that includes Pakistan Paper Products Limited (PPP), Packages Limited (PKGS), and Burshane Private Limited (BPL). By utilizing various Value at Risk (VaR) methods, we seek to optimize stock allocation to enhance returns while minimizing risks, facilitating informed investment decisions.

#### Technical Details
* Important concepts used: Historical VaR, Model-Building VaR, Monte-Carlo VaR, Copulas
  1. Historical VaR is used for calculating Value at Risk using historical stock price data
  2. Model-Building VaR is used for calculating Value at Risk using the parametric approach and variance-covariance matrix
  3. Monte-Carlo VaR is used for calculating Value at Risk using simulations
  4. Copulas are used for modeling dependencies between different stocks in the portfolio
* [Code](https://github.com/javeriamalik06/Stock-and-Portfolio-Analysis-and-Prediction/tree/main/Project%202) and [Final report](https://github.com/javeriamalik06/Stock-and-Portfolio-Analysis-and-Prediction/blob/main/Project%202/Project%202%20-%20Portfolio%20Analysis%20-%20Report.pdf) available
* Technology: **Python** (numpy, pandas, matplotlib, seaborn, scipy, statsmodels, copulae, riskfolio, psx, finance)

#### Portfolio Recommendation
The recommendations for the portfolio analysis include reallocating weights to increase investment in Packages Limited and Pakistan Paper Products Limited while reducing exposure to Burshane Private Limited. Regularly monitor performance and employ risk management strategies to mitigate losses. Utilize forecasting models for better predictions, implement periodic rebalancing, and stay informed about market trends.

---

## [Pokemon Exploratory Data Analysis](https://github.com/javeriamalik06/Pokedex-EDA) <a name="pokedex-eda-analysis"></a>

#### Business Problem
As a lifelong Pokémon player, I often wondered what the ultimate combination of Pokémon would be for battle. This project explores data to identify Pokémon with the highest stats (for eg. HP, defense etc.) for optimal team selection.
#### Technical Details
* Dataset: [Pokedex Database](https://www.kaggle.com/datasets/hamzacyberpatcher/data-of-1010-pokemons)
* Explored Pokémon statistics including attack, defense, and total scores by types, generations, and ranks
* Created visualizations such as histograms, bar plots, and box plots to analyze patterns in Pokémon stats
* Analyzed legendary, mythical, and ordinary Pokémon to find insights about their strengths and characteristics
* Provided insights and recommendations on which Pokémon to start with and which ones to catch for players of the game
* [Code and Analysis](https://github.com/javeriamalik06/Pokedex-EDA/blob/main/Pokedex_EDA.ipynb) available
* Technology: **Python** (pandas, seaborn, matplotlib, numpy)
#### Recommendation
For optimal Pokémon team composition, start with Squirtle for defense and Charmander for attack among the starter options. Steel Pokémon offer the highest defensive capabilities, making them excellent choices for fortifying your team. Meanwhile, Dragon Pokémon excel in attack, providing powerful offensive options. Additionally, including a Legendary Pokémon significantly boosts overall stats.

---

## [Maven Movies Analysis-SQL](https://github.com/javeriamalik06/Maven-Movies-Analysis-SQL) <a name="maven-movies-analysis-sql"></a>

* Implemented SQL queries with aggregate functions, CASE statements, JOIN operations, and UNION to extract and merge comprehensive relational database insights.
* Important Concepts Used: Exploratory Data Analysis of a movie database
  1. Basic SQL Operations: SELECT, GROUP BY, ORDER BY
  2. Data Aggregation: Aggregate functions (COUNT, AVG, SUM, MIN, MAX)
  3. Data Filtering and Sorting: HAVING, CASE statements
  4. Data Joins: INNER JOIN, LEFT JOIN, multi-condition joins
  5. Data Manipulation: UNION operations
* Technology: **SQL**
