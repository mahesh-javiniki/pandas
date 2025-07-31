### ✅ **What is Data Cleaning in pandas?**

Data cleaning involves **identifying and correcting errors or inconsistencies** in the data to make it reliable and suitable for analysis or modeling. In pandas, this involves handling:

* Missing values
* Duplicates
* Invalid formats
* Inconsistent data types
* Outliers
* Wrong or noisy values
* Irregular string formats

---

### 📘 **Master List of Data Cleaning Techniques in pandas**

Here is a categorized list of **all major techniques and methods** involved in data cleaning using pandas:

---

#### **1. Handling Missing Data**

* `isnull()`, `notnull()`
* `dropna()`
* `fillna()`
* `interpolate()`
* `ffill()` / `bfill()`
* `replace(np.nan, value)`
* Missing value indicator columns

---

#### **2. Handling Duplicates**

* `duplicated()`
* `drop_duplicates()`

---

#### **3. Handling Incorrect Data Types**

* `astype()`
* `to_numeric()`
* `to_datetime()`
* `infer_objects()`

---

#### **4. Handling Invalid / Out-of-Range Values**

* Logical filtering and replacement
* `clip()`
* `apply()` with custom validation
* Regex validations

---

#### **5. String Cleaning & Normalization**

* `str.strip()`, `str.lower()`, `str.upper()`
* `str.replace()`, `str.extract()`, `str.contains()`
* Remove unwanted characters using regex
* Split & join operations: `str.split()`, `str.cat()`

---

#### **6. Dealing with Outliers**

* Z-score or IQR methods
* Using `quantile()` to cap or remove
* Visualization with boxplots, histograms

---

#### **7. Renaming & Replacing Labels**

* `rename()`
* `replace()`
* `map()` for categorical values
* `rename_axis()`

---

#### **8. Index Cleaning**

* Resetting indexes: `reset_index()`
* Setting proper indexes: `set_index()`
* Removing unnamed index columns

---

#### **9. Type Conversions & Consistency Checks**

* Object to category
* Enforcing consistent types across columns

---

#### **10. Encoding Categorical Variables (optional for modeling prep)**

* `get_dummies()`
* `LabelEncoder` or `map()` for simple labels

---

#### **11. Fixing Structural Errors**

* Correcting column names
* Fixing mixed data in single columns
* Unpivoting or pivoting (reshaping): `melt()`, `pivot()`, `stack()`, `unstack()`

---

#### **12. Removing or Treating Noise**

* Spelling correction using `fuzzywuzzy` or `difflib`
* Frequency filtering of rare categories

---

We **cannot explain all of them in detail in a single response**, so here’s a suggestion:

<center><b>Thanks</b></center>