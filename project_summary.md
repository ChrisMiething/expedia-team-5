## Title

Expedia Hotel Recommendations - Team 5

## Team/Roles

1. Christian - Superman
2. Michael - Ironman
3. Hamza - Batman

## Scope

Create a machine learning model to predict the probability that a user will book a specific hotel cluster.

## Objective

Predict the likelihood of a user booking a hotel cluster.

## KPI

MAP@5 (Mean Average Precision @ 5):

$$
MAP@5 = \frac{1}{|U|} \sum_{u=1}^{|U|} \sum_{k=1}^{\min(5, n)} P(k)
$$

1. Number of User Events |U|
2. Precision at Cutoff P(k)
3. Number of Predicted hotel Clusters (n)

## Deliverables

- up to 5 predictions for each user event
- Presentation

## DoR / DoD

DoR: 
- The Card is well defined (Title, Description, Sub-tasks)
- Acceptance criteria are clearly defined and agreed upon
- The Card can be completed within one day
- Dependencies are identified and managed

DoD:
- All acceptance criteria are met
- Code has been peer-reviewed and merged into the main branch
- The team has reviewed and accepted the story
