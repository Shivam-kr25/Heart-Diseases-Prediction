### Overview

HEART DISEASES PREDICTION is a web application that is developed using the machine learning Logistic Regression, Naive Bayes and KNN algorithm. The technology used for deployment is Flask and Heroku. Tools used Sklearn, Python, Bootstrap. The GUI of this web application is more user-friendly so that normal people can easily check their Heart diseases.

  
**A Demo of the Web App :**

![Heart_disease](https://github.com/asthasharma98/Heart-Disease-Prediction-Deployment/blob/master/Readme_resources/heart_disease.gif)
 
 
 ### Technical Aspect
 
 This Project is mainly divided into two parts:
 
 1. Exploring the dataset and traning the model using `Sklearn`.
 2. Building and hosting a `flask` web app on `Heroku`.

**About the repository Structure :**

- Project consist `app.py` script which is used to run the application and is engine of this app. contians API that gets input from the user and computes a predicted value based on the model.
- `prediction.py` contains code to build and train a Machine learning model.
- *templates* folder contains two files `main.html` and `result.html` which describe the structure of the app and the way this web application behaves. These files are connected with Python via Flask framework.  
- *static* folder contains file `style.css` which adds some styling and enhance the look of the application. 

### Installation

The Code is written in Python 3.8. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

```
pip install -r requirements.txt 
```

*To clone the repository*

```
git clone https://github.com/Shivam-kr25/Heart-Diseases-Prediction
```

### Run 

*To Run the Application*

```
python app.py
```

### Deployement on Heroku

Install Heroku CLI as this makes it easy to create and manage your Heroku apps directly from the terminal. 
You can download it from [here](https://devcenter.heroku.com/articles/heroku-cli).

next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

### Technologies used 

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)  

[![Heroku](https://github.com/jalbertsr/logo-badge-images/blob/master/img/rsz_heroku.png?raw=true)](https://www.heroku.com/)

[![Flask](https://github.com/jalbertsr/logo-badge-images/blob/master/img/rsz_flask.png?raw=true)](http://flask.pocoo.org/)  


### Future work 

- improve model performance.
- Add more better styling to the user interface.

**Some Useful Resources**

- **Flask Quickstart Documentation** : [https://flask.palletsprojects.com/en/1.1.x/quickstart/](https://flask.palletsprojects.com/en/1.1.x/quickstart/)







