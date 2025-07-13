# Addressing overfitting

- Get more data.(Getting more data is not always possible)
- Feature selection, maybe based on your intiution or some methods
- Regularization -  In regularization we add extra values to the cost function to penalize the weights and prevent overfitting.


# L2 Regularization of Ridge Regression:

<img width="1033" height="315" alt="image" src="https://github.com/user-attachments/assets/44892091-8706-4d51-8097-4430a83fbb25" />

<img width="811" height="228" alt="image" src="https://github.com/user-attachments/assets/e9375785-00bf-4416-9c82-49005a5d5cdb" />


If lambda is 0 then model is overfitting or else if it is large number then it will penalize all the features making f(x) = b, refer above images for intiution by replacing lambda with 0 and large value

Because of new cost function, the formula of gradient descent changes
<img width="789" height="360" alt="image" src="https://github.com/user-attachments/assets/2c13c7e9-6161-4759-95cd-08f97bf63347" />


# How shrinkage of weights occur

Basically if you carefully look at the new gardient descent update formula you will see that instead of w - alpha * dj/dw, now w is multiplied to value slightly smaller than 1.

<img width="1274" height="372" alt="image" src="https://github.com/user-attachments/assets/512ca5dc-1c1c-4d76-b28e-4cd4ea7d9b9d" />

