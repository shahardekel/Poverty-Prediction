# Poverty-Prediction

Many social programs have a hard time making sure the right people are given enough aid.<br>
It’s especially tricky when a program focuses on the poorest segment of the population.<br>
The world’s poorest typically can’t provide the necessary income and expense records to prove that they qualify.<br><br>
In Latin America, one popular method uses an algorithm to verify income qualification, It’s called the <b>Proxy Means Test (or PMT)</b>.<br>
With PMT, agencies use a model that considers a family’s observable household attributes like the material of their walls and ceiling, or the assets found in the home to classify them and predict their level of need.<br><br>
While this is an improvement, accuracy remains a problem as the region’s population grows and poverty declines.<br>
there is a belief that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance.<br><br>
The data contains 142 columns, with core columns:
- Id - a unique identifier for each row.
- Target - the target is an ordinal variable indicating groups of income levels.
        1 = extreme poverty
        2 = moderate poverty
        3 = vulnerable households
        4 = non vulnerable households
- idhogar - this is a unique identifier for each household. This can be used to create household-wide features, etc. All rows in a given household will have a matching value for this identifier.
- parentesco1 - indicates if this person is the head of the household.

Full data available here 
https://www.kaggle.com/competitions/costa-rican-household-poverty-prediction/data

The workflow in this project:
- import the data
- clean the data
- find relevant parameters 
- create a model
- optimize the model 
- fit and test the model
