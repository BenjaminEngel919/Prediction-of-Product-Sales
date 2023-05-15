# Prediction-of-Product-Sales
## Analysis of Item Sales

**Author: Benjamin Engel**

## Business Problem:

    What Store Type should we build next?
    Which Model would be best predict Outlet Sales?

#### Data: Excel Data Sheet with data about Item Outlet Sales, Outlet Type and Size.
#### Outlet Establishment Year, Item Type and MRP.
#### Fat Content, Item Visability and Weight.


## Methods
    First we had to load, clean and inspect the data.
    Then we did Exploratory and Explanatory Data Analysis.
    Finally we did Modling with multiple types of Linear Regression Modling taking into account Regression Metrics.


## Results

    Visual 1

![image](https://user-images.githubusercontent.com/126991382/236390597-6ea3ec89-b4e8-4261-972b-418acf305fda.png)

    Visual 2

![image](https://user-images.githubusercontent.com/126991382/236390260-c42b9253-866e-40b6-8231-b7a1243019d7.png)

    Visual 3

![image](https://user-images.githubusercontent.com/126991382/236390659-48eef6d4-913a-4aac-8194-6acf2ea62bad.png)
    
    Visual 4

![image](https://user-images.githubusercontent.com/126991382/236390710-404c0856-cca3-4a95-9ea3-4ec2239e2b39.png)

    Visual 5

![image](https://user-images.githubusercontent.com/126991382/236391404-0ed80730-a248-42b8-b33c-f691cc4e9f6e.png)


## Models

    -Linear Regression Train Scores
    -MAE: 847.6553 
    -MSE: 1,298,674.2664 
    -RMSE: 1,139.5939 
    -R2: 0.5609

    -Linear Regression Test  Scores
    -MAE: 810.3803 
    -MSE: 1,210,308.6412 
    -RMSE: 1,100.1403 
    -R2: 0.5679
    
    Tuned Decision Tree
    -Linear Regression Train Scores
    -MAE: 847.6553 
    -MSE: 1,298,674.2664 
    -RMSE: 1,139.5939 
    -R2: 0.5609

    -Linear Regression Test  Scores
    -MAE: 810.3803 
    -MSE: 1,210,308.6412 
    -RMSE: 1,100.1403 
    -R2: 0.5679
    
        -Bagged Tree Train Scores
    -MAE: 326.7676 
    -MSE: 245,996.1809 
    -RMSE: 495.9800 
    -R2: 0.9168

    -Bagged Tree Test Scores
    -MAE: 800.9113 
    -MSE: 1,335,594.8783 
    -RMSE: 1,155.6794 
    -R2: 0.5232
    
    Linear Regression Percentage Error: 37.15%
    Decision Tree Percentage Error: 34.08%
    
   Recommendations:
    Model Recommendation, Tuned Decision Tree
  - Tuned Decision Tree had the lowest MAE of 743.4843.  Our model was off on it's predictions by $743.48.  
  - Error percentage of 34.08%.  
  - Fairly lower error percentage on Decision Tree vs Linear Regression.
  - The Root Mean Squared Error is also slightly lower for the Decision Tree. This means that there are less outliers throwing off the weight of our        model.
  - Both models had good balance. The Tuned Decision Tree once again was slightly better.
    Next Store type to build definitely would be a Supermarket Type 3
    I would Recommend a Tuned Decision Tree Model. But don't put 100% faith in it. More like 60%.
