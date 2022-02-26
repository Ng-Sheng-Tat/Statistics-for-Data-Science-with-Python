### Week 4

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-24-02-image.png)

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-24-50-image.png)

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-26-10-image.png)

---

**Levene's Test**

* is an inferential statistic to assess the equality of variance

```
scipy.stats.levene(df[df['gender']=='female']['eval'], df[df['gender']=='male']['eval'], center='mean')
```

```
scipy.stats.levene(df[df['gender']=='female']['eval'], df[df['gender']=='male']['eval'], equal_var=True)
```

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-30-31-image.png)

---

**Anova**: one-way analysis of variance is used to compare means of more than two groups using the F distribution

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-32-17-image.png)

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-32-33-image.png)

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-32-47-image.png)

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-32-59-image.png)

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-33-44-image.png)

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-34-04-image.png)

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-34-31-image.png)

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-21-34-51-image.png)
