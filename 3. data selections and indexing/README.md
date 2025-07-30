### ✅ **Data Selection & Indexing in pandas: Full Coverage Plan**

### 🔹 A. **Basic Selection Techniques**

1. Selecting columns using `[]`
2. Selecting rows using `loc[]` and `iloc[]`
3. Slicing rows (`:`) and columns
4. Boolean indexing (with single and multiple conditions)
5. Selection with `.at[]` and `.iat[]` (fast accessors)

---

### 🔹 B. **Indexing & Reindexing**

6. `set_index()`, `reset_index()`
7. `reindex()` and `reindex_like()`
8. Changing index with `df.index = ...`
9. Hierarchical indexing (MultiIndex)

---

### 🔹 C. **Label-based Selection**

10. `df.loc[]` – Label-based row and column selection
11. `df.at[]` – Scalar label-based accessor (fastest for single values)

---

### 🔹 D. **Integer-based Selection**

12. `df.iloc[]` – Position-based row and column selection
13. `df.iat[]` – Scalar position-based accessor (fastest for single values)

---

### 🔹 E. **Boolean Indexing & Filtering**

14. Boolean masks with comparison operators
15. Filtering with `.isin()`, `.between()`, `.str.contains()` etc.
16. `.query()` method

---

### 🔹 F. **Selection with callable functions**

17. Passing a function to `df.loc[]`, `df.iloc[]`, etc.

---

### 🔹 G. **Advanced Indexing Concepts**

18. MultiIndex advanced selection using `xs()`, slicing, etc.
19. Indexing with `IndexSlice`
20. Partial string indexing on datetime index
21. Chained indexing vs. `.loc[]` (why to avoid chained indexing)
22. Index alignment behavior in selection

---

### 🔹 H. **Selection on Series**

23. Indexing and slicing on Series
24. Boolean masking on Series

---

### 🔹 I. **Best Practices**

25. When to use `.loc` vs `.iloc` vs `[]`
26. Performance tips and caveats
27. Avoiding SettingWithCopyWarning

<center><b>Thanks</b></center>
