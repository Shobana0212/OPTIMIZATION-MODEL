
## 🏢 Internship Details

- **Company**: CODTECH IT SOLUTIONS  
- **Intern Name**: Shobana Balusamy
- **Intern ID**: CITS0D117  
- **Domain**: Data Science
- **Duration**: 4 Weeks  
- **Mentor**: Neela Santosh  

# 📊 Business Optimization Using Linear Programming in Python (PuLP)

## 🚀 Project Overview

This project demonstrates how to solve a real-world business optimization problem using **Linear Programming (LP)** techniques with Python. The problem chosen is a classic **Product Mix Optimization** scenario where a company produces two types of products and wants to **maximize profit** under resource constraints such as labor hours and raw materials.

This project is designed as a beginner-friendly guide and is implemented entirely in a **Jupyter Notebook** using **Anaconda** and the `PuLP` library. The notebook includes problem definition, mathematical model formulation, Python implementation, and result interpretation.

---

## 🧠 Problem Description

A company manufactures two products: **Product A** and **Product B**. Each product requires a certain amount of labor and raw materials and contributes a specific profit. Due to resource limitations, the company must decide the **optimal number of units** of each product to manufacture in order to **maximize total profit**.

### Problem Data:
- **Profit per unit**: ₹20 for Product A, ₹30 for Product B
- **Labor hours per unit**: 2 hours for A, 4 hours for B (max 100 hours available)
- **Raw material per unit**: 3 units for A, 2 units for B (max 90 units available)

### Objective:
Maximize total profit subject to the labor and material constraints.

---

## 🧰 Tools and Technologies Used

- **Python 3** (via Anaconda)
- **Jupyter Notebook**: For interactive coding and documentation
- **PuLP**: Python library for Linear Programming
- **Pandas & Matplotlib** *(optional)*: For data analysis and visualization
- **Anaconda Navigator**: Used to manage the Python environment and launch notebooks

---

## 🛠️ Methodology

The approach followed in this project includes:

1. **Problem Formulation**:
   - Identified decision variables (units of Product A and B).
   - Defined the objective function to maximize profit.
   - Translated constraints into linear inequalities.

2. **Model Implementation**:
   - Used `PuLP` to define the LP model, variables, objective function, and constraints.
   - Solved the model using PuLP’s solver.
   - Extracted and printed the optimal solution.

3. **Result Interpretation**:
   - Displayed optimal production quantities for both products.
   - Calculated and printed the maximum achievable profit.
   - Discussed how resource limitations influence production decisions.

---

## 📝 How to Run the Project

### Prerequisites
Ensure you have the following installed:

- **Anaconda** (https://www.anaconda.com/products/distribution)
- **Jupyter Notebook** (comes with Anaconda)
- **PuLP Library** (install via pip)

### Installation
Launch Jupyter Notebook and run the following command in a notebook cell (if PuLP is not already installed):

```python
!pip install pulp

<img width="1919" height="1009" alt="Image" src="https://github.com/user-attachments/assets/975d31a0-202b-4e3e-b557-b469bfcf039e" />
