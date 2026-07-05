# 🚗 Car Price Analysis — Exploratory Data Analysis (EDA)


Identifying which car characteristics actually drive price — using correlation analysis, statistical testing, and visual EDA to build a foundation for smarter pricing decisions.




## 🌍 What This Project Does (For Everyone)

Have you ever wondered why two cars with similar looks are priced so differently? Is it the engine? The weight? The mileage?

This project analyses historical car sales data to find out exactly which features drive car prices — and which ones people assume matter but actually don't.

The findings help answer:


🏷️ Which features justify a higher price tag?
⛽ Does fuel efficiency make a car cheaper or more expensive?
🔧 Does engine size really matter that much?
🚙 Which specs are weak predictors that dealers over-emphasise?



## 📌 Project Overview

This project covers a full EDA workflow:


🧹 Data cleaning and feature exploration
📊 Price distribution analysis
🔗 Correlation analysis between specs and price
📐 Statistical significance testing
📈 Visual investigation of numerical and categorical variables
💡 Business pricing recommendations



## 📂 Dataset Description

Source: Kaggle — Car Price Dataset

The dataset contains detailed car specifications and their corresponding prices:

Feature CategoryVariables💰 TargetPrice🔧 Engine SpecsEngine size, horsepower, bore, stroke, peak RPM⚖️ Physical DimensionsCurb weight, width, length, height⛽ Fuel EfficiencyCity mileage, highway mileage🏷️ Categorical FeaturesBody style, drive wheels, engine location


## ⚙️ Tools & Technologies

ToolPurpose🐍 Python (Pandas, NumPy)Data manipulation and analysis📊 Matplotlib, SeabornScatter plots, boxplots, regression plots📐 SciPyStatistical testing and correlation analysis📓 Jupyter NotebookDevelopment environment


## 🧹 Data Cleaning & Preprocessing


Inspected and handled missing values across key feature columns
Standardised data types for numerical and categorical variables
Removed outliers affecting price distribution
Encoded categorical variables for correlation analysis
Normalised feature ranges for fair comparison



## 📈 Key Findings

#### 🔗 What Drives Car Prices Most?

FeatureCorrelation with PriceVerdictEngine SizeStrong Positive ✅Key price driverCurb WeightStrong Positive ✅Key price driverWidthStrong Positive ✅Key price driverHorsepowerStrong Positive ✅Key price driverCity MileageStrong Negative 🔽Higher mileage = lower priceHighway MileageStrong Negative 🔽Higher mileage = lower pricePeak RPMWeak ❌Not a reliable predictorStrokeWeak ❌Not a reliable predictor

#### 💡 The Biggest Surprise

Fuel efficiency negatively correlates with price — cars that get better mileage are generally cheaper. This makes sense because high-performance, premium cars tend to have larger, less efficient engines — which is exactly what drives their higher price.

#### 🚙 Categorical Insights


Drive wheels show meaningful price differences — rear-wheel drive vehicles tend to be significantly more expensive than front-wheel drive ones
Engine location (front vs rear) also shows a notable price difference
Body style has a moderate impact — hardtops and convertibles tend to sit at higher price points than hatchbacks


#### 🔑 Strong vs Weak Predictors Summary

Worth pricing around: Engine size, horsepower, curb weight, width
Not worth over-emphasising: Peak RPM, stroke — these have weak relationships with price and should not be used to justify premium pricing


#### 💡 Business Recommendations


Price around engine size and horsepower — these are the two most defensible premium price justifiers to customers.
Don't use fuel efficiency as a premium signal — high mileage correlates with lower prices, not higher. It's a value feature, not a luxury one.
Rear-wheel drive configurations command a premium — stock and market them accordingly.
Drop peak RPM and stroke from pricing models — their weak correlation with price means they add noise, not insight.
Focus marketing for premium segments on weight and dimensions — larger, heavier cars are perceived as more valuable and the data backs this up.



## 🔑 Key Technical Takeaway


Correlation analysis reveals which car features customers are actually willing to pay for — vs which ones sound impressive but don't move the price needle. This distinction is what separates data-driven pricing from intuition-based pricing, and the gap between the two is measurable in margin.
