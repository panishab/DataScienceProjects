## Objective
The goal of this project is to  predict the price of a used Toyota Corolla based on its specification.
## Data
Used  this data ToyotaCorolla.csv( datahttps://www.dropbox.com/s/wzmj60pufhysc9r/ToyotaCorolla.csv?dl=1)  provided by the instructor. The data has 1436 records and details on 38 attributes.
 ## Solved Question:
 1. Fitting the neural network model to the data.
 2. Using single hidden layer with 2 nodes.
 3. Using predictors Age_08_04, KM, Fuel_Type, HP, Automatic, Doors, Quarterly_Tax, Mfr_Guarantee, Guarantee_Period, Airco, Automatic_airco, CD_Player, Powered_Windows, Sport_Model, and Tow_Bar.
 4. Converting Categorical  predictors to dummies variables
 5. Training and Testing the data set with random_state=1
 6. Repeating the process with changing the number of hidden layers and nodes  with single layers with 5 nodes and two layers, 5 nodes in each layer.
 7. Comparing the RMS for the training and testing data  as the number of layers increases.
## Findings
The RMS error for the training data typically goes down as the number of layers and nodes rises. In this specific case, we can see that the RMSE for the training data decreased as the numbers layers and node increased.However,In validataion data,the second RMSE is increased when nodes and layers both increased. Hence, it can suggest that the single hidden layer with 2 nodes may be sufficient for this application.

 
