# NumPy and Pandas Operations in Python

This notebook provides a comprehensive overview and practical examples of various operations using the NumPy and Pandas libraries in Python. It covers fundamental array manipulations, arithmetic operations, data type handling, indexing, slicing, iteration, array restructuring, and data merging/grouping with Pandas.

## Table of Contents

- [NumPy Array Creation](#numpy-array-creation)
- [NumPy Array Attributes](#numpy-array-attributes)
- [NumPy Arithmetic Operations](#numpy-arithmetic-operations)
- [NumPy Array Functions](#numpy-array-functions)
- [NumPy Array Reshaping](#numpy-array-reshaping)
- [NumPy Broadcasting](#numpy-broadcasting)
- [NumPy Indexing & Slicing](#numpy-indexing--slicing)
- [NumPy Iteration](#numpy-iteration)
- [NumPy Copy vs View](#numpy-copy-vs-view)
- [NumPy Join & Split](#numpy-join--split)
- [NumPy Search & Sort](#numpy-search--sort)
- [NumPy Filter & Unique](#numpy-filter--unique)
- [NumPy Insert & Delete](#numpy-insert--delete)
- [NumPy Matrix Operations](#numpy-matrix-operations)
- [Pandas Merge & Concat](#pandas-merge--concat)
- [Pandas Groupby](#pandas-groupby)
- [Pandas Join](#pandas-join)
- [Pandas Melt Function](#pandas-melt-function)

## NumPy Array Creation
Demonstrates various ways to create NumPy arrays, including from lists, using `np.array()`, `np.zeros()`, `np.ones()`, `np.empty()`, `np.arange()`, `np.eye()`, `np.linspace()`, and random number generation functions (`np.random.rand`, `np.random.randn`, `np.random.ranf`, `np.random.randint`).

## NumPy Array Attributes
Examples of checking array dimensions (`ndim`) and data types (`dtype`).

## NumPy Arithmetic Operations
Covers basic arithmetic operations (addition, subtraction, multiplication, division, modulo) on NumPy arrays, including scalar operations and element-wise operations between arrays.

## NumPy Array Functions
Illustrates the use of mathematical functions like `np.min()`, `np.max()`, `np.sqrt()`, `np.sin()`, and `np.cumsum()`.

## NumPy Array Reshaping
Shows how to change the shape of arrays using `reshape()` and flatten arrays using `reshape(-1)`.

## NumPy Broadcasting
Examples of broadcasting rules in NumPy for operations between arrays of different shapes.

## NumPy Indexing & Slicing
Demonstrates how to access elements or subsets of arrays using indexing and slicing techniques.

## NumPy Iteration
Methods for iterating over array elements using basic loops, `np.nditer()`, and `np.ndenumerate()`.

## NumPy Copy vs View
Explains the difference between creating a copy and a view of a NumPy array and their implications on data modification.

## NumPy Join & Split
Examples of combining arrays using `np.concatenate()`, `np.stack()`, `np.hstack()`, `np.vstack()`, and splitting arrays using `np.array_split()`.

## NumPy Search & Sort
Covers searching for elements using `np.where()` and `np.searchsorted()`, and sorting arrays using `np.sort()`.

## NumPy Filter & Unique
Demonstrates filtering arrays with boolean indexing and finding unique elements using `np.unique()`.

## NumPy Insert & Delete
Examples of adding and removing elements from NumPy arrays using `np.insert()` and `np.delete()`.

## NumPy Matrix Operations
Introduces NumPy's matrix capabilities, including matrix creation, arithmetic operations, dot product, transpose, and linear algebra functions like `np.linalg.matrix_power()` and `np.linalg.det()`.

## Pandas Merge & Concat
Illustrates how to combine DataFrames using `pd.merge()` for various join types (`how='outer'`, `suffixes`) and `pd.concat()` for stacking or joining along an axis.

## Pandas Groupby
Examples of grouping data in DataFrames using `groupby()` and performing aggregation functions like `min()`, `max()`, and `mean()`.

## Pandas Join
Demonstrates the `join()` method for combining DataFrames based on their indices.

## Pandas Melt Function
Shows how to transform DataFrames from a wide format to a long format using `pd.melt()`.
