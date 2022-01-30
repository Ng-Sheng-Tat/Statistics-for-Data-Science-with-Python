### Week 2

- types of data determines your type of chart that you used

- visualization using seaborn and matplotlib libraries in python

``df = df.drop_duplicates(subset=['prof'])``

``ax = sns.countplot(x="gender", data=ratings_df, hue='tenure')``

``ax.set_title("My Title")``

``as.sns.catplot(x='gender', data=, kind='count', hue='tenure', row='division')``

```
g = sns.FacetGrid(ratings_df,row="tenure", hue="gender")
g = (g.map(plt.scatter, "age", "eval").add_legend())
```

``ax = sns.boxplot(x="gender", y="age", data="rating_df, hue=gender")``

![](C:\Users\user\AppData\Roaming\marktext\images\2022-01-30-18-49-10-image.png)




































































































