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
- **Source**: Canadian government open datasets on vehicle fuel consumption and emissions.
- **Key Features**:
  - Vehicle Class
  - Engine Size
  - Transmission Type
  - Fuel Type
  - Fuel Consumption Rates (City, Highway, Combined)
  - CO₂ Emissions
  - Environmental Rating

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

## Project Structure
- Raw and cleaned datasets
- Data cleaning, EDA, and modeling notebooks
- SQL scripts for database management and queries
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
This project is for educational and research purposes only.
