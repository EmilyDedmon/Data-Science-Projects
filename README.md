## Seattle Data Airbnb Project

[![Exploring Airbnb's in Seattle](Airbnb. jpg)]

This exploration was to see if we could group certain Airbnb based on their scores.


#### Questions: 

I want to know the best Airbnb available 365 days a year based on their score rating, cancelation policy, and monthly reviews.
I also want to know what score rating they received based on availability.
Based on the monthly Airbnb reviews, I want to see the top selections.


#### Packages to download

Importing the following packages. Pandas for reading in and analyzing my data. Numpy for any mathematical arrays I need 
for modeling. Seaborn for visuals that I may use for my data. Matplotlib can be used with NumPy, but it also expresses math and more data 
visuals.

`pandas as pd`
`numpy as np`
`seaborn as sns`
`matplotlib.pyplot as plt`


#### Description

In this notebook, you will see how to use these packages to read your data and use functions to review, wrangle, and analyze your data. In this process, I wanted to use the columns useful for my analysis. I subsetted a few of them that seemed appropriate and made sure the missing values and any categorical variables that needed recording were removed. I also chose to use a correlation matrix to see if any of the variables were related in some way. I was then using relevant variables to plot to see what groups were clustered together.