# MCS7103_AI_Price_Intelligence
AI-Powered Price Intelligence for Car Buyers in Uganda.

### 01_Data_Collection

All the scraping scripts and notebooks used to collect car data from online marketplaces. It includes the web scrapers that extract information from BeForward and Autorec. The goal of this stage is to gather raw vehicle data such as make, model, year, mileage, engine size, transmission type, fuel type and price.

### 02_Data_Cleaning

Includes the notebooks that clean and prepare the scraped data. Here, missing values are handled with oversampling, numeric fields are converted into proper numbers, text fields are standardized and USD prices are converted into UGX. The cleaned data from all sources is then merged into one unified dataset that is ready for analysis and modelling.

### 03_Explaratory_Analysis

Contains the exploratory data analysis notebook. This notebooks generates summary statistics and graphs to help understand the patterns in the dataset. Price distributions are explored in this stage to guide the modelling process.

### 04_Modelling

Holds the machine learning models used in the project. It includes the regression model for predicting car prices and the classification model for detecting whether a price is underpriced, fair or overpriced. The notebooks here also evaluate the models and save the best-performing versions.

### 05_Recommendation

Contains the notebooks that use the best trained models to make real predictions. It includes the price recommendation system and the overpricing checker, as well as a tool for showing similar cars. This stage produces the final outputs that a user would interact with.

### 06_Documentation
This folder contains the concept paper as well as the final report on what has been done. The report was generated with Latex.
