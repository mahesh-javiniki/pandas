## ✅ **9. Data Visualization (with Pandas)**

We’ll focus **only on pandas' built-in plotting capabilities**, using its `.plot()` API which is built on top of **Matplotlib** — but we’ll **not cover advanced customization**, since that belongs in libraries like **Seaborn** and **Matplotlib**, which you’ll tackle later.

---

## ✅ **Topics to Cover Under 9. Data Visualization (with Pandas)**

Here’s a structured and complete list of methods and techniques you should learn in this section:

### 1. **Basics of `.plot()` Method**

* What is `df.plot()` and its underlying engine
* When to use `.plot()` in exploratory data analysis (EDA)
* Basic syntax and structure

### 2. **Line Plot**

* Default behavior of `.plot()`
* Line plots for single and multiple columns
* Plotting datetime index
* Use case: Trend over time

### 3. **Bar Plot**

* `kind='bar'` and `kind='barh'`
* Grouped and stacked bar plots
* Plotting categorical variables

### 4. **Histogram**

* `.hist()` vs `.plot(kind='hist')`
* Customizing number of bins
* Use case: Distribution of values

### 5. **Box Plot (Box-and-Whisker)**

* `kind='box'`
* Comparing distributions across categories
* Identifying outliers and spread

### 6. **Area Plot**

* `kind='area'`
* Stacked vs unstacked
* Use case: Cumulative trends

### 7. **Pie Chart**

* `kind='pie'` (works only on Series)
* Use case: Share or percentage visualizations

### 8. **Scatter Plot**

* `kind='scatter'`
* Requires `x` and `y` arguments
* Use case: Bivariate analysis

### 9. **Density Plot / KDE Plot**

* `kind='kde'` or `kind='density'`
* Use case: Smooth distribution curves

### 10. **Subplots & Layouts**

* `subplots=True`
* Plotting multiple charts together

### 11. **Customization Options (Basic)**

* Title, labels, grid, color, figsize
* Legend, marker, alpha, linestyle
* Saving plots with `plt.savefig()` (light touch)

---

## ✅ What We Will NOT Cover in This Section

To avoid overlapping with your future learning:

* ❌ Custom plotting with **Matplotlib** or **Seaborn**
* ❌ Plot aesthetics, themes, and styles from Seaborn
* ❌ Plot interactivity (Plotly, Altair)
* ❌ Dashboards or UI visualizations
* ❌ Advanced statistical plotting (violin plots, pair plots, regression plots)

---

## 🧭 Plan of Action

We’ll cover each of these **one by one**:

1. Explain what it does and when to use
2. Provide syntax and core parameters
3. Show different techniques (with variations)
4. Understanding each technique with examples (with data)
5. Include common pitfalls
6. Provide real-world examples and use cases

<center><b>Thanks</b></center>