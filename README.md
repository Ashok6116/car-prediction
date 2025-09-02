# car-Price-prediction

This is a historical data on used car prices from CarDekho, including various features such as make, model, year, fuel type, transmission type, and other relevant attributes from different cities. I develop a machine learning model that can accurately predict the prices of used cars based on these features. I has integrated this model into a Streamlit-based web application to allow users to input car details and receive an estimated price instantly.

I have done,
  1.Data Processing
    a).Import and concatenate
    b).Handling Missing Values: Identify and fill or remove missing values in the dataset.
    c).Standardising Data Formats.
    d).Encoding Categorical Variables. 
    e).Normalizing Numerical Features.
    f).Removing Outliers: Identify and remove or cap outliers in the dataset to avoid skewing the model.

  2.Exploratory Data Analysis (EDA)
    a).Descriptive Statistics: Calculate summary statistics to understand the distribution of data.
        Mean, median, mode, standard deviation, etc.
    b).Data Visualization: Create visualizations to identify patterns and correlations.
        Used scatter plots, histograms, box plots, and correlation heatmaps.
    c).Feature Selection: Identify important features that significantly impact the car prices.
        Used techniques like correlation analysis, feature importance from models, and domain knowledge.

  3.Model Development
    a).Train-Test Split: Splited the dataset into training and testing sets to evaluate model performance.
    b).Model Selection: I Choosed appropriate machine learning algorithms for price prediction.
    c).Model Training: Trained the selected models on the training dataset.
        Used cross-validation techniques for ensure robust performance.
    e).Hyperparameter Tuning: Optimize model parameters to improve performance.
        (Used techniques like Grid Search or Random Search.)

  4.Model Evaluation
    a).Performance Metrics
      Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared.
    b).Model Comparison: Compared different models based on evaluation metrics to select the best performing model.

  5.Optimization
  
  6.Deployment
    a).Streamlit Application: Deployed the final model using Streamlit to create an interactive web application.
        allowed users to input car features and get real-time price predictions.

  7.Results: 
    A functional and accurate machine learning model for predicting used car prices.
    An interactive Streamlit application for real-time price predictions based on user input.


Technical skills:
Data Preprocessing, Machine Learning, Price Prediction, Regression, Python, Pandas, Scikit-Learn, Exploratory Data Analysis (EDA), Streamlit, Model Deployment

