# Disruptive_Technologies
Final project for the course Disruptive Technologies

Communities and crime dataset and description: http://archive.ics.uci.edu/ml/datasets/communities+and+crime

# Main idea
Main idea is to make prediction for several cases :

***Case 1 : Try to predict missing data about police officers and see is there any impact on target variable.*** 

***Case 2 : Create dummy variable for 1 if there is more than 100 pollice officers in population , 0 less then 100.***

In the end compare those two predictions!

The normalization preserves rough ratios of values WITHIN an attribute (e.g. double the value for double the population within the available precision - except for extreme values (all values more than 3 SD above the mean are normalized to 1.00; all values more than 3 SD below the mean are normalized to 0.00)).

# Problem description
In this dataset target variable is violence per population, my goal is to find variables with strong predictive power for target variable.

# Main problem:
Main problem is missing huge amount of police data. As described in previous line first i will try predict Police data in order to have better power prediction later in building the final model.

Then on the second model i will create variable dummy instead of missing data and we will see how will that perform.
