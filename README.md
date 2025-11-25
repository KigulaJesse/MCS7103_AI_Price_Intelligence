# MCS7103_AI_Price_Intelligence
AI-Powered Price Intelligence for Car Buyers in Uganda.

### 01_Data_Collection

This folder contains all the scripts and notebooks used to collect car data from online marketplaces. It includes the web scrapers that extract information from BeForward and Autorec. The goal of this stage is to gather raw vehicle data such as make, model, year, mileage, engine size, transmission type, fuel type and price.

### 02_Data_Cleaning

This folder includes the notebooks that clean and prepare the scraped data. Here, missing values are handled, numeric fields are converted into proper numbers, text fields are standardized and USD prices are converted into UGX. The cleaned data from all sources is then merged into one unified dataset that is ready for analysis and modelling.

### 03_Explaratory_Analysis

This folder contains the exploratory data analysis notebooks. These notebooks generate summary statistics, graphs and visual insights to help understand the patterns in the dataset. Price distributions, correlations, trends and unusual values are explored in this stage to guide the modelling process.

### 04_Modelling

This folder holds the machine learning models used in the project. It includes the regression model for predicting car prices and the classification model for detecting whether a price is underpriced, fair or overpriced. The notebooks here also evaluate the models and save the best-performing versions.

### 05_Recommendation

This folder contains the notebooks that use the trained models to make real predictions. It includes the price recommendation system and the overpricing checker, as well as tools for showing similar cars. This stage produces the final outputs that a user would interact with.
