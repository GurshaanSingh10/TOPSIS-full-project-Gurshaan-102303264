# TOPSIS Project – Gurshaan Bajwa (Roll No: 102303264)

## Overview
This repository contains a complete implementation of the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** method for solving **Multi-Criteria Decision Making (MCDM)** problems.

TOPSIS is a widely used decision-making technique that ranks alternatives based on their relative closeness to the ideal best and ideal worst solutions.

In this project, TOPSIS has been implemented and deployed in **three different forms**:

1. 📓 **Jupyter Notebook** – For step-by-step explanation and learning
2. 🐍 **Python Package (Published on PyPI)** – For command-line and programmatic usage
3. 🌐 **Web Application** – For user-friendly browser-based interaction

All three versions are linked and documented here.

---

## Project Components

### 1. Jupyter Notebook
The notebook explains:
- What TOPSIS is
- Mathematical formulation
- Step-by-step computation
- Normalization
- Weighted normalized matrix
- Ideal best and worst values
- Distance calculation
- Score computation
- Ranking

This notebook is meant for **learning, demonstration, and academic submission**.

📁 Location: `notebooks/`

---

### 2. Python Package (Published on PyPI)

The TOPSIS algorithm has been converted into a fully functional Python package that can be installed and used from the command line.

🔗 PyPI Link:
https://pypi.org/project/Topsis-Gurshaan-Bajwa-102303264/

#### Installation
```bash
pip install Topsis-Gurshaan-Bajwa-102303264
```

#### Command Line Usage
```bash
topsis <inputfile> <weights> <impacts> <outputfile>
```

Example:
```bash
topsis sample.csv "0.25,0.25,0.25,0.25" "+,+,-,+" result.csv
```

#### Input Format
- First column: Alternatives
- Remaining columns: Numeric criteria

Example:
| Model | Storage | Camera | Price | Looks |
|------|---------|--------|-------|-------|
| M1 | 16 | 12 | 250 | 5 |
| M2 | 16 | 8 | 200 | 3 |
| M3 | 32 | 16 | 300 | 4 |
| M4 | 32 | 8 | 275 | 4 |
| M5 | 16 | 16 | 225 | 2 |

#### Weights
```
0.25,0.25,0.25,0.25
```

#### Impacts
```
+,+,-,+
```

#### Output
The output file will contain TOPSIS Score and Rank.

Higher score = better alternative.

---

### 3. Web Application

A web-based version of the TOPSIS tool has also been created. This allows users to:
- Upload CSV files
- Enter weights and impacts
- Instantly download results

🔗 Live Website:
https://topsis-web-gurshaan-102303264.vercel.app

This version is useful for users who do not want to use the command line or install Python packages.

---

## Features

- Fully automated TOPSIS computation
- Supports any number of criteria
- Input validation
- Error handling
- CSV input/output
- Command-line support
- Web UI support
- Academic-friendly notebook

---

## Error Handling
The implementation validates:

- File existence
- Correct number of weights
- Correct number of impacts
- Numeric-only criteria values
- Valid impact symbols (+ or -)
- Missing or invalid data

---

## Use Cases

- College selection
- Product comparison
- Vendor evaluation
- Stock ranking
- Scholarship selection
- Any MCDM problem

---

## Conclusion

This project demonstrates the practical implementation of the TOPSIS method across multiple platforms — notebook, Python package, and web application. It aims to be both **educational** and **usable**.

---

## Author

**Gurshaan Bajwa**  
Roll No: 102303264

---

If you find this project useful, feel free to star ⭐ the repository and share it.

