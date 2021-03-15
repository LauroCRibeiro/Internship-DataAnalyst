## Deploying ML Model using Flask
It is a simple project to elaborate on how to deploy a Machine Learning model using Flask API.

### Prerequisites
It would be best to have Scikit Learn, Pandas (for Machine Learning Model), and Flask (for API) installed.

Flask version: 1.1.2
conda install flask (or) pip install Flask

### Create a virtual environment
pip install virtualenv

virtualenv salary-env

- Mac OS / Linux: source mypython/bin/activate
- Windows: mypthon\Scripts\activate

### Project Structure
This project has four major parts :
1. model.py - This contains code for our Machine Learning model to predict employee salaries based on training data in the 'hiring.csv' file.
2. app.py - This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.
3. template - This folder contains the HTML template (index.html) to allow the user to enter employee detail and displays the predicted employee salary.
4. static - This folder contains the CSS folder with style.css file, which has the styling required for out index.html file.

### Running the project
1. Ensure that you are in the project home directory. Create the machine learning model by running below command from command prompt -
```
python model.py
```
This would create a serialized version of our model into a file model.pkl

2. Run app.py using the below command to start Flask API
```
python app.py
```
By default, Flask will run on port 5000.

3. Navigate to URL http://127.0.0.1:5000/ (or) http://localhost:5000

You should be able to view the homepage.

Enter valid numerical values in all three input boxes and hit Predict.

If everything goes well, you should be able to see the predicted salary value on the HTML page!
check the output here: http://127.0.0.1:5000/predict

