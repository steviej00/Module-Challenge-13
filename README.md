# Module-Challenge-13


Analysis Overview of Machine Learning Models
# Objective of the Challenge:
Process data from neural network model.
Use the model-fit-predict figure to compile and evaluate a binary classification model.
Optimize model. 

## Prepare the Data for Use on a Neural Network Model:

Opened starter code file, and completed the data prep steps:
  - Read the applicants_data.csv file into a Pandas DataFrame. Look for categorical variables including columns to define features and target variables.

  - Drop the “EIN” (Employer Identification Number) and “NAME” columns from the DataFrame, they are not applicable to the binary classification model.

  - Encode the dataset’s categorical variables using OneHotEncoder, indclude encoded variables into a new DataFrame.

  - Add the original DataFrame’s numerical variables to the DataFrame containing the encoded variables.

  - Split the features(X) and target(y) for training, testing datasets. 

  - Scalce the features (X) data. 

## Compile and Evaluate a Binary Classification Model Using a Neural Network

Desing a binary classification deep learning neural network model. 

  - Establish a deep neural network by designated the number of input features, number of layers, and number of neurons on each layer using Tensorflow’s Keras.

  - Compile and fit the model using "binary_crossentropy" loss function, "adam" optimizer, and "accuracy" metrics. 

  - Evaluate the model with the test data to determine the model's loss and accuracy. 

  - Save and export model to HDF5 file and named file "AlphabetSoup.h5". 

## Optimize the Neural Network Model

Improve models accuracy by optimize model. 

  - Define two new deep neural network models (using the original model plus two optimization models). To try and improve first models accuracy. 
 
  - Run models to display accuracy scores for each model and compare the model results. 

  - Save each model as an HDF5 file. 

# Summary: 

Very minimual changes in the comparative models. I beileve working with the first model is simplest form to use for neural network model and determing accuracy score. 

