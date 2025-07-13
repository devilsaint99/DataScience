# Addressing overfitting

- Get more data.(Getting more data is not always possible)
- Feature selection, maybe based on your intiution or some methods
- Regularization -  In regularization we add extra values to the cost function to penalize the weights and prevent overfitting.


# L2 Regularization of Ridge Regression:

<img width="1033" height="315" alt="image" src="https://github.com/user-attachments/assets/44892091-8706-4d51-8097-4430a83fbb25" />

<img width="811" height="228" alt="image" src="https://github.com/user-attachments/assets/e9375785-00bf-4416-9c82-49005a5d5cdb" />


If lambda is 0 then model is overfitting or else if it is large number then it will penalize all the features making f(x) = b, refer above images for intiution by replacing lambda with 0 and large value

Because of new cost function, the formula of gradient decsent changes
<img width="789" height="360" alt="image" src="https://github.com/user-attachments/assets/2c13c7e9-6161-4759-95cd-08f97bf63347" />
