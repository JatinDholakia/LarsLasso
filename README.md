# Lars Lasso Algorithm
Visualization of the Lars Lasso regression algorithm implemented using iPython widgets.

## General info:
LARS LASSO (least absolute shrinkage and selection operator) is a regression method that performs both variable selection and regularization to reduce the model complexity for better generalizability. LARS LASSO is a combination of forward and backward selection methods.

## Parameters:
* Iterations
* Distribution - Can be Linear, Exponential or Logarithmic. Distribution of noise added to data.
* noise
* n_samples - Number of data points.
* LogAlpha - Constant that multiplies the penalty term.

## Requirements
Project is created with:
* numpy
* ipywidgets
* nbinteract
* scikit-learn
* scipy
* matplotlib
* pandas

## Setup
To run this project, follow these steps:
```
Clone this repo
$ pip install -r requirements.txt
Open larslasso.html
```

## Todo
- [ ] Add project to personal website.