# xG-model-for-use-with-sofascore
A guide to creating and applying an xG model using sofascore data

I created this project to find the expected goals data for league of ireland games without using premium sports data platforms (opta, wyscout etc.). 

Part 1 covers some data exploration creates a logistic regression model for calculating expected goals. This was heavily inspired by this repository https://github.com/iandragulet/xG_Model_Workflow

I highly recommend reading it for essential background in the expected goals metric and its statistical significance.

Part 2 Applies the model to sofascore data and covers data manipulation, cleansing and conversion from sofascores data format to a format that fits with the model. 

Part 3 is an example python visualisation using the model and sofascore data.
