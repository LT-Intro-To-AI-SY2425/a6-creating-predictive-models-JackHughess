# Part 1 - Linear Regression Writeup

After completing `a6_part1.py` answer the following questions

## Questions to answer

1. What is the r squared value?  What does this say about this linear regression model?

The r squared value shows how well that the line fits the data. It shows how far, on average, the distance to each point from the line is squared on a scale from 0 to 1. This says that the value is .626 meaning that the line doesn't fit the data very well which could be because of other factors that we are not taking into account.

2. According to your model, what is the predicted systolic blood pressure for a person who is 42 years old?

137.46185286

3. How accurate do you think this model's predictions are?  Do you think this model is accurate enough to reliably predict someone's blood pressure based on their age?  Why or why not?  And if not, what could improve the model?

I think it is more like an estimate but I would not use it to predict blood pressure reliably because the r^2 is only .62. Most scientific data sets require a r^2 of .95 or higher so I wouldn't use this. To improve the model we could give it more data and also add more features to explain all of the varience.