# Decision-Tree-Random-Forest

## Data Preprocessing. 

Transform data format/shape, shuffle the data, and deal with missing values.  

## Model Construction. 

The data consists of both categorical and continuous features  

Implement Decision Tree and Random Forest from scratch WITHOUT machine learning packages.


For the Random Forest model, I construct multiple Decision Tree models from randomly selected data (from the training subset) and perform voting for prediction.

## Validation

### a. Holdout validation with the ratio 7:3
### b. K-fold cross-validation with 𝐾=3
I split the training set (X_train.csv / y_train.csv) downloaded from the competition into training subset and validation set to perform the validation.

## Results

I obtain the performances of all experiment settings in tables by the following metrics:
### Confusion matrix
### Accuracy
### Sensitivity(Recall)
### Precision
