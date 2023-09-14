# Real-Time-ASL-Alphabet-Recognition
A program that detects alphabet signs in American Sign Language (ASL) and displays the corresponding alphabet in real time.

## Setting up the project
You can install all the requirements needed to run the project either directly or in a virtual evnironment by running this command on your terminal:

pip install -r requirements.txt

## Other Information
The order in which the code should be run is:
* data_collection.py
* data_preprocessing.py
* classifier_training.py
* classifier_testing.py

I have included the model I trained when making the project in case you just want to go ahead and see the results. In that case, you only need to run 'classifier_testing.py' but note that I used my left hand when training the classifier so you have to use yours as well in order to get the accurate predictions.
