# SpaceX Falcon 9 Landing Prediction Project

## Project Overview
SpaceX's Falcon 9 rocket is designed to be reusable, with its first stage booster capable of landing back on Earth after launch. This reusability drastically reduces the cost of space travel, making Falcon 9 launches much more cost-effective compared to traditional rockets. However, the success of each landing depends on a variety of factors such as payload mass, weather conditions, launch site, and booster version.

This project focuses on predicting the outcome of Falcon 9 booster landings using data science techniques. By analyzing historical data from SpaceX launches and applying machine learning algorithms, we aim to forecast whether a booster will successfully land after launch. The project also explores the potential for improving launch planning and reducing risks through accurate predictions, which is critical for cost management and resource optimization.



## Objectives
- **Collect and clean data** on SpaceX Falcon 9 launches.
- Perform **Exploratory Data Analysis (EDA)** to identify key variables influencing landing success.
- **Build predictive models** using various machine learning algorithms to forecast landing outcomes.
- **Visualize results** through interactive dashboards and maps to gain insights.

## Tools and Technologies
- **Python** for data analysis and machine learning.
- **Pandas**, **NumPy** for data manipulation and cleaning.
- **Matplotlib**, **Seaborn** for data visualization.
- **Scikit-learn** for building machine learning models.
- **SQL** for querying launch data.
- **Folium** for creating interactive maps.
- **Plotly Dash** for dashboard visualization.

## Data Collection and Preparation
- Data was sourced using SpaceX's API and web scraping techniques.
- Key variables include launch sites, payload mass, weather conditions, and booster version.
- After collecting the raw data, extensive cleaning and wrangling were performed to make the dataset suitable for analysis.

## Exploratory Data Analysis (EDA)
- Initial analysis focused on understanding the distribution of launch outcomes, identifying trends, and exploring relationships between variables such as payload mass and landing success.
- Data visualization techniques like histograms, scatter plots, and correlation matrices were used to reveal insights.

## Machine Learning Models
- We used several machine learning algorithms to predict the likelihood of a successful Falcon 9 landing:
  - **Logistic Regression**
  - **Random Forest**
  - **Support Vector Machines (SVM)**
- Model performance was evaluated using metrics like accuracy, precision, recall, and F1 score.

## Results
- The Random Forest model achieved the highest accuracy in predicting landing outcomes.
- Key variables such as payload mass, booster version, and launch site played a significant role in determining landing success.

## Visualizations and Interactive Tools
- **Folium** was used to map the launch sites and visualize the success of landings across different locations.
- A **Plotly Dash dashboard** was created to interactively explore launch data and prediction results.

## Conclusion
This project demonstrates how data science can be applied to predict the landing success of reusable rockets like the Falcon 9. By improving the accuracy of these predictions, SpaceX can continue to innovate in reducing space travel costs.

## Files in this Repository
- `1.Task-SpaceX-Falcon9-LandingPrediction.ipynb`: Notebook for collecting launch data via API and web scraping.
- `2.TaskSpaceX-Falcon9-WebScraping.ipynb`: Web scraping techniques to gather supplementary data.
- `3TaskSpaceX-Falcon9-DataWrangling.ipynb`: Cleaning and transforming the raw data for analysis.
- `5.TaskSpaceX-Falcon9-Visualization.ipynb`: Exploratory Data Analysis and visualizations.
- `6.TaskSpaceX-Falcon-MapVis.ipynb`: Interactive map visualizations using Folium.
- `7.TaskSpaceX_dash_app.ipynb`: Interactive map visualizations using Folium.
- `8.TaskSpaceX-Falcon9-MachineLearning.ipynb`: Machine learning models for predicting landing success..
- Various `.csv` files: Cleaned and processed datasets used in the project.
