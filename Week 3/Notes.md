### Week 3

* Probability

* All outcomes: Probability space

* Probability Model

* Alpha (α) is also known as the significance level.

* P-value is a calculated value and an output you get as part of conducting your hypothesis test.

**Math behind Normality**

$f(x,\mu, \sigma)=\frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-\mu)^2}{2\sigma^2}}$

```
import numpy as np
import matplotlib.pyplot as plt
from scipy.stats import norm

x_axis = np.arange(-1, 1, 0.1)

plt.plot(x_axis, norm.pdf(x_axis, 0.1))
plt.show()
```

---

* T-distribution: T-test

```
import scipy.stats

scipy.stats.ttest_ind(df[df["column1"]=="female"]["eval"],
df[df["column1"]=="male"]["eval"])
```

---

**Standardization** - z-scores

$z=\frac{x-\mu}{\sigma}$

```
import scipy.stats

prob0 = scipy.stats.norm.cdf((4.5-mean)/stddev)
```
