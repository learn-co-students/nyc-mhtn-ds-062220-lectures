# Classification Bake-off:

The goal of this bake off if for students to practice the data science process and handling . Through this process, you will need to clean and prepare the data, engineer features, fit different models, tune the hyperparameters of those models, and account for how any class imbalance can affect your model.

## Data Set Information:

This dataset contains information about customers' credit card default payments in Taiwan. It was taken from a study that compares the predictive accuracy of probability of default among six data mining methods. This data set is not as clean as some of the data you have previously received. Below is all of the information that is given about the different columns of data. As you explore this data you will find that the 'data dictionary' below does not include all of the values that you will find in the actual dataset. You will have to make decisions on your own as to how you will interpret and handle these unknown values.  

## Evaluation:

For this bake-off, we will be scoring the submitted predictions using the F1 score.


## Attribute Information:

This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:
X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
X2: Gender (1 = male; 2 = female).
X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
X4: Marital status (1 = married; 2 = single; 3 = others).
X5: Age (year).
X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.
X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.
