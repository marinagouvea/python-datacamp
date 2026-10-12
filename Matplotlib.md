# Matplotlib
## WHAT is matplotlib?

It is a Python library used to create visualizations, such as charts and graphs. It helps us explore data and communicate results visually.

Code Example:

```python
import matplotlib.pyplot as plt

year = [1950, 1970 1990, 2010]
pop = [2.519, 3.692, 5.263, 6.972]
plt.plot(year, pop)
plt.show()
```

## WHAT is scatter()?

The scatter() function in Matplotlib creates a scatter plot to show the relationship between two numerical variables. Each point represents a pair of values.

**Syntax**

plt.scatter(x, y)

x: values for the horizontal axis.

y: values for the vertical axis.

Code Example:
```python
year = [1950, 1970 1990, 2010]
pop = [2.519, 3.692, 5.263, 6.972]
plt.scatter(year, pop)
plt.show()
```
