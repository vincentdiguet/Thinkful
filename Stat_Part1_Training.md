

```python
# Calculate mode, medium, average, Standard deviation, std error, variance

import pandas as pd
import numpy as np

# Vanilla Python, using the built-in statistics module.
import statistics

# Make a blank data frame.
df = pd.DataFrame()

# Populate it with data.
df['age'] = [14,12,11,10,8,6,8]


# Mean
mean = np.mean(df['age'])
#Mode
mode = statistics.mode(df['age'])
#Median
median = np.median(df['age'])
#Variance
variance=np.var(df['age'])
#standard deviation
stan_dev=np.std(df['age'], ddof=1)
#standard error         
ste=np.std(df['age'] ,ddof=1) / np.sqrt(len(df['age']))

print(mean)
print(mode)
print(median)
print(variance)
print(stan_dev)
print(ste)

#I woudl select Average and Standard deviaton

```

    9.85714285714
    8
    10.0
    6.40816326531
    2.73426232761
    1.03345401972



```python
# Clauclate mode, medium, average, Standard deviation, std error, variance

import pandas as pd
import numpy as np

# Vanilla Python, using the built-in statistics module.
import statistics

# Make a blank data frame.
df = pd.DataFrame()

# Populate it with data.
df['age'] = [14,12,11,10,8,7,8]


# Mean
mean = np.mean(df['age'])
#Mode
mode = statistics.mode(df['age'])
#Median
median = np.median(df['age'])
#Variance
variance=np.var(df['age'])
#standard deviation
stan_dev=np.std(df['age'], ddof=1)
#standard error         
ste=np.std(df['age'] ,ddof=1) / np.sqrt(len(df['age']))

print(mean)
print(mode)
print(median)
print(variance)
print(stan_dev)
print(ste)

# I would choose mean because of ...

```

    10.0
    8
    10.0
    5.42857142857
    2.51661147842
    0.951189731211



```python
# Calculate mode, medium, average, Standard deviation, std error, variance

import pandas as pd
import numpy as np

# Vanilla Python, using the built-in statistics module.
import statistics

# Make a blank data frame.
df = pd.DataFrame()

# Populate it with data.
df['age'] = [14,12,11,10,8,7,1]


# Mean
mean = np.mean(df['age'])
#Mode
#mode = statistics.mode(df['age'])
#Median
median = np.median(df['age'])
#Variance
variance=np.var(df['age'])
#standard deviation
stan_dev=np.std(df['age'], ddof=1)
#standard error         
ste=np.std(df['age'] ,ddof=1) / np.sqrt(len(df['age']))

print(mean)
#print(mode)
print(median)
print(variance)
print(stan_dev)
print(ste)

# Let's go for the median

# TV Guide 20% fans Entertainment Weekly 23%

```

    9.0
    10.0
    15.4285714286
    4.24264068712
    1.60356745147



```python
#Prob exercise

1) 50% * 50% * 50% *50%
2) 24/45
3) 10%*0.005%
4 ) People clicking on the link are more likely to be engaged already
overestimation

```


```python

```
