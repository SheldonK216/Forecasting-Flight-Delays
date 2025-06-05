Project Title: Flight Delay Analysis and Prediction Framework

Author: Sheldon Khongjee

==========================================
Overview
==========================================

This project focuses on the end-to-end analysis and predictive modeling of flight delays in the United States. 
Using Python, it processes airline, airport, and flight datasets to perform exploratory data analysis (EDA), 
visualize delay patterns, examine spatial distribution of airports, and train a machine learning model to 
predict flight delays.

==========================================
Technologies and Libraries Used
==========================================

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Cartopy
- Mpl_toolkits (3D plotting)
- SimpleImputer (sklearn)
- LabelEncoder (sklearn)
- LogisticRegression (sklearn)

==========================================
Key Functionalities
==========================================

1. Data Loading and Inspection
   - Load CSV data for flights, airlines, and airports
   - Display metadata, dimensions, and missing values

2. Exploratory Data Analysis (EDA)
   - Column-wise distribution plots
   - Correlation matrices and scatter plots
   - Delay boxplots and percentile-based delay bar charts

3. Delay Type Visualization
   - Plot breakdowns of delays caused by weather, airline, and late aircraft
   - Separate visualizations for 0–90th and 90–100th percentiles

4. Airport Geospatial Visualization
   - Use Cartopy to plot airport locations on U.S. maps
   - Robinson and Lambert projections used for clarity

5. Mean Arrival Delay by Airline
   - Compute and display average arrival delay per airline
   - Merge airline metadata and visualize comparisons

6. Machine Learning: Delay Prediction
   - Create binary classification label for delayed flights
   - Impute missing data and encode categorical variables
   - Train a logistic regression model
   - Evaluate model accuracy on test set

==========================================
Folder Structure
==========================================

- flights.csv           --> Raw flight-level dataset
- airlines.csv          --> Airline reference data
- airports.csv          --> Airport reference data
- flight_delay_analysis.py --> Main Python script
- README.txt            --> This file

==========================================
How to Run
==========================================

1. Install required libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn cartopy

2. Place the CSV files in the same directory as the script

3. Run the script:
   python flight_delay_analysis.py

4. Outputs include:
   - Statistical summaries
   - Multiple plots for EDA
   - Geographic visualizations
   - Delay prediction accuracy

==========================================
Acknowledgments
==========================================

This project was developed to explore real-world applications of data analysis 
and machine learning using publicly available flight data. Inspired by 
data science best practices and visualization techniques from:

- Scikit-learn documentation
- Matplotlib/Seaborn galleries
- Cartopy geospatial toolkit examples
- Aviation data on Kaggle

==========================================
CONTACT
==========================================

GitHub: https://github.com/SheldonK216/Forecasting-Flight-Delays
Email: sheldonkjee216@gmail.com
