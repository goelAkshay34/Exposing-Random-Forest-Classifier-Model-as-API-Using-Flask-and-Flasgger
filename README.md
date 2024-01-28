# Exposing Random Forest Classifier Model as API Using Flask and Flasgger
 Exposing Random Forest Classifier Model as API Using Flasgger

 Steps
 1. Initially we have build a Random Forest Classifier model using sklean library
 2. Then we have loaded the model in .pkl file using pickle library
 3. We have used flask library to expose the model using http request
 4. We have utilized the Flagger library to load the input data / file into http request 
    which will request the flask to get the output and print it back on the localhost.