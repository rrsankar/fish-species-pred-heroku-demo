# Fish Species Prediction

The objective of this project is to build a web application that display the fish specie when a set of features are given as input.

The dataset contains 7 species of fish and the features "weight", "length1", "length2", "length3", "height" and "width".

Here is the link to the dataset. https://www.kaggle.com/aungpyaeap/fish-market

### Installation:

    1. Clone/download the repo to your local.
    2. Create a virtual environment (this application was built and test on Python 3.6)
    3. Run the requirements.txt (pip install -r requirements.txt)

### Running the application:
 
    1. After the environment is setup, Run main.py.
    2. A flask server will be up and running and a link to the webpage will be outputted. Go to the link.
    3. Insert necessary values for the fields and click Predict.

### Deployment:

The application is deployed on Heroku.

The Procfile in the repo, facilitates the deployment process.

The deployed application can be accessed here, 

https://fish-species-predict-demo.herokuapp.com/

### Main tools used:

* [flask](https://flask.palletsprojects.com/en/1.1.x/) - Web framework
* [scikit-learn](https://scikit-learn.org/0.22/getting_started.html) - Machine Learning library

Please check the requirements.txt file to see all the tools and their versions.

### ML Model:

The repo contains a jupyter notebook -> "model_training.ipynb".

This notebook can be used to train the model.

The dataset is also present in the repo -> "fish_dataset.csv".

A model is already trained and used currently for prediction -> "fish_classifier.pkl".

The model was trained using "RandomForestClassifier" and obtained an accuracy score of 80 %.

The model is loaded when the flask server goes up.

