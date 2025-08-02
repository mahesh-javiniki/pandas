## ✅ **8. Working with Date and Time in pandas**

### 📦 A. DateTime Conversion and Parsing

* `pd.to_datetime()` — Convert strings or objects to datetime
* Parsing formats manually with `format=`
* Handling errors (`errors=‘coerce’`)

---

### 🔍 B. Exploring and Accessing DateTime Components

* `.dt` accessor

  * `.dt.year`, `.dt.month`, `.dt.day`
  * `.dt.hour`, `.dt.minute`, `.dt.second`
  * `.dt.weekday`, `.dt.day_name()`, `.dt.month_name()`
* `.date`, `.time` for extracting pure date/time

---

### 🗃️ C. Filtering and Indexing by Dates

* Boolean filtering using date ranges
* Filtering between dates using:

  * Masks (e.g., `df[(df['date'] >= ...) & (df['date'] <= ...)]`)
  * `pd.date_range()` and comparisons
* Date slicing if `DatetimeIndex` is set

---

### 🧱 D. Date Ranges and Frequency Generation

* `pd.date_range()` – generating ranges with frequency (`freq=`)
* `pd.timedelta_range()`, `pd.period_range()`
* Useful frequencies:

  * `'D'`, `'H'`, `'M'`, `'Y'`, `'W'`, `'Q'`, `'B'` (business days)

---

### 🧮 E. Time Deltas and Date Arithmetic

* `pd.Timedelta()` for differences
* Subtracting dates and computing time differences
* Adding or subtracting days, hours, etc.
* `dt.days`, `dt.total_seconds()`

---

### ⏱️ F. Resampling and Frequency Conversion

* `.resample()` – upsampling/downsampling time series

  * Aggregations: `.sum()`, `.mean()`, etc.
* Difference between `.resample()` vs `.groupby()`
* Custom resampling frequencies

  * E.g., `'M'`, `'Q'`, `'W-MON'`, `'H'`, `'15T'`

---

### 🔄 G. Rolling, Expanding, and Shifting Windows

* `.rolling(window=).mean()` – moving average
* `.expanding()` – cumulative stats
* `.shift()` – lead/lag operations
* Use cases in trends, anomaly detection

---

### 🧭 H. Setting and Using DatetimeIndex

* Converting a column to index: `df.set_index('date')`
* `pd.DatetimeIndex()`, `df.index.freq`
* Benefits of DatetimeIndex in slicing & resampling

---

### 🧰 I. Handling Time Zones

* Localizing naive datetimes: `.dt.tz_localize()`
* Converting time zones: `.dt.tz_convert()`
* Common pitfalls when working with time zones

---

### 🧪 J. Real-Time Use Cases & Applications

* Time series data cleaning
* Stock price analysis
* IoT sensor data
* Web/app activity logs

---

## 🗓️ Iterative Learning Plan

1. **What** it does and **when** to use it
2. **Syntax** and **core parameters**
3. Different **methods and techniques**
4. **Examples** on real/pseudo data
5. **Common pitfalls** and best practices
6. **Real world use cases**

<center><b>Thanks</b></center>