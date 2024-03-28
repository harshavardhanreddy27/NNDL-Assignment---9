### NNDL-Assignment---9
Neural Network and Deep Learning Assignment - 9

### Question 1:
1.The necessary libraries are imported, including pandas for data manipulation, Keras for building the neural network model, and scikit-learn for label encoding and splitting the data.
2.Data is loaded from a CSV file and preprocessed by converting text to lowercase, removing special characters, and replacing 'rt' (possibly indicating retweets) with spaces.The text data is tokenized into sequences and padded to ensure uniform length for input to the neural network.
3.The data is split into training and testing sets for model evaluation.The trained model is evaluated on the testing data to compute the test score and accuracy.
4.A new text is preprocessed similarly to the training data, tokenized, padded, and then used to make predictions using the loaded model. The predicted sentiment label is then printed out.

Question 2:

1.Same steps as Question 1 but we have to use hypertenson in question 2
2.A wrapper for the Keras model is created to be compatible with scikit-learn's GridSearchCV. The model is then trained using different hyperparameter combinations defined in the param_grid, and the best performing combination is selected based on the highest cross-validated accuracy.

### Video Link
https://drive.google.com/file/d/1FMAO2jQIRUJejgt7kiUK5YeDmp3cEYr0/view?usp=share_link
