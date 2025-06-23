7-day, 4-hour-per-day roadmap to go from zero to confident in pandas—complete with daily goals, resources, and hands-on exercises using real-world datasets. At the end, I’ll point you toward the next logical libraries to learn.

---

## Day 1 – Fundamentals of pandas  
**Total time: 4 hrs**  
1. **Overview & Setup (30 min)**  
   - Quick tour of the pandas API and ecosystem.  
   - Install/upgrade: `pip install --upgrade pandas jupyterlab`.  
2. **Core Data Structures (1.5 hrs)**  
   - **Series**: creation, indexing, alignment.  
   - **DataFrame**: creation from dicts/arrays/CSV, `.head()/.info()/.describe()`.  
   - 👉 *Resource*: “10 Minutes to pandas” (pandas.pydata.org)  
3. **Indexing & Selection (1 hr)**  
   - Label vs. position: `.loc`, `.iloc`, boolean masks.  
   - Chaining vs. single-step selection.  
4. **Exercise (1 hr)**  
   - Dataset: Iris flower data (`sepal/petal` measurements).  
   - Tasks: load CSV, explore shape, select subsets (e.g., rows where petal_length > 1.5), compute basic stats.

---

## Day 2 – Data Cleaning & Preparation  
**Total time: 4 hrs**  
1. **Handling Missing Data (1 hr)**  
   - `.isna()`, `.dropna()`, `.fillna()`, interpolation.  
2. **Type Conversion & Parsing (30 min)**  
   - Converting dtypes, parsing dates with `pd.to_datetime`.  
3. **Renaming, Reordering & Duplicates (30 min)**  
   - `.rename()`, `.reindex()`, `.drop_duplicates()`.  
4. **String Methods & Categoricals (1 hr)**  
   - `.str` accessor for text columns, converting to `category`.  
5. **Exercise (1 hr)**  
   - Dataset: NYC 2019 bike-share (trip data with missing fields).  
   - Clean up missing start/end times, standardize column names, drop duplicates, convert user-type to categorical.

---

## Day 3 – Transformations & Aggregations  
**Total time: 4 hrs**  
1. **Arithmetic & Broadcasting (30 min)**  
   - Elementwise ops, alignment rules.  
2. **GroupBy Mechanics (1.5 hrs)**  
   - Split-apply-combine: `.groupby()` + `.agg()`, `.transform()`, filtering groups.  
3. **Merging, Joining & Concatenating (1 hr)**  
   - `.merge()` (inner/left/right), `.join()`, `pd.concat()`.  
4. **Exercise (1 hr)**  
   - Dataset: COVID-19 time series (cases by country).  
   - Compute weekly averages per country, join with population data, identify top five most-affected.

---

## Day 4 – Advanced Indexing & Time Series  
**Total time: 4 hrs**  
1. **MultiIndex (Hierarchical) (1 hr)**  
   - Creating, slicing, swapping levels.  
2. **Window & Rolling Operations (1 hr)**  
   - `.rolling()`, `.expanding()`, `.ewm()`.  
3. **Time Series Manipulations (1 hr)**  
   - Resampling (`.resample()`), shifting, time-zone handling.  
4. **Exercise (1 hr)**  
   - Dataset: S&P 500 historical prices.  
   - Compute 7-day moving average, compare monthly vs. daily returns.

---

## Day 5 – Visualization with pandas & Integration  
**Total time: 4 hrs**  
1. **Built-in Plotting (30 min)**  
   - `df.plot()` (line, bar, histogram, box).  
2. **Seaborn & matplotlib Basics (1 hr)**  
   - Wrapping pandas data in Seaborn (e.g., `sns.scatterplot(data=df, x=…, y=…)`).  
3. **Interactive Plots (plotly/pandas) (30 min)**  
   - `df.plot(kind='scatter', …, backend='plotly')`.  
4. **Dashboards Intro (1 hr)**  
   - Using Streamlit: quick “Hello, pandas!” app that reads CSV and shows charts.  
5. **Exercise (1 hr)**  
   - Dataset: Global happiness index.  
   - Visualize relationships (GDP vs. happiness), create an interactive dashboard in Streamlit.

---

## Day 6 – End-to-End Mini Project  
**Total time: 4 hrs**  
Pick a dataset from Kaggle (e.g., Titanic, Housing Prices, or World Bank indicators).  
1. **Project Setup (30 min)**  
   - Define questions you want to answer.  
2. **Data Ingestion & Cleaning (1 hr)**  
   - Apply all cleaning techniques learned.  
3. **Exploration & Analysis (1 hr)**  
   - Use grouping, aggregations, visualizations to uncover insights.  
4. **Reporting (1.5 hrs)**  
   - Prepare a Jupyter notebook with narrative, charts, and key findings.  
   - Optionally convert to a shareable HTML/PDF.

---

## Day 7 – Next Steps & Broader Ecosystem  
**Total time: 4 hrs**  
1. **Quick Stats Refresher (1 hr)**  
   - Mean, median, variance, correlation—how pandas computes them.  
   - Resource: Khan Academy “Descriptive Statistics” primers.  
2. **NumPy & SciPy (1 hr)**  
   - Arrays vs. Series, vectorized ops, linear algebra basics.  
3. **scikit-learn Introduction (1 hr)**  
   - Loading data from pandas into `sklearn`, train/test split, a simple regression.  
4. **SQL & NoSQL Data Sources (30 min)**  
   - Reading from databases: `pd.read_sql()`.  
5. **Dashboarding & Deployment (30 min)**  
   - Next: Plotly Dash, Power BI, or advanced Streamlit features.

---

### Key Resources & Datasets  
- **Documentation & Tutorials**  
  - Pandas official “User Guide” and “Cookbook”.  
  - Kaggle Learn “pandas” micro-course.  
  - YouTube channels: Corey Schafer, Data School.  
- **Real-World Data Sources**  
  - [Kaggle Datasets](https://kaggle.com/datasets) (Titanic, NYC Taxi, COVID-19).  
  - [UCI Machine Learning Repository](https://archive.ics.uci.edu).  
  - [data.gov](https://data.gov) for government open data.

---

#### Tips for Success  
- **Hands-on repetition**: After each lesson, try variations on the exercises.  
- **Version control**: Keep your notebooks in Git with clear commits.  
- **Community**: Join forums like Stack Overflow, r/learnpython, or the pandas GitHub discussions.  
