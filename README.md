# car-emission-forecast

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Project Structure](#project-structure)
- [Results Highlights](#results-highlights)
- [Future Work](#future-work)
- [License](#license)

## Project Overview
This project aims to explore the relationship between vehicle characteristics and their environmental performance in Canada. Using a data-driven approach, the study applies statistical analysis and machine learning models to predict fuel consumption, emissions, and environmental ratings based on vehicle specifications such as engine type, transmission, and fuel type.

## Dataset
The dataset used in this project is obtained from the Government of Canada's open data portal, specifically the Vehicle Fuel Consumption Ratings and Emissions datasets.  
It provides detailed information on vehicle specifications, fuel efficiency, CO₂ emissions, and environmental ratings for vehicles sold in Canada.

- **Source**: https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64

- **Key Features**:
  - Vehicle Class
  - Engine Size
  - Transmission Type
  - Fuel Type
  - Fuel Consumption Rates (City, Highway, Combined)
  - CO₂ Emissions
  - Environmental Rating

This dataset serves as the basis for analyzing the relationships between vehicle attributes and their environmental performance.

## Methodology
1. **Data Cleaning**
   - Handle missing values and inconsistent records.
   - Standardize feature formats.

2. **Exploratory Data Analysis (EDA)**
   - Analyze fuel efficiency, emission patterns, and environmental ratings across different vehicle groups.

3. **Model Building**
   - **Regression Models**: Predict continuous targets (e.g., fuel consumption, CO₂ emissions).
   - **Classification Models**: Predict categorical targets (e.g., environmental ratings).
   - Techniques used: Linear Regression, Ridge Regression, Decision Tree, K-Nearest Neighbors (KNN).

4. **Model Evaluation**
   - Applied cross-validation and performance metrics such as RMSE, Accuracy, and Confusion Matrix to assess model performance.

## Requirements

Before running this project, please ensure the following requirements are met:

- **Python 3.8+**  
- **Libraries**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - mysql-connector-python

You can install the required libraries using:

```bash
pip install -r requirements.txt
```
- **Database:**
  - AWS account with an RDS (MariaDB) instance properly set up.
  - Credentials (host, port, username, password) configured for database connection.
- **Environment:**
  - Jupyter Notebook or compatible IDE (e.g., VS Code, PyCharm).

## Project Structure
- Raw and cleaned datasets
- Data cleaning, EDA, and modeling notebooks
- SQL scripts for database management, queries, and AWS RDS (MariaDB) integration
- Summary of findings and results
- Project documentation

## Results Highlights
- Identified significant vehicle features affecting emissions and environmental ratings.
- Developed predictive models with reasonable accuracy, providing insights for greener vehicle choices.

## Future Work
- Integrate more recent datasets to update models.
- Explore advanced machine learning methods such as Random Forest or Gradient Boosting.
- Analyze the impact of emerging vehicle types like electric and hybrid vehicles.

## License
This project is intended for educational and research purposes only.  
It includes examples of SQL database management and cloud database integration using AWS RDS (MariaDB).  
Please ensure appropriate credential management and access controls when deploying similar database solutions in production environments.
