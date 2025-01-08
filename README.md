# Resturant profits
### Linear Regression Predictions

This project demonstrates implementing linear regression with one variable to predict profits for a restaurant franchise.

### 2 - Problem Statement

Suppose I am the CEO of a restaurant franchise and am considering different cities for opening a new outlet.

- I would like to expand my business to cities that may give my restaurant higher profits.
- The chain already has restaurants in various cities, and I have data for profits and populations from these cities.
- I also have data on cities that are candidates for a new restaurant.  
    - For these cities, I have the city population.

### Goal:
Can I use the data to help me identify which cities may potentially give my business higher profits?

In this project, I use linear regression to predict profits based on city population data. By analyzing the data, I aim to provide insights into which cities might be ideal for opening new restaurant outlets, based on their population size and predicted profit.
### Calculations 
Calculations are performed in the Jupyter Notebook.

### Results:

1. **Prediction Context**:  
   The output shows predictions for profits based on a linear regression model that takes the population size of a city as input.  
   The model uses a formula:  
   $$f_{w,b}(x) = wx + b$$  
   where `w` is the weight (slope), `b` is the bias (intercept), and `Population` is the input in thousands.

2. **Results**:
   - For **Population = 35,000**:  
     The model predicts a **profit of $4,519.77**.
     

     This means, based on the trained parameters, a city with a population of 35,000 people is expected to yield this profit.  
   
   - For **Population = 70,000**:  
     The model predicts a **profit of $45,342.45**, indicating the expected profit from a city with 70,000 people.

3. **Purpose**:  
   These predictions demonstrate the model's ability to provide insights into potential profits based on population size, helping businesses make informed decisions.
