## 🔍 Comprehensive List of Methods & Techniques to Cover under **Input/Output Operations**

### 🔹 1. **CSV Files**

* `pd.read_csv(filepath_or_buffer, **kwargs)`
* `df.to_csv(path_or_buf, **kwargs)`

### 🔹 2. **Excel Files**

* `pd.read_excel(io, sheet_name=0, **kwargs)`
* `df.to_excel(excel_writer, **kwargs)`

### 🔹 3. **JSON Files**

* `pd.read_json(path_or_buf, **kwargs)`
* `df.to_json(path_or_buf, **kwargs)`

### 🔹 4. **SQL Databases**

* `pd.read_sql(query, con)`
* `df.to_sql(name, con, if_exists='replace')`

> Note: We'll use `sqlite3` or mock databases for real-world examples.

### 🔹 5. **Clipboard**

* `pd.read_clipboard()`
* `df.to_clipboard()`

### 🔹 6. **HTML Tables**

* `pd.read_html(io)`
* (No direct `.to_html_table()` method, but `df.to_html()` is used)

### 🔹 7. **Pickle Files**

* `pd.read_pickle(path)`
* `df.to_pickle(path)`

---


We’ll go step-by-step like this:

1. **What** it does and **when** to use it
2. **Syntax** and key parameters
3. **Examples** of reading/writing
4. **Common pitfalls**
5. **Real-world usage**

<center><b>Thanks</b></center>