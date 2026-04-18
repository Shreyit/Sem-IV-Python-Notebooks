# Python Course Curriculum Summary - Semester IV

## Overview
This Python course spans 12 weeks with 5 homework assignments, covering fundamentals through data manipulation and analysis. The course progresses from basic data types to advanced NumPy and Pandas operations.

---

## CLASS-BY-CLASS BREAKDOWN

### **CLASS 02** (25-01-2026)
**Topic:** Built-in Functions & Modules Introduction
- **Main Concepts:**
  - Built-in functions and their documentation (`dir()`, `help()`)
  - Mathematical functions (`pow()`)
  - Module imports and usage
  
- **Key Libraries/Functions:**
  - `math` module: `factorial()`, `pow()`
  - `random` module: `randint()`
  - `numpy` module: `np.random.randint()`
  
- **Datasets:** None

---

### **CLASS 03** (01-02-2026)
**Topic:** Data Types - Numbers & Strings
- **Main Concepts:**
  - Number types (int, float, complex)
  - Immutability of numbers
  - Arithmetic operators (+, -, *, /, //, %, **)
  - String immutability and operations
  - String indexing and slicing
  - String methods: upper(), lower(), title(), find(), replace(), split(), strip()
  - List basics and indexing
  
- **Key Libraries/Functions:**
  - `math` module: `sqrt()`, `factorial()`, `ceil()`, `floor()`
  - `random` module: `randint()`, `random()`
  - String methods: `len()`, `upper()`, `lower()`, `title()`, `find()`, `replace()`, `split()`, `strip()`
  
- **Datasets:** None

---

### **CLASS 04** (07-02-2026)
**Topic:** Data Structures - Lists & Dictionaries
- **Main Concepts:**
  - List operations: mutable data structure using []
  - List methods: `append()`, `insert()`, `remove()`, `pop()`, `extend()`
  - Dictionary structure: key-value pairs using {}
  - Dictionary operations and methods: `keys()`, `values()`, `items()`, `get()`, `update()`
  - Dictionary use cases: APIs, databases
  
- **Key Libraries/Functions:**
  - List methods: `.append()`, `.insert()`, `.remove()`, `.pop()`, `.extend()`
  - Dictionary methods: `.keys()`, `.values()`, `.items()`, `.get()`, `.update()`
  
- **Datasets:** None

---

### **CLASS 05** (08-02-2026)
**Topic:** Data Structures - Sets, Tuples & Booleans
- **Main Concepts:**
  - Sets: unique elements, immutable elements, mutable collection
  - Set operations: intersection (&), union (|), difference (-)
  - Tuple: immutable, ordered collection
  - Mutable vs Immutable data types
  - Boolean: TRUE/FALSE for decision making
  - Set use cases: unique datasets, data cleaning
  
- **Key Libraries/Functions:**
  - Set operations: `&` (intersection), `|` (union), `-` (difference)
  - Set methods: `.add()`, `.remove()`
  - Tuple indexing and slicing
  
- **Datasets:** None

---

### **CLASS 06** (01-03-2026)
**Topic:** Control Flow - While Loops & For Loops
- **Main Concepts:**
  - While loops with conditions
  - If-else statements
  - For loops with `range()`
  - Nested loops
  - Loop control: `continue` statement
  - Compound conditional statements
  - Real-world example: Electricity bill calculation
  
- **Key Libraries/Functions:**
  - `range()`: generates sequence of numbers
  - Loop control keywords: `if`, `elif`, `else`, `continue`, `for`, `while`
  
- **Datasets:** None

---

### **CLASS 07** (14-03-2026)
**Topic:** List Comprehension
- **Main Concepts:**
  - List comprehension syntax: [expression for item in iterable if condition]
  - Creating lists efficiently
  
- **Key Libraries/Functions:**
  - List comprehension syntax
  
- **Datasets:** None

---

### **CLASS 08** (14-03-2026)
**Topic:** NumPy Introduction
- **Main Concepts:**
  - NumPy arrays vs Python lists
  - 1D and 2D arrays
  - Array creation: `np.ones()`, `np.zeros()`, `np.random()`
  - Seeding random numbers for reproducibility
  - Array properties: `ndim`, `shape`, `itemsize`, `size`
  - Data types: int8, int32, int64, etc.
  - Function writing with parameters
  
- **Key Libraries/Functions:**
  - `np.array()`: create arrays
  - `np.ones()`: create array of ones
  - `np.zeros()`: create array of zeros
  - `np.arange()`: create range array
  - `np.linspace()`: create evenly spaced numbers
  - `np.random.default_rng()`: random number generator with seed
  - `.rng.random()`: generate random decimals
  - `.rng.integers()`: generate random integers
  - Array properties: `.ndim`, `.shape`, `.itemsize`, `.size`
  
- **Datasets:** None
- **Practice Questions Included:** Discount calculation, finding minimum, vowel counting, divisors, tax calculation

---

### **CLASS 09** (23-03-2026)
**Topic:** NumPy - Indexing & Slicing Arrays
- **Main Concepts:**
  - 1D array indexing and slicing
  - 2D array indexing and slicing
  - Array reshaping
  - Advanced slicing techniques
  - Creating various array types
  
- **Key Libraries/Functions:**
  - Array slicing: `array[start:end:step]`
  - Array indexing: `array[row, col]`
  - `.reshape()`: change array dimensions
  - `np.arange()`: with reshape
  - Random number generation with various distributions:
    - `.random()`: uniform distribution 0-1
    - `.integers()`: random integers in range
    - `np.random.normal()`: normal distribution (mean, std, size)
  
- **Datasets:** None
- **Practice Questions:** Various array operations including random number generation with specific distributions

---

### **CLASS 10** (04-04-2026)
**Topic:** NumPy - Array Operations & Filtering
- **Main Concepts:**
  - Arithmetic operations on arrays
  - Array filtering with boolean masks
  - Unique values: `np.unique()`
  - `np.where()` function for conditional selection
  - Array statistics: sum(), mean(), max(), min(), sort()
  - Complex filtering with multiple conditions
  
- **Key Libraries/Functions:**
  - Array arithmetic: +, -, *, /
  - Boolean indexing: `array[array > value]`
  - Comparison operators: >, <, ==, !=, &, |
  - `np.unique()`: find unique values
  - `np.where()`: conditional replacement
  - `.sum()`, `.mean()`, `.max()`, `.min()`, `.sort()`
  
- **Datasets:** None

---

### **CLASS 11** (05-04-2026)
**Topic:** Pandas - Introduction & Series
- **Main Concepts:**
  - Pandas Series: 1D labeled array
  - Pandas DataFrame: 2D table structure
  - Reading CSV files: `pd.read_csv()`
  - Absolute vs relative file paths
  - Series creation from arrays
  - Data type conversion: `.astype()`
  - Series sorting: `.sort_values()`, `.sort_index()`
  - Indexing: `.iloc[]` (position-based), `.loc[]` (label-based)
  
- **Key Libraries/Functions:**
  - `pd.read_csv()`: read CSV files
  - `pd.Series()`: create Series with data, index, name
  - `pd.DataFrame()`: create DataFrame from dict/list
  - `.astype()`: convert data types
  - `.sort_values()`: sort by values
  - `.sort_index()`: sort by index
  - `.iloc[]`: integer-location based indexing
  - `.loc[]`: label-based indexing
  - `os.getcwd()`: get current working directory
  
- **Datasets:** 
  - `retail_2016_2017.csv`: Retail transaction data

---

### **CLASS 12** (18-04-2026)
**Topic:** Pandas - Data Ingestion & Cleaning
- **Main Concepts:**
  - Reading CSV and Excel files
  - DataFrame inspection: `shape`, `head()`, `tail()`, `info()`, `describe()`, `dtypes`
  - Sampling: `.sample()`
  - Missing values: `.isnull()`, `.sum()`
  - Data cleaning approaches:
    - Handle duplicates
    - Fix null values
    - Fix inconsistent typos
    - Type casting
    - Handle outliers
  - String operations: `.str.replace()`
  - Numeric conversion: `pd.to_numeric()` with error handling
  
- **Key Libraries/Functions:**
  - `pd.read_csv()`: read CSV files
  - `pd.read_excel()`: read Excel files
  - `pd.to_numeric()`: convert to numeric with error handling options
  - DataFrame methods: `.shape`, `.head()`, `.tail()`, `.info()`, `.describe()`, `.dtypes`, `.sample()`
  - Missing data methods: `.isnull()`, `.sum()`
  - String methods: `.str.replace()`, `.str.strip()`
  - `.copy()`: create DataFrame copy
  - Column renaming: `df.columns = [...]`
  
- **Datasets:**
  - `retail_2016_2017.csv`: Retail transaction data
  - `oil.csv`: Oil price data
  - `Run Times.xlsx`: Runtime data with mixed data types

---

## ASSIGNMENT BREAKDOWN

### **ASSIGNMENT 03** (Class 3 - Data Types)
**Topics:** Built-in functions, Numbers, Strings
- **Concepts Practiced:**
  1. Factorial calculation: `math.factorial()`
  2. Random number generation: `random.randint()`
  3. Power calculation: `math.pow()`
  4. Average calculation: `sum()`, `len()`
  5. Maximum value: `max()`
  6. Sum of list: `sum()`
  7. String replacement: `.replace()`
  8. String splitting: `.split()`
  9. Remove spaces: `.replace()`
  10. Find function: `.find()`
  11. Text case: `.upper()`, `.lower()`
  12. Strip whitespace: `.strip()`

- **Key Skills:** Math functions, string manipulation, list operations

---

### **ASSIGNMENT 04** (Class 4 - Data Structures)
**Topics:** Dictionary & List operations
- **Concepts Practiced:**
  1. Dictionary update: `.update()`
  2. Count keys: `len(dict.keys())`
  3. Dictionary pop/get: `.pop()`, `.get()`
  4. Dictionary items: `.items()`
  5. Delete key: `del dict[key]`
  6. Sort by value: `sorted(dict.items(), key=lambda item: item[1])`
  7-16. List operations: append, insert, pop, remove, extend, len, max, min, count, index

- **Key Skills:** Dictionary and list manipulation

---

### **ASSIGNMENT 05** (Class 5 - Data Types Theory)
**Topics:** Theory questions on all data types
- **Theory Questions Covered:**
  - Numbers: int, float, complex, immutability
  - Strings: indexing, slicing, immutability
  - Lists: definition, operations, mutability
  - Dictionaries: structure, unique keys, methods
  - Sets: uniqueness, operations, use cases
  - Tuples: immutability, immutable storage
  - Mutable vs Immutable classification

---

### **ASSIGNMENT 09** (Class 9 - NumPy Arrays)
**Topics:** NumPy array creation and operations
- **Concepts Practiced:**
  1. 1D array creation and inspection
  2. Creating arrays of zeros and ones
  3. 2D array creation with specified dimensions
  4. Python list to NumPy array conversion
  5. Random decimal generation
  6. Random integers with range
  7. Normal distribution random numbers
  8. Mixed array operations
  9. Complex array creation: student IDs, attendance, test scores

- **Key Skills:** NumPy array creation, random number generation with different distributions

---

### **ASSIGNMENT 10** (Class 10 - NumPy Operations)
**Topics:** Array operations, arithmetic, filtering, and advanced concepts
- **Assignment 1:** Array basics - convert list comprehension to array
- **Assignment 2:** Array creation using NumPy functions like `np.arange()`
- **Assignment 3:** Accessing array data - slicing and indexing
- **Assignment 4:** Arithmetic operations - shipping calculations with discounts
- **Assignment 5:** Filtering arrays with boolean masks

- **Key Skills:** Array manipulation, filtering, arithmetic operations, reshaping

---

## CURRICULUM ORGANIZATION BY THEME

### **THEMATIC CLUSTERS**

#### **1. Python Fundamentals (Classes 2-5)**
- **Focus:** Core data types and structures
- **Classes:** 2, 3, 4, 5
- **Topics:** 
  - Built-in functions and modules
  - Numbers (int, float, complex)
  - Strings and string operations
  - Lists and dictionaries
  - Sets and tuples
  - Boolean logic
- **Progression:** Basic → Collections → Operations
- **Assignments:** 3, 4, 5

#### **2. Control Flow & Logic (Class 6)**
- **Focus:** Program flow and decision-making
- **Classes:** 6
- **Topics:**
  - While loops
  - For loops
  - Conditional statements (if/elif/else)
  - Loop control (continue)
  - Compound conditions
- **Practical Application:** Utility bill calculation, password validation
- **Prerequisite:** Classes 2-5

#### **3. Advanced Python Concepts (Class 7)**
- **Focus:** Efficient coding patterns
- **Classes:** 7
- **Topics:**
  - List comprehension
  - Expression-based list creation
- **Connection:** Used in NumPy classes

#### **4. NumPy & Array Computing (Classes 8-10)**
- **Focus:** Numerical computing and array operations
- **Classes:** 8, 9, 10
- **Topics:**
  - Array creation (1D, 2D)
  - Array properties and attributes
  - Indexing and slicing
  - Seeding for reproducibility
  - Arithmetic operations
  - Boolean filtering
  - Statistical functions
  - `np.where()` for conditional operations
- **Progression:** Basic arrays → Indexing → Operations & Filtering
- **Datasets:** Inventory, sales, pricing data
- **Assignments:** 9, 10

#### **5. Data Science Foundations (Classes 11-12)**
- **Focus:** Data manipulation and cleaning
- **Classes:** 11, 12
- **Topics:**
  - Pandas Series and DataFrames
  - File I/O (CSV, Excel)
  - Data inspection methods
  - Missing data handling
  - Data cleaning techniques
  - String operations for data
  - Type conversion and error handling
- **Progression:** Reading data → Inspecting → Cleaning
- **Datasets:** 
  - `retail_2016_2017.csv`: Main learning dataset
  - `oil.csv`: Secondary dataset
  - `Run Times.xlsx`: Data cleaning practice
- **Real-world Application:** Preparing data for analysis

---

## KEY LIBRARIES SUMMARY

| Library | Classes | Main Functions | Use Case |
|---------|---------|-----------------|----------|
| `math` | 2, 3, A3 | `factorial()`, `pow()`, `sqrt()`, `ceil()`, `floor()` | Mathematical calculations |
| `random` | 2, 3, A3 | `randint()`, `random()` | Random number generation |
| `numpy` | 2, 8, 9, 10, A9, A10 | `array()`, `zeros()`, `ones()`, `arange()`, `linspace()`, `where()`, `unique()` | Numerical computing |
| `pandas` | 11, 12 | `read_csv()`, `read_excel()`, `Series()`, `DataFrame()` | Data manipulation |
| `os` | 11 | `getcwd()` | System operations |

---

## DATASETS USED

| Dataset | Classes | Source | Content |
|---------|---------|--------|---------|
| `retail_2016_2017.csv` | 11, 12 | `../data/` | Retail transaction data |
| `oil.csv` | 12 | `../data/` | Oil price/data |
| `Run Times.xlsx` | 12 | `../data/` | Runtime metrics with mixed types |

---

## RECOMMENDED COURSE STRUCTURE

### **Phase I: Fundamentals (Weeks 1-5)**
- **Objective:** Master Python data types and structures
- **Classes:** 2, 3, 4, 5
- **Assignments:** 3, 4, 5
- **Outcomes:** Understanding immutability, collections, and basic operations

### **Phase II: Control Flow (Week 6-7)**
- **Objective:** Program flow and algorithmic thinking
- **Classes:** 6, 7
- **Outcomes:** Loop mastery, conditional logic, code efficiency

### **Phase III: Numerical Computing (Weeks 8-10)**
- **Objective:** Array operations and numerical analysis
- **Classes:** 8, 9, 10
- **Assignments:** 9, 10
- **Outcomes:** NumPy proficiency, filtering, statistical operations

### **Phase IV: Data Science Intro (Weeks 11-12)**
- **Objective:** Data manipulation and preparation
- **Classes:** 11, 12
- **Outcomes:** Reading files, data cleaning, preparing for analysis

---

## SKILL PROGRESSION MAP

```
Class 2: Built-in functions
    ↓
Class 3: Data types (Numbers & Strings)
    ↓
Class 4: Collections (Lists & Dicts)
    ↓
Class 5: More Collections (Sets & Tuples)
    ↓
Class 6: Control Flow (Loops & Conditionals)
    ↓
Class 7: Advanced Python (List Comprehension)
    ↓
Class 8: Numerical Computing (NumPy Basics)
    ↓
Class 9: Array Indexing & Slicing
    ↓
Class 10: Array Operations & Filtering
    ↓
Class 11: Data Structures (Pandas Series)
    ↓
Class 12: Data Cleaning & Preparation
```

---

## DATA TYPES COVERAGE

| Data Type | Class | Mutable | Operations |
|-----------|-------|---------|-----------|
| int | 3 | No | Arithmetic, conversion |
| float | 3 | No | Arithmetic, conversion |
| complex | 3 | No | Arithmetic, conversion |
| str | 3 | No | Indexing, slicing, methods |
| list | 4 | Yes | append, insert, remove, pop, extend |
| dict | 4 | Yes | keys, values, items, get, pop, update |
| set | 5 | Yes | union, intersection, difference, add, remove |
| tuple | 5 | No | Indexing, slicing, unpacking |
| bool | 5 | No | Logical operations |
| ndarray | 8-10 | Yes | Arithmetic, filtering, reshaping |
| Series | 11 | Yes | Indexing, slicing, sorting |
| DataFrame | 11-12 | Yes | I/O, selection, aggregation |

---

## KEY FUNCTIONS BY PURPOSE

### **Mathematical Operations**
- `math.factorial()`, `math.pow()`, `math.sqrt()`, `math.ceil()`, `math.floor()`
- `pow()` (built-in)
- NumPy arithmetic: `+`, `-`, `*`, `/`

### **Random Number Generation**
- `random.randint()`, `random.random()`
- `np.random.default_rng(seed)` (seeded RNG)
- `.rng.random()`, `.rng.integers()`
- `np.random.normal()` (normal distribution)

### **Array Operations**
- Creation: `np.array()`, `np.zeros()`, `np.ones()`, `np.arange()`, `np.linspace()`
- Manipulation: `.reshape()`, `np.unique()`
- Filtering: `np.where()`, boolean indexing
- Statistics: `.sum()`, `.mean()`, `.max()`, `.min()`, `.sort()`

### **Data I/O**
- `pd.read_csv()`, `pd.read_excel()`

### **Data Inspection**
- `.head()`, `.tail()`, `.info()`, `.describe()`, `.dtypes`, `.shape`, `.sample()`

### **Data Cleaning**
- `.isnull()`, `.astype()`, `pd.to_numeric()`, `.str.replace()`

---

## ASSIGNMENTS MAPPED TO CLASSES

| Assignment | Associated Class | Topics | Skills |
|-----------|-----------------|--------|--------|
| A3 | Class 3 | Numbers, Strings, Built-ins | Math functions, string ops, collections |
| A4 | Class 4 | Listed, Dictionaries | Collection methods, sorting |
| A5 | Class 5 | Theory | Data type understanding |
| A9 | Class 9 | NumPy Arrays | Array creation, random generation |
| A10 | Class 10 | NumPy Operations | Filtering, arithmetic, reshaping |

---

## TECHNICAL PREREQUISITES FOR EACH PHASE

**Before Class 2:** Python environment setup

**Before Class 6:** Complete Classes 2-5, understand data types

**Before Class 8:** Complete Classes 2-7, know how to use functions

**Before Class 11:** Complete Classes 8-10, comfort with NumPy

**Before Class 12:** Complete Class 11, Pandas Series understanding

---

## COURSE ASSESSMENT POINTS

1. **Theoretical Understanding** (Assignment 5): Data type concepts
2. **Practical Application** (Assignments 3, 4): Operations on data structures
3. **Numerical Computing** (Assignments 9, 10): Array and numerical operations
4. **Real-world Skills** (Classes 11-12): Data manipulation and cleaning

---

## SUGGESTED FOLLOW-UP TOPICS

After completing this curriculum:

1. **Data Visualization**: Matplotlib, Seaborn
2. **Advanced Pandas**: Groupby, merge, pivot tables
3. **Statistical Analysis**: SciPy, statistics
4. **Machine Learning**: Scikit-learn basics
5. **Data Wrangling**: More complex cleaning scenarios
6. **SQL Integration**: Database interactions with Python

