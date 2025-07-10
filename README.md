The data (sample) were collected in São Paulo — Brazil, in a university, where there are some parties with groups of students from 18 to 28 years of age(average). 
The dataset used for this activity has 7 attributes, being a Target, with a period of one year.
You have to predict the quantity of beer consumption basedon the features that contain climate conditions.
Dataset Description:I.Data: date of the recordII.
Temperatura Media (C): Average temperature of the day in celsiusIII.Temperatura Minima 
(C): Minimum temperature of the day in celsiusIV.TemperaturaMaxima (C): 
Maximum temperature of the day in celsiusV.Precipitacao (mm):
Percipitation in mmVI.Final de Semana: If the day is the weekend or notVII.Consumo de cerveja (litros):
Beer consumption in litersWrite a Python code to perform the following tasks mentioned:1.Load the dataset, check its shape2.Rectify the data of the first four columns
Hint:Check columns 'Temperatura Media (C)', 'Temperatura Minima (C)', 'TemperaturaMaxima (C)', and 
'Precipitac’Fix the following errors present in these features3.Create new features using the 'Data' feature and the make 'Data' column as indexHint:Create a new feature 'Month'
from the dates, consisting of the month of the year.Create a new feature 'Day' from the dates, consisting of the day of the week.
Set values from the 'Data' column as indexes. Use code snippet:df1.set_index('Data',inplace=True)4.Handle null and duplicate values
5.Check the data typeof the features and convert them to the appropriate data type 
6.Analyze features with outlier values  
7.Plot and analyze the correlation 
8.Split the dataset for training and testing 
9.Train a linear regression model and print the intercept and coefficients 
10.Evaluate the model using the R2 score, mean absolute error, and root mean squared error 
