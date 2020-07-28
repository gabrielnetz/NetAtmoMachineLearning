NetAtmo Machine Learning by Gabriel Netz

This is a Program developed to get data from a NetAtmo Weather Station and train a ML Model to detect the presence in a room. The data is collected through GWES-Data-Gathering server, that you can also find on the GitHub Page for this project.

What is the purpose of this

The idea of this software is developing a model to be used on the final AR app. The ML Models section trains 4 different supervised learning models and one unsupervised learning one, printing its accuracy and a batch of predictions.

We selected Logistic Regression due to its simplicity and fit to our use case, but you could use any of the other ML Models presented here.

How to use this

Import the device_data.csv.

Run the whole code once. Every different model section outputs a pickle file with the model, so you can choose what model to use. You can also re-run the code to get a better accuracy, or wrangle with the hyperparameters. Due to Machine Learning randomness nature, results will vary for different Test/Train data splits, or different data sets, so we encourage you to try different parameters

Once you have a pickle file with the model of your choice, you can run the Python Function for Predicting, with an example being available on the Presence Notification section. It currently outputs graphs over here, but you reallistically would use the function outputs in a real application.
