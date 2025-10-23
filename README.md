# 📈 Optimization Practice — Python Numerical Methods

> A Python-based collection of optimization exercises exploring **unconstrained and constrained optimization**,  
> using both analytical and numerical methods.  
> Conducted as part of the *Optimization Methods* course in the **Erasmus Mundus MIR Programme** at Université de Toulon.

---

## 🎯 Objective

The goal of this project was to apply optimization algorithms to engineering and control problems,  
analyzing how numerical methods can find optimal solutions for nonlinear functions and systems.  

Topics covered include:
- Gradient-based optimization (steepest descent, conjugate gradient)
- Newton and quasi-Newton methods
- Constrained optimization using Lagrange multipliers and penalty methods
- MATLAB/Python numerical experiments comparing convergence behavior

---

## 📂 Repository Structure

| Path | Description |
|------|--------------|
| **Course_Materials/** | Lecture slides, theoretical notes, and datasets used for the assignments |
| **Assignement_Codes_HyejoKwon.ipynb** | Main Jupyter Notebook containing all optimization implementations and analysis |
| **README.md** | Project overview and documentation (this file) |

---

## ⚙️ Implemented Methods

| Method | Description |
|--------|--------------|
| **Gradient Descent** | Basic first-order optimization for convex functions |
| **Newton’s Method** | Second-order approach using Hessian information |
| **Conjugate Gradient** | Efficient iterative method for large-scale systems |
| **Penalty & Barrier Methods** | Used for inequality constraints |
| **Lagrange Multipliers** | Analytical approach to equality-constrained problems |
| **Nelder–Mead (Scipy)** | Derivative-free optimization for comparison |

---

## 📊 Key Insights

- Step size and gradient direction strongly affect convergence rate.  
- Newton’s method converges faster but requires accurate Hessians.  
- Penalty and barrier methods work well for constraints but depend on penalty scaling.  
- Analytical gradients validated against **finite difference approximations** in all cases.  
- Visualization of cost surfaces and convergence paths helped interpret optimization dynamics.

---

## 🧩 Tools & Libraries

- **Python**: NumPy · SciPy · Matplotlib · Sympy  
- **Jupyter Notebook**: Visualization and step-by-step derivation  
- **Optimization Theory**: Gradient-based methods, KKT conditions  

---

## 🧠 Learning Outcomes

| Concept | Skill Gained |
|----------|---------------|
| Optimization Algorithms | Implemented first- and second-order numerical methods |
| Constrained Systems | Applied Lagrange and penalty-based formulations |
| Numerical Stability | Learned to tune step size and convergence criteria |
| Visualization | Interpreted cost landscapes and path trajectories |
| Problem Solving | Applied optimization to engineering functions and data fitting |

---

## 👩‍🔬 Author

**Hyejoo Kwon**  
📍 Erasmus Mundus Master’s in *Marine & Maritime Intelligent Robotics (MIR)*  
🧑‍🏫 Instructor: *Prof. Nicolas Petit*  
📅 Submitted: February 2025  

🔗 [GitHub Repository](https://github.com/S1194789/Optimization_Practice)
