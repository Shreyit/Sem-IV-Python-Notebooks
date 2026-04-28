# 🐍 Semester IV Python Notebooks

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-009933?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243)
![License](https://img.shields.io/badge/License-MIT-green)

Comprehensive Python learning journey covering fundamentals, control flow, numerical computing, and data science. **15 classes** with hands-on assignments and real-world datasets.

---

## 📋 Quick Overview

| Metric | Count |
|--------|-------|
| **Classes** | 15 (Feb 25 - Apr 26, 2026) |
| **Assignments** | 6 (Classes 3, 4, 5, 9, 10, 15) |
| **Datasets** | 11 files (CSV, XLSX, TXT, PKL, Parquet) |
| **Core Libraries** | NumPy, Pandas, Matplotlib/Seaborn, Requests |

---

## 📚 Curriculum Structure

### **Phase 1: Python Fundamentals** (Classes 2-5)
*Building core programming skills*

| Class | Date | Topics | Libraries | Assignment |
|-------|------|--------|-----------|-----------|
| **Class 2** | 25-01-26 | Python setup, variables, data types | - | - |
| **Class 3** | 01-02-26 | Lists, tuples, strings, indexing | `str` methods | ✅ Class 3 |
| **Class 4** | 07-02-26 | Dictionaries, sets, type operations | Built-ins | ✅ Class 4 |
| **Class 5** | 08-02-26 | Conditionals, control flow | `if/elif/else` | ✅ Class 5 |

**Key Concepts**: Data structures, string manipulation, basic logic

---

### **Phase 2: Control Flow & Iteration** (Classes 6-7)
*Mastering loops and efficient coding patterns*

| Class | Date | Topics | Key Skills |
|-------|------|--------|-----------|
| **Class 6** | 01-03-26 | Loops (for, while), iterations | Loop mechanics, nested loops |
| **Class 7** | 14-03-26 | List comprehensions, lambda functions | Functional programming, concise syntax |

**Key Concepts**: Loop optimization, functional approach to data manipulation

---

### **Phase 3: Numerical Computing** (Classes 8-10)
*Introduction to scientific Python*

| Class | Date | Topics | Libraries | Assignment |
|-------|------|--------|-----------|-----------|
| **Class 8** | 14-03-26 | NumPy arrays, creation, shape | `numpy` | - |
| **Class 9** | 23-03-26 | Array indexing, slicing, filtering | `np.where()`, boolean indexing | ✅ Class 9 |
| **Class 10** | 04-04-26 | Statistical operations, aggregations | `np.mean()`, `np.sort()`, descriptive stats | ✅ Class 10 |

**Key Concepts**: Vectorized operations, numerical arrays, filtering & statistics

---

### **Phase 4: Data Science Fundamentals** (Classes 11-12)
*From data ingestion to cleaning*

| Class | Date | Topics | Libraries | Focus |
|-------|------|--------|-----------|-------|
| **Class 11** | 05-04-26 | Pandas basics, DataFrames, file I/O | `pandas` | Data ingestion from CSV/Excel |
| **Class 12** | 18-04-26 | Data cleaning, handling missing values | `pandas` | Removing duplicates, type casting, null handling |

**Key Concepts**: DataFrame operations, data inspection, cleaning pipelines

---

### **Phase 5: Advanced Data Science & Visualization** (Classes 13-15)
*Building stronger EDA and pandas skills*

| Class | Date | Topics | Libraries | Focus |
|-------|------|--------|-----------|-------|
| **Class 13** | 19-04-26 | Data cleaning review, outlier detection, typos, duplicate handling | `pandas`, `numpy`, `seaborn` | Robust data quality checks |
| **Class 14** | 25-04-26 | Advanced filtering, string operations, sorting, groupby aggregation | `pandas` | Structured dataset exploration |
| **Class 15** | 26-04-26 | Data visualization, correlation analysis, concat, web scraping | `pandas`, `seaborn`, `requests`, `bs4` | EDA, data combination, and CSV/text integration |

**Key Concepts**: Visual analytics, groupby aggregation, concatenation, scraping supplemental data

---

## 📊 Datasets

Located in `/data/`:

| File | Format | Purpose | Used In |
|------|--------|---------|---------|
| **retail_2016_2017.csv** | CSV | Retail sales analysis | Classes 11-15 |
| **oil.csv** | CSV | Oil price/supply data | Class 12 |
| **Student Grades.xlsx** | Excel | Student performance data | Class 13 |
| **Run Times.xlsx** | Excel | Exercise performance data | Class 12 |
| **Groceries.xlsx** | Excel | Transaction data | Class 14 |
| **groceries_with_new_columns.pkl** | Pickle | Enriched grocery dataset | Classes 14-15 |
| **student_data.csv** | CSV | Student survey grades | Classes 14-15 |
| **happiness_survey_data.csv** | CSV | Global happiness scores | Classes 15, Assignment 15 |
| **happiness_data_*.txt** | TXT | Country happiness data slices | Class 15 |
| **final_student_dataset.parquet** | Parquet | Processed student data archive | Course reference |

Additional dataset formats support exercises in file I/O, concatenation, and text parsing.

---

## 📁 Directory Structure

```
Sem IV Python/
├── Class ipynb Notebook/        # Main course content
│   ├── class_02 to class_15     # 15 classroom sessions
│   └── Organized by date
├── Class Assignment/            # Assessments & exercises
│   ├── assignment_class_03-15   # Problem sets
│   └── Class_XX_Assignment.docx # Assignment details
├── data/                        # Datasets for practice
│   ├── *.csv, *.txt, *.xlsx, *.pkl, *.parquet
└── README.md                    # This file
```

---

## 🚀 Getting Started

### Environment Setup
```bash
# Option 1: Using Anaconda (Recommended)
# 1. Install Anaconda from https://www.anaconda.com
# 2. Launch Jupyter Notebook from Anaconda Navigator
# 3. Navigate to this repository folder

# Option 2: Using pip
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install jupyter pandas numpy
jupyter notebook
```

### View Notebooks
1. Open Jupyter Notebook
2. Navigate to the repository folder
3. Select a class notebook to explore

### Run Assignments
- Open corresponding assignment notebook
- Complete the exercises
- Run cells to validate your solutions

---

## 🎓 Learning Path

**Recommended Order:**
1. ✅ Start with **Phase 1** (Classes 2-5) - Foundation
2. ✅ Practice **Phase 2** (Classes 6-7) - Iteration & Efficiency
3. ✅ Learn **Phase 3** (Classes 8-10) - Numerical Computing
4. ✅ Master **Phase 4** (Classes 11-12) - Data Science
5. ✅ Explore **Phase 5** (Classes 13-15) - Advanced Data Science & Visualization

Each phase builds on previous concepts. Assignments reinforce learning.

---

## 📝 Key Topics Covered

### Data Types & Structures
- Lists, Tuples, Dictionaries, Sets
- String manipulation and methods
- Type casting and conversion

### Control Structures
- Conditional statements (if/elif/else)
- Loops (for, while)
- List comprehensions

### Numerical Computing
- NumPy arrays and vectorization
- Advanced indexing and slicing
- Statistical operations

### Data Science
- Pandas DataFrames and Series
- File I/O (CSV, Excel)
- Data cleaning and preprocessing
- Handling missing/duplicate values

---

## 💡 Tips

- **Run cells sequentially** - Variables defined earlier are needed
- **Modify code** - Try different parameters to understand behavior
- **Use assignments** - Apply learning through problem-solving
- **Refer to documentation** - Check pandas/numpy docs when needed

---

## 📖 Resources

- [Python Official Docs](https://docs.python.org/3/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Jupyter Notebook Guide](https://jupyter.org/)

---

## 👨‍💻 Author

**Shreyit** 
- GitHub: [@Shreyit](https://github.com/Shreyit)
