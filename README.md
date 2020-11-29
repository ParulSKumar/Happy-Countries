# Pursuit Of Happiness
Project for the course Data Analytics (UE18CS312)

Team Name: What's In A Name?                                                                                                                                                  
Members: Parul S Kumar, Ananya Angadi, Manasa V L

Original Data: https://www.kaggle.com/unsdsn/world-happiness

# About the data
The World Happiness Report is a document published annually by the United Nations’ Sustainable Development Solutions Network. The data used to prepare this report is collected as part of the Gallup World Poll. The study focusses on estimating the state of happiness in over 156 countries around the world, based on how happy citizens from this country consider themselves to be. The happiness report also assigns a happiness score to each country, and ranks them with respect to the same. This data can be used by policy makers in every country to assess the overall well-being, and to identify areas for improvement.

# Overview
Our project aims to study the socio-economic and political factors affecting individual well-being in countries around the world, with special emphasis on India. We aim to forecast future values of the happiness score, and this knowledge can be used to influence policy-making. In addition, we look at differences between the happiest and saddest countries to find areas where each nation can do better.

# Dataset
A subset of the data being used for preparing the WHR has been made available to the public on Kaggle. We have used the same for the purpose of our analysis. Contains the following information:
•	Happiness score and Happiness Rank
•	Estimate of the extent to which six factors – GDP, social support, government trust, life expectancy, freedom, and generosity – which are responsible for making life evaluations higher in that country than they are in Dystopia.
•	Dystopia Residuals
Dystopia is a hypothetical nation which houses the unhappiest people in the world. The least score for each of the 6 variables among all countries is assigned to Dystopia. In short, no country does worse than Dystopia, and hence is it can be used as a benchmark to measure other countries against. Dystopia residual is the unexplained component, which is not captured by the 6 factors.
The happiness score is the sum of the 6 contributions.

# Code
DataIntegration.ipynb: Combining data from the years 2015 to 2019, along with preliminary preprocessing                                                                   
EDA.ipynb: Exploratory Data Analysis and Visualizations   
Model.ipynb: Training and Testing Forecasting models

# Instructions to Run
Run DataIntegration.ipynb to preprocess and integrate the data.
The cleaned and integrated data is stored in data.csv. [FINAL DATA]
Run EDA.ipynb for EDA and visualization
Run Model.ipynn for model training
No other specific instructions
