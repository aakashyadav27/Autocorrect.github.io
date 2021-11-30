## AUTOSPELL CHECKER
### Prerequisites
You must have Scikit Learn, Pandas (for Machine Learning Model) and Flask (for API) installed.

### Project Structure
This project has four major parts :
1.app.py - This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.
2.request.py - This uses requests module to call APIs already defined in app.py and dispalys the returned value.
3templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted employee salary.

### Running the project


1.Run app.py using below command to start Flask API
```
python app.py
```
By default, flask will run on port 5000.

2Navigate to URL http://localhost:5000
