# Drug_Solubility
> The study objective: ML for drug solubility prediction. 


## Table of contents
* [General info](#general-info)
* [Drug solubility]
* [Packages and approaches](#R)
* [Status](#status)
* [Inspiration](#inspiration)
* [Files](#files) 

## General info
Drug solubility has an important physicochemical role in Drug discovery, design and development.

## Drug solubility
More than 40% of new drug-like molecules are not water soluable. Solubility is still a challenge for optimization of molecules. Drugs must be present in the form of solution at the site of absorption.

[Drug solubility](https://www.hindawi.com/journals/isrn/2012/195727/)


## Packages and approaches
rdkit, sklearn, pandas, numpy,matplotlib,


#### Code Example - model.predict
    Y_pred_train = model.predict(X_train)
    
    print('Coefficients:', model.coef_)
    print('Intercept:', model.intercept_)
    print('Mean squared error (MSE): %.2f'
        % mean_squared_error(Y_train, Y_pred_train))
    print('Coefficient of determination (R^2): %.2f'
        % r2_score(Y_train, Y_pred_train))
 
  
## Status
Project is completed.

## Inspiration
Characterizing a prediction ML model for drug molecule solubility.

## Files 
Ref codes: https://github.com/melaniaAB/Drug_Solubility.git
