# DSI-course-materials
All course materials for the statistical learning section of the introductory data science course coming soon to the University of Toronto's Data Science Institute.

This course is adapted from *An Introduction to Statistical Learning: with Applications in R* by James, Gareth, et al. (2021).

Author: Simone Collier (contact: simonekcollier@gmail.com)

## Statistical Learning Modules

This repo is divided into 11 modules, each containing lecture slides, lesson plans, and exercises in R. The list below provides an overview for what is covered in each module.

1. **Introduction to Statistical Learning**
    * Supervised versus unsupervised learning
    * Prediction versus inference
    * Parametric and nonparametric methods for estimation
    * Prediction accuracy and model interpretability trade-off
    * Regression versus classification
    * Measuring the quality of fit
    * Bias-variance trade-off
    
2. **Linear regression**
    * Simple and Multiple Linear Regression
        * Estimating the coefficients and assessing accuracy
        * Assessing accuracy of the model (ex: Residual standard error, R2 Statistic)
    * Other Considerations
        * Qualitative predictors
        * Modification of the additive assumption
        * Potential problems (ex: non-linearity, correlation of error, outliers)

3. **Classification**
    * Logistic regression
    * Generative models for classification
        * Linear discriminant analysis
        * Quadratic discriminant analysis
        * Naive Bayes
    * K-nearest neighbours
    * Generalised linear Models

4. **Resampling Methods**
    * Cross-validation
        * Leave-one-out Cross-Validation
        * k-Fold Cross-Validation
            * Bias-Variance Trade-Off
        * Classification Problems
    * Bootstrap
    
5. **Linear model selection and regularisation**
    * Subset Selection
        * Best subset selection
        * Stepwise selection (forward, and backward)
        * Choosing the optimal model
            * Cp, AIC, BIC, Adjusted R2
            * Validation and Cross-Validation
    * Shrinkage
        * Ridge Regression
        * Lasso
        * Selecting the Tuning Parameter

6. **Beyond Linearity**
    * Polynomial Regression
    * Step Functions
    * Regression Splines
    * Smoothing Splines
    * Local Regression
    * Generalised Additive Models
    
7. **Tree-Based Methods**
    * Decision Tree Basics
        * Regression Trees
        * Classification Trees
        * Tree pruning
        * Advantages and disadvantages of Trees
    * Bagging
    * Random Forests
    * Boosting
    * Bayesian Additive Regression Trees

8. **Support Vector Machines**
    * What is a hyperplane?
    * Maximal Margin Classifier
    * Support Vector Classifiers
    * Support Vector Machines
        * Classification with non-linear decision boundaries
        * SVM with more than two classes
            * One-versus-one classification 
            * One-versus-all classification

9. **Survival analysis and Censored Data**
    * Survival and Censoring Times
    * The Kaplan-Meier Survival Curve
    * The Log-Rank Test
    * Regression Models with a Survival Response
        * The Hazard Function
        * The Proportional Hazards Assumption
        * Cox’s proportional hazards model
        
10. **Unsupervised learning**
    * Principal Components Analysis (PCA)
        * The Proportion of Variance
        * Uses for principal components
        * Missing Values and matrix Completion
    * Clustering Methods
        * K-means Clustering
        * Hierarchical Clustering

11. **Ethics, Inequity, and Reproducibility**
    * Reproducibility
        * Pineau, J. et al. 2021. Improving Reproducibility in Machine Learning Research. Journal of Machine Learning Research 22: 1–20.
        * Tatman, R., J. VanderPlas, and S. Dane. 2018. A Practical Taxonomy of Reproducibility for Machine Learning. 2nd Reproducibility in Machine Learning Workshop at ICML. Stockholm, Sweden.
    * Ethics
        * Mittelstadt, B. D., et al. 2016. The ethics of algorithms: mapping the debate. Big Data & Society.
    * Inequity
        * Bias in algorithms – case study: Obermeyer, Powers, Vogeli, Mullainathan, 2019, ‘Dissecting racial bias in an algorithm used to manage the health of populations’, Science.
