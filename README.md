# Linear Regression Using Gradient Descent From Scratch

## Overview

This project implements Linear Regression from scratch using Python and NumPy, without relying on machine learning libraries such as Scikit-learn for model training.

The objective is to understand the mathematical foundations of Linear Regression and how Gradient Descent optimizes model parameters by minimizing the cost function.

## Concepts Covered

- Linear Regression
- Hypothesis Function
- Mean Squared Error (MSE) Cost Function
- Partial Derivatives
- Gradient Descent Optimization
- Model Predictions
- Cost Convergence Visualization

## Mathematical Formulation

### Hypothesis Function

\[
h_\theta(x)=\theta_0+\theta_1x
\]

### Cost Function

\[
J(\theta_0,\theta_1)=\frac{1}{2m}\sum_{i=1}^{m}(h_\theta(x^{(i)})-y^{(i)})^2
\]

### Gradient Descent Update Rules

\[
\theta_0 := \theta_0-\alpha\frac{\partial J}{\partial\theta_0}
\]

\[
\theta_1 := \theta_1-\alpha\frac{\partial J}{\partial\theta_1}
\]

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Implementation Details

| Parameter | Value |
|---|---:|
| Learning Rate | 0.01 |
| Iterations | 1000 |
| Initial θ₀ | 0 |
| Initial θ₁ | 0 |

## Results

The algorithm successfully learns the model parameters through iterative optimization.

- Initial Cost: 48.5
- Final Cost: Approximately 0.000699
- Learned θ₀: Approximately 0.9164
- Learned θ₁: Approximately 2.0169

## Visualizations

The notebook includes:

1. Cost convergence graph showing the reduction in cost over iterations.
2. Linear regression graph comparing actual data points with predicted values.

## How to Run

1. Clone this repository.
2. Install the required dependencies.
3. Open the Jupyter Notebook.
4. Run all cells.

```bash
pip install -r requirements.txt
jupyter notebook
```

## Learning Outcome

This project helped develop an understanding of how Linear Regression works internally, particularly how partial derivatives and Gradient Descent are used to optimize model parameters.

---

**Project:** Linear Regression Using Gradient Descent From Scratch  
**Language:** Python