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

You should be able to view the homepage as below :
![alt text](http://www.thepythonblog.com/wp-content/uploads/2019/02/Homepage.png)

Enter valid numerical values in all 3 input boxes and hit Predict.

If everything goes well, you should  be able to see the predcited salary vaule on the HTML page!
![alt text](http://www.thepythonblog.com/wp-content/uploads/2019/02/Result.png)

4. You can also send direct POST requests to FLask API using Python's inbuilt request module
Run the beow command to send the request with some pre-popuated values -
```
python request.py
```
