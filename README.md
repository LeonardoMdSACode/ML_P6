# Linear & Lasso Regression Modele

"The Lasso is a linear model that estimates sparse coefficients. It is useful in some contexts due to its tendency to prefer solutions with fewer non-zero coefficients, effectively reducing the number of features upon which the given solution is dependent. For this reason, Lasso and its variants are fundamental to the field of compressed sensing. Under certain conditions, it can recover the exact set of non-zero coefficients (see Compressive sensing: tomography reconstruction with L1 prior (Lasso)).

Mathematically, it consists of a linear model with an added regularization term. The objective function to minimize is:

 \min_{w} { \frac{1}{2n_{\text{samples}}} ||X w - y||_2 ^ 2 + \alpha ||w||_1}"
[1]

### Classification Metrics

1. Linear Regression Model
  
   Test r^2 Error:  0.7954751007064392

2. Lasso Regression Model
   
   Test r^2 Error:  0.7940197883277862


[1] - <https://scikit-learn.org/stable/modules/linear_model.html>