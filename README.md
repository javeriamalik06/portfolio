
# Javeria Malik - Data Analysis/Science Portfolio

Hi! I am Javeria, a data analyst and aspiring data scientist with a strong foundation in business.

I am currently pursuing my Masters in Business Analytics at the University of Illinois Urbana Champaign and have completed my Bachelors in Business Administration from IBA Karachi. My work experience includes a year as a Quantitative Insights Consultant at Oula (Kantar), where I strengthened my skills in data-driven insights generation, quantitative analysis and data storytelling. 

The following portfolio showcases my skills, and you can find my CV [here](https://docs.google.com/document/d/1g8u4zkN-hzx0cRiTgMiYPJlApT6MzPLWEVqcxUlM66Q/edit?usp=sharing).

### Contents

1. [Understanding the Effect of Economic Indicators on US Stock Market Returns](#understanding-economic-indicators)
2. [Telecom Customer Churn Prediction](#telecom-customer-churn-prediction)
3. [Stock Analysis for Burshane Private Limited (BPL)](#stock-analysis-for-burshane-private-limited-bpl)
4. [Portfolio Risk Analysis and Optimization for PKGS, PPP, BPL](#portfolio-risk-analysis-and-optimization-for-pkgs-ppp-bpl)
5. [Pokemon Exploratory Data Analysis](#pokedex-eda-analysis)
6. [Maven Movies Analysis-SQL](#maven-movies-analysis-sql)

---

## [Understanding the Effect of Economic Indicators on US Stock Market Returns](https://github.com/javeriamalik06/Adv-DS-and-Python-for-Finance)<a name="understanding-economic-indicators"></a>

#### Business Problem
The stock market is sensitive to various macroeconomic factors, influencing investor decisions and portfolio strategies. This project aims to analyze the impact of economic indicators—like GDP, CPI, unemployment rates, and money supply—on US stock market performance. By identifying correlations and predictive relationships, the study provides insights for investors with different risk appetites to make informed decisions.

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
* Technology: Python (Pandas, NumPy, Seaborn, Scikit-learn)

#### Recommendations
For risk-averse individuals, ETFs tracking diversified indices like Russell 3000 are ideal, offering stability against economic fluctuations. Risk-tolerant investors might prefer Dow Jones due to its high sensitivity to economic activity, yielding potentially higher returns.

---

## [Telecom Customer Churn Prediction](https://github.com/javeriamalik06/Telecom-Customer-Churn-Prediction) <a name="telecom-customer-churn-prediction"></a>

#### Business Problem
The telecom industry faces significant customer churn, threatening profitability and market share. This project identifies the customers at risk of churning in the company and recommends effective retention strategies to enhance customer satisfaction and drive long-term business growth. 

#### Technical Details
* Data was taken from Kaggle
* Machine Learning models: Logistic Regression and Decision Trees
* Logistic Regression was used to predict the churn and profitability
* Decision trees were used to identify customer segments and strategies to maximize satisfaction from each segment
* [Code](https://github.com/javeriamalik06/Telecom-Customer-Churn-Prediction/blob/main/Telecom%20Customer%20Churn%20Prediction%20Code.R) and [Final report](https://github.com/javeriamalik06/Telecom-Customer-Churn-Prediction/blob/main/Customer%20Churn%20Prediction%20Report.pdf) available
* Technology: **R** (dplyr, caret, PRROC, rpart, rpart.plot)

#### Recommendation
To reduce customer churn, the telecom company should implement targeted pricing strategies for price-sensitive customers, enhance DSL service reliability, and focus on personalized retention efforts for high-value customers. Continuous monitoring of customer feedback is essential to identify and address pain points. Additionally, investing in targeted marketing campaigns to highlight the company’s unique offerings and superior customer service can strengthen customer loyalty and satisfaction.

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
