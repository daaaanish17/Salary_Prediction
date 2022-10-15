# Salary_Prediction
This is a demo project to elaborate how Machine Learn Models are deployed on production using Flask API




*This project has four major parts :*

model.py - This contains code fot our Machine Learning model to predict employee salaries absed on trainign data in 'hiring.csv' file.

app.py - This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.

request.py - This uses requests module to call APIs already defined in app.py and dispalys the returned value.

templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted employee salary.
