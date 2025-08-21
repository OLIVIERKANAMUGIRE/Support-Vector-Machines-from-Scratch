# Nonlinear Support Vector Machine (SVM) with Polynomial Kernel

This project implements a **Nonlinear Support Vector Machine (SVM)** from scratch in Python using **Quadratic Programming (QP)** with the help of the [cvxopt](https://cvxopt.org/) optimization library.  
The model uses a **polynomial kernel** to separate non-linearly separable data and is tested on a small dataset (`t030.csv`).  

The implementation includes:
- Training SVM with a polynomial kernel
- Identifying support vectors
- Plotting decision boundaries
- Train-test split evaluation
- Accuracy calculation

---

## Project Overview
Support Vector Machines (SVMs) are powerful supervised learning models for classification tasks. While **linear SVMs** work on linearly separable data, this implementation extends SVM to **nonlinear classification** using a **polynomial kernel**.

We solve the optimization problem using **cvxopt quadratic programming solver**.
![Results of classification](smv.png)

---

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/OLIVIERKANAMUGIRE/Support-Vector-Machines-from-Scratch.git
