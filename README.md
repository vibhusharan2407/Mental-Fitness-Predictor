# Mental-Fitness-Predictor

## Introduction
Mental and substance use disorders are significant contributors to the global disease burden. This project aims to analyze the prevalence of these disorders and predict their impact on DALYs using various machine learning models.

## Datasets
The following datasets from Kaggle are used in this project:

Mental Health Dataset: https://www.kaggle.com/datasets/programmerrdai/mental-health-dataset  

Global Trends in Mental Health Disorder: https://www.kaggle.com/datasets/thedevastator/uncover-global-trends-in-mental-health-disorder  

These datasets contain information about the prevalence of different mental and substance use disorders and their contribution to the overall disease burden.

## Project Structure

mental-health-analysis/  

│  

├── data/  

│   ├── mental-and-substance-use-as-share-of-disease.csv  

│   ├── prevalence-by-mental-and-substance-use-disorder.csv  

│  

├── notebooks/  

│   ├── MFT_vibhu.ipynb  

│  

├── images/  

│   ├── eda_plots.png  

│   ├── model_performance.png  

│  

├── README.md  


## Installation
To run this project, you need to have Python and Jupyter Notebook installed.

Clone this repository:  

git clone https://github.com/yourusername/mental-health-analysis.git
cd mental-health-analysis
Download the datasets from Kaggle and place them in the data directory.  
Open the Jupyter Notebook:

jupyter notebook notebooks/MFT_vibhu.ipynb  

Run the notebook cells to perform data analysis, visualization, and modeling.
## Exploratory Data Analysis (EDA)  

The project includes several visualizations to understand the data better:  
Heatmaps to show correlations between different variables.
Joint plots to explore relationships between mental disorder prevalence and DALYs.
Pair plots to visualize pairwise relationships among all variables.
Pie charts and line plots to show the distribution and variation of mental fitness over the years across different countries.
## Modeling  

Three regression models are used to predict DALYs:  
Random Forest Regression: Achieved the highest R2 score of 0.99, indicating excellent model performance.
Decision Tree Regression: Also performed well with an R2 score of 0.98.
Support Vector Machine (SVM) Regression: Performed poorly with a low R2 score.
Model Evaluation Metrics
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared Score (R2)  

## Conclusion  

The Random Forest Regression model proved to be the most effective in predicting the impact of mental and substance use disorders on DALYs. This model can be used to provide insights and assist in policy-making for mental health interventions.

## Contributing  

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.
