## Car Price Analysis – Exploratory Data Analysis (EDA)

#### 🏢 Business Problem

Car manufacturers, dealerships, and online marketplaces need to understand which vehicle features drive price variation to optimize pricing strategies, inventory planning, and marketing focus. Without data-driven insight, pricing decisions are often based on intuition, leading to:

cars being undervalued, reducing profit margins

cars being overpriced, leading to low sales and higher inventory holding cost

poor understanding of which features customers are truly willing to pay for

This project analyzes historical car sales data to answer the question:

“Which car characteristics contribute the most to price, and how strongly do they influence it?”

The goal is to translate raw car specification data into actionable pricing intelligence.

##### This project performs exploratory data analysis on car sales data to understand which characteristics most strongly influence car prices. The analysis explores both numerical and categorical factors, identifies statistically significant relationships, and highlights the most important predictors of price.

### 🎯 Project Objectives

Identify key features impacting car price

Explore relationships between numerical variables and price

Evaluate categorical features using visualization and statistical tests

Determine which variables are strong vs weak predictors

Build an analytical foundation for potential predictive modelling

### 🧰 Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scipy

### 🔍 Analysis Performed

#####The notebook includes:

#### ✔ Data understanding & feature exploration

Price distribution inspection

Feature-wise visual exploration

#### ✔ Correlation analysis

Pairwise correlations with price

Identification of strong positive and negative relationships

#### ✔ Numerical variable investigation

Relationship of price with:

engine size

curb weight

width and length

horsepower

city/highway mileage

bore and stroke

peak-rpm

#### ✔ Categorical variable analysis

body style

engine location

drive wheels

Visualizations used:

scatter plots

regression plots

boxplots

correlation tables and statistics


### 📈 Key Insights (from the notebook)

##### Engine size, curb weight, width and horsepower show strong positive correlation with price

##### City and highway mileage show strong negative correlation with price

##### Peak-rpm and stroke have weak relationships and are not good price predictors

##### Certain categorical features such as drive-wheels show meaningful differences in price distributions

##### These findings help narrow down important predictors for car price modelling.

### ✅ Conclusion

#### The project successfully:

Identifies the features most strongly affecting car prices

Differentiates strong vs weak predictors

Builds a statistical and visual foundation for future regression modelling

This project demonstrates skills in EDA, statistical reasoning, data visualization, and insight communication.


### 📊 Business Impact

Insights from this EDA can support multiple business decisions:

#### 🏷️ Optimized pricing strategy
Identify features that justify higher price points (engine size, horsepower, weight, drive-wheels)

#### 🚗 Product design & feature prioritization
Understand which specifications customers value most in premium segments

#### 🏬 Dealer inventory strategy
Focus stocking decisions on high-value configurations more likely to generate higher revenue

#### 📢 Targeted marketing
Promote features proven to be associated with premium pricing

#### 📉 Risk reduction
Avoid overemphasizing features with weak price impact (e.g., peak-rpm, stroke)

This analysis forms the foundation for future predictive pricing models, demand forecasting, and ROI optimization across automotive retail and manufacturing.
