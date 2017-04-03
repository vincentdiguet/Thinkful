

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

pop1 = np.random.binomial(10, 0.3, 10000)
pop2 = np.random.binomial(10,0.5, 10000) 

sample1 = np.random.choice(pop1, 100, replace=True)
sample2 = np.random.choice(pop2, 100, replace=True)

plt.hist(sample1, alpha=0.5, label='sample 1') 
plt.hist(sample2, alpha=0.5, label='sample 2') 
plt.legend(loc='upper right') 
plt.show()

print(sample1.mean())
print(sample2.mean())
print(sample1.std())
print(sample2.std())

sample3 = np.random.choice(pop1, 200, replace=True)
sample4 = np.random.choice(pop2, 200, replace=True)

plt.hist(sample3, alpha=0.5, label='sample 1') 
plt.hist(sample4, alpha=0.5, label='sample 2') 
plt.legend(loc='upper right') 
plt.show()

print(sample3.mean())
print(sample4.mean())
print(sample3.std())
print(sample4.std())


sample5 = np.random.choice(pop1, 20, replace=True)
sample6 = np.random.choice(pop2, 20, replace=True)

plt.hist(sample5, alpha=0.5, label='sample 1') 
plt.hist(sample6, alpha=0.5, label='sample 2') 
plt.legend(loc='upper right') 
plt.show()

print(sample5.mean())
print(sample6.mean())
print(sample5.std())
print(sample6.std())

```


![png](output_0_0.png)


    2.07
    5.09
    1.37298943914
    1.6498181718



![png](output_0_2.png)


    2.015
    4.915
    1.250909669
    1.47233657837



![png](output_0_4.png)


    2.2
    5.55
    1.46969384567
    1.11691539518



```python

```
