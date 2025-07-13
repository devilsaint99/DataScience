# Addressing overfitting

- Get more data.(Getting more data is not always possible)
- Feature selection, maybe based on your intiution or some methods
- Regularization -  In regularization we add extra values to the cost function to penalize the weights and prevent overfitting.


# L2 Regularization of Ridge Regression:

<img width="1033" height="315" alt="image" src="https://github.com/user-attachments/assets/44892091-8706-4d51-8097-4430a83fbb25" />

<img width="811" height="228" alt="image" src="https://github.com/user-attachments/assets/e9375785-00bf-4416-9c82-49005a5d5cdb" />


if lambda is 0 then model is overfitting or else if it is large number then it will penalize all the features making f(x) = b, refer above images for intiution by replacing lambda with 0 and large value
