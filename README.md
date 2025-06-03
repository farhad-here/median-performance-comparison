# Median Performance Comparison

This project compares the performance and result of calculating the **median** using two approaches:

- **Vanilla Python** (pure Python logic with sorting)
- **NumPy library** (optimized C-based implementation)

---

## 📊 Goal

- Generate 100 random integers between **20 and 60**
- Compute the **median** using:
  - Plain Python
  - NumPy
- Compare the **execution time** of both methods
- Interpret the **meaning of the median**

---

# 📌 Interpretation

<pre style="color:green;padding:1rem;background-color:black">The median is the middle value of a sorted list. It is useful for understanding the central tendency of a dataset, especially when the data contains outliers, as it is less sensitive to them compared to the mean.</pre>

⚖️ Conclusion
- Both methods return the same median value

- NumPy performs faster than plain Python, especially for large datasets

# 🧰 Requirements
1. Python 3.x

2. NumPy

Install NumPy:
```python
pip install numpy
```
# 🧑‍💻 Author
Made with ❤️ by FarhadGhaherdoost