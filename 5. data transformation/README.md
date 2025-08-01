## 🔧 5. Data Transformation

1. **Applying functions**

   * `df.apply(function, axis=…)`
   * `Series.map()`
   * `df.applymap()`

2. **Lambda functions**

   * Inline transformations: `df['col'].apply(lambda x: …)`

3. **Discretization & binning**

   * `pd.cut()`, `pd.qcut()`
   * Creating custom bins/labels for numeric data

4. **Sorting**

   * `.sort_values(by=…, ascending=…)`
   * `.sort_index()`

5. **Combining columns / splitting strings**

   * Concatenating (`+`, `str.cat()`)
   * Splitting (`str.split()`, `expand=True`)
   * Extracting with regex: `str.extract()`

6. **Value transformations**

   * `.replace()`
   * `.astype()` for type casting
   * `.round()`, `.abs()`, etc.

7. **Handling duplicates or unique transformations**

   * Marking duplicates: `.duplicated()`
   * Dropping duplicates: `.drop_duplicates()`

8. **Conditional transformations / new columns**

   * `np.where()`
   * `.loc[condition, 'col'] = new_val`

9. **Pivot/melt for long/wide formats**

   * `pd.melt()`, `df.pivot()`, `df.pivot_table()` *(these edge into section 6 but often used in transformation)*

10. **Reshaping/transposing**

    * `.T` (matrix transpose)
    * `.stack()`, `.unstack()` for hierarchical indexing

11. **Window functions (basic)**

    * Rolling transforms: `.rolling(window).mean()/sum()/apply()`

---

## 🗓️ Iterative Learning Plan

We'll tackle one method at a time, covering:

1. **What** it does and **when** to use it
2. **Syntax** and **core parameters**
3. Different **methods and techniques**
4. **Common pitfalls** and best practices
5. **Examples** on real/pseudo data
6. **Real world use cases**

<center><b>Thanks</b></center>