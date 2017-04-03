

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

#Generate a random variable
normalvar = np.random.normal(0,1, 100)
poisonvar = np.random.poisson(1, 100)
bernoullivar=np.random.binomial(1, .5, 100)
gammavar = np.random.gamma(5,1, 100)
exponentialvar=np.random.exponential(1,100)
logisticvar=np.random.logistic(1,1,100)

#Graph the variable using a histogram
#Plot a histogram.
plt.hist(normalvar)


# Add a vertical line at the mean.
plt.axvline(normalvar.mean(), color='b', linestyle='solid', linewidth=1)
# Add a vertical line at one standard deviation above the mean.
plt.axvline(normalvar.mean() + normalvar.std(), color='b', linestyle='dashed', linewidth=2)
# Add a vertical line at one standard deviation below the mean.
plt.axvline(normalvar.mean()-normalvar.std(), color='b', linestyle='dashed', linewidth=2) 
plt.show()

plt.hist(poisonvar)

# Add a vertical line at the mean.
plt.axvline(poisonvar.mean(), color='b', linestyle='solid', linewidth=1)
# Add a vertical line at one standard deviation above the mean.
plt.axvline(poisonvar.mean() + poisonvar.std(), color='b', linestyle='dashed', linewidth=2)
# Add a vertical line at one standard deviation below the mean.
plt.axvline(poisonvar.mean()-poisonvar.std(), color='b', linestyle='dashed', linewidth=2)
plt.show()


plt.hist(bernoullivar)
# Add a vertical line at the mean.
plt.axvline(bernoullivar.mean(), color='b', linestyle='solid', linewidth=1)
# Add a vertical line at one standard deviation above the mean.
plt.axvline(bernoullivar.mean() + bernoullivar.std(), color='b', linestyle='dashed', linewidth=2)
# Add a vertical line at one standard deviation below the mean.
plt.axvline(bernoullivar.mean()-bernoullivar.std(), color='b', linestyle='dashed', linewidth=2)

plt.show()

plt.hist(gammavar)

# Add a vertical line at the mean.
plt.axvline(gammavar.mean(), color='b', linestyle='solid', linewidth=1)
# Add a vertical line at one standard deviation above the mean.
plt.axvline(gammavar.mean() + gammavar.std(), color='b', linestyle='dashed', linewidth=2)
# Add a vertical line at one standard deviation below the mean.
plt.axvline(gammavar.mean()-gammavar.std(), color='b', linestyle='dashed', linewidth=2)

plt.show()

plt.hist(exponentialvar)

# Add a vertical line at the mean.
plt.axvline(exponentialvar.mean(), color='b', linestyle='solid', linewidth=1)
# Add a vertical line at one standard deviation above the mean.
plt.axvline(exponentialvar.mean() + exponentialvar.std(), color='b', linestyle='dashed', linewidth=2)
# Add a vertical line at one standard deviation below the mean.
plt.axvline(exponentialvar.mean()-exponentialvar.std(), color='b', linestyle='dashed', linewidth=2)

plt.show()

plt.hist(logisticvar)

# Add a vertical line at the mean.
plt.axvline(logisticvar.mean(), color='b', linestyle='solid', linewidth=1)
# Add a vertical line at one standard deviation above the mean.
plt.axvline(logisticvar.mean() + logisticvar.std(), color='b', linestyle='dashed', linewidth=2)
# Add a vertical line at one standard deviation below the mean.
plt.axvline(logisticvar.mean()-logisticvar.std(), color='b', linestyle='dashed', linewidth=2)
plt.show()



#Std does not make sense for Binomial

```


![png](output_0_0.png)



![png](output_0_1.png)



![png](output_0_2.png)



![png](output_0_3.png)



![png](output_0_4.png)



![png](output_0_5.png)



```python

```
