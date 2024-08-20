# Practical Application Assignment 17.1

## Notebook linked [here](https://github.com/Raesu/pcmlai-mod17/blob/main/prompt_III.ipynb)

### Intro
The classification goal is to predict if a client will subscribe (yes/no) to a term deposit (y). Data files described below:
- bank-additional-full has all examples 41188 and 20 inputs ordered by date May 2008 to November 2010
- bank-additional.csv has 10% of the full set (for training SVM model if it is too slow)
- bank.csv


### Objective
The business objective is to predict if a client will subscribe to a term deposit. This will likely be used by the bank's phone center to improve revenue. I think the insights should have two goals, ranked by importance:
- Create a model that most accurately can maximize sales (the yes case). Interpretability is nice but is not required. This will help the phone center prioritize their calling time.
- If the model is interpretable, provide the business group with insights to help them find more marketing leads of a certain profile (likely purchasers). This will make their acquisition costs more efficient.

### Suggestions for Bank
I would suggest using this logistic classification model to prioritize calls in the call center. This should maximize their calling success (looking for the "yes" answer) and improve their operations rapidly.

Beyond that, I would analyze the coefficients in the model to identify where the bank should find more customers for their sales funnel. This will give them demographic info they can use to purchase lead lists, or access within their own CRM. This may also help them refine their pitch.