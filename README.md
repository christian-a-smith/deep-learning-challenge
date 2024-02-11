# deep-learning-challenge report

## Overview
This analysis was created to help determine whether applicants to Alphabet Soup funding would be successful, based on a number of criteria. Application type, affiliated industry, government organization classification, use case, organization type, active status, income amount, and ask amount were all considered for each applicant.

## Data Preprocessing

# What variables are you targeting for your model?
In this model, I am targeting the "IS_SUCCESSFUL" column for prediction. 

# What variables are the features for your model?
In my third version of the model, I featured the ask amounts, application types, affiliations, classifications, use case, organization type, and income amounts.

# What variables should be removed from the input data because they are neither targets nor features?
The variables that can be removed from the input data, as they are not relevant to the target variable or have minimal deviations across the dataset, are active status, special considerations, business name, and id.

# How many neurons, layers, and activation functions did you select for your neural network model, and why?
Across multiple iterations of the model, I selected between 110-180 neurons, 3-4 layers, and 3-4 activation functions, in addition to changing the binning of some columns, and the removal of others. All of these changes were made to experiment with obtaining the most accurate results.

# Were you able to achieve the target model performance?
I was unable to achieve the target for performance. The closest I was able to get was a 72.6% accuracy rating, and despite the numerous changes to the neurons, layers, activation functions, and epochs I was unable to increase that rating.

# What steps did you take in your attempts to increase model performance?
In the first revision of the model, I added a layer, increased the number of neurons, and changed the activation functions in an attempt to increase model performance. In the second revision, I dropped the active status and special considerations columns, as well as simplified the affiliation column by binning the more rare affiliations.

## Summary
Overall, the learning model was close, but unable to achieve the desired performance. A different model could further simplify the feature column data, or perhaps continue experimenting with the activation functions in order to achieve the target performance.