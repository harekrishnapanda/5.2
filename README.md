# 5.2

import scipy.stats as stats
Group1 = [51, 45, 33, 45, 67]
Group2 = [23, 43, 23, 43, 45]
Group3 = [56, 76, 74, 87, 56]
stats.f_oneway(Group1,Group2,Group3)
# CriticalF(2,12) = 3.89 (From the F table) (2 and 12 are degree of freedom of the numerator and denominator respectively)
# since F value is greater then F Critical value we can Reject the Null Hypothesis
