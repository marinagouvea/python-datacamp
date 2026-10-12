# Matplotlib
## WHAT is matplotlib?

It is a Python library used to create visualizations, such as charts and graphs. It helps us explore data and communicate results visually.

Code Example:

```python
import matplotlib.pyplot as plt

year = [1950, 1970, 1990, 2010]
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
year = [1950, 1970, 1990, 2010]
pop = [2.519, 3.692, 5.263, 6.972]
plt.scatter(year, pop)
plt.show()
```

## Exercises
**Line Chart (1)**

With Matplotlib, you can create various types of charts in Python. The most basic chart is the line chart. Here is a general example.

```python
import matplotlib.pyplot as plt
plt.plot(x, y)
plt.show ()
```

In the video, you’ve already seen how much the world’s population has grown in recent years. Will it continue to grow? The World Bank has estimates of the world’s population between the years 1950 and 2100. The years are loaded into your workspace as a list called `year`, and the corresponding populations as a list called `pop`. 

**Instructions**

- Use `print()` to print the last item in the `year` and `pop` lists and see what the estimated population is for the year 2100. Use two `print()` functions.
- Before you begin, you must import `matplotlib.pyplot` as `plt`. `pyplot` is a subpackage of `matplotlib`, which is why there’s a period.
- Use `plt.plot()` to create a line graph. `year` should be plotted on the horizontal axis, and `pop` on the vertical axis. Don’t forget to end with the `plt.show()` function to actually display the graph.

**Print the last item from year and pop**
```python
print(year[-1])
print(pop[-1])
```
**Import matplotlib.pyplot as plt**
```python
import matplotlib.pyplot as plt
```
**Make a line plot: year on the x-axis, pop on the y-axis**
```python
plt.plot(year, pop)
```

**Display the plot with plt.show()**
```python
plt.show()
```

**Line Chart (2)**

Now that you’ve created your first line chart, let’s start working with the data that Professor Hans Rosling used to create his beautiful bubble chart. The data was collected in 2007. There are two lists available to you:

life_exp, which contains the life expectancy for each country; and
gdp_cap, which contains the GDP per capita (i.e., per person) for each country expressed in U.S. dollars.
GDP stands for Gross Domestic Product. Basically, it represents the size of a country’s economy. When you divide this value by the population, you get GDP per capita.

matplotlib.pyplot has already been imported as plt, so you can get started right away.

**Instructions** 
- Print the last item in the `gdp_cap` list and the `life_exp` list; these are data points about Zimbabwe.
- Create a line graph with `gdp_cap` on the x-axis and `life_exp` on the y-axis. Does it make sense to plot this data on a line graph?
- Don't forget to end with the `plt.show()` command to actually display the graph.

**Print the last item of gdp_cap and life_exp**
```python
print(gdp_cap[-1])
print(life_exp[-1])
```
**Make a line plot, gdp_cap on the x-axis, life_exp on the y-axis**
```python
plt.plot(gdp_cap, life_exp)
```
**Display the plot**
```python
plt.show()
```

```
