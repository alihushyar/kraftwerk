Assignment 5.1:  “Will a customer accept the coupon?”
https://github.com/alihushyar/kraftwerk/blob/main/prompt.ipynb

# There is a baseline of 41% of bar coupons that are accepted. 
# It is clear that those patrons who go often (more than 3 times a month) accept coupons at a higher rate (76% vs 37%)
# Regarding age, there is no real difference in acceptance rate - under 25 and over 25 have similar acceptance rates (67% and 69%)
# Those whose passengers were not children also have a higher acceptance rate in the 70% range
# Finally, financial situation is not a driver as bar coupons are not accepted that much more (44%) over the baseline for those who frequent cheap restaurants with lower incomes

Independent Investigation:

# For those who drink coffee at least once a month, almost 66% of all Coffee coupons were accepted
# 81% acceptance rate when coupon is received at 10AM - 7AM is too early and doesn't move the needle!
# Surprisingly, morning coffee does not correlate with coupon acceptance, instead coupons accepted at higher rate when urgency is not factor (74%)
# Direction does have a measurable impact on acceptance rate for coffee drinkers at 73% when venue is in the same direction
# Hotter temperatures also drive coupon usage at 71% - iced coffee and speciality drinks perhaps ?

Next Steps:

# Explore the interplay of multiple categorical variables - contingency tables - to see if there are deeper patterns that can be established in the data
# Explore prediction of coupon acceptance based on predictors.  Acceptance is binary and could be explored through logistic regression as one method 
