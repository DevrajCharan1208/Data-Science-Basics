# 🐼 Pandas Learning Path

> 6-notebook series on data manipulation and analysis using **real-world data** — the Stack Overflow Developer Survey 2024.

---

## 📜 Notebook Breakdown

| # | Notebook | Key Concepts |
|---|---|---|
| 1 | `Pandas_1_basics` | Series, DataFrames, `read_csv()`, `.head()`, `.info()`, `.describe()` |
| 2 | `Pandas_2_dictionary` | Creating DataFrames from dicts, column operations, `value_counts()` |
| 3 | `Pandas_3_indexing_and_operations` | `.loc[]`, `.iloc[]`, conditional selection, arithmetic ops |
| 4 | `Pandas_4_filtering` | Boolean filters, `isin()`, `str` accessor, multiple conditions |
| 5 | `Pandas_5_modifying_data` | Updating values, `apply()`, `map()`, type casting, `replace()` |
| 6 | `Pandas_6_add_remove_rows_columns` | `concat()`, `append()`, `drop()`, `insert()`, axis operations |

---

## 📦 Dataset

**Stack Overflow Developer Survey 2024** (`data_2024/`)
- `survey_results_public.csv` — Full survey responses
- `survey_results_schema.csv` — Column descriptions

Used as the primary dataset throughout the notebooks for realistic, messy, real-world data experience.

---

## 💡 Key Takeaways

- **DataFrames** are the core structure — understand rows (axis=0) and columns (axis=1)
- **Boolean indexing** is far more powerful than loops for filtering
- **`apply()` + `map()`** enable vectorized custom transformations
- Real data is messy — `NaN` handling and type conversion are essential skills

---

## 🚀 How to Run

```bash
pip install pandas jupyter
jupyter notebook
```

Open any notebook and run cells top-to-bottom. Make sure the `data_2024/` folder is in the same directory.
