# Computational Programming in Chemical Reaction Engineering

**Advanced C++ Programs for Solving Chemical Reaction Equations using Runge-Kutta and Newton-Raphson Methods**


---

## 📌 Introduction

This project explores the application of advanced numerical methods—primarily the 4th order Runge-Kutta and Newton-Raphson algorithms—in solving chemical reaction engineering problems. The C++ programs developed here are designed to simulate dynamic chemical reactions, solve ordinary differential equations (ODEs), and determine equilibrium compositions with high accuracy.

By integrating mathematical rigor with computational efficiency, this framework aims to:
- Optimize reaction conditions
- Streamline chemical process simulations
- Provide reliable insights for research and engineering applications

---

## 🎯 Objectives

- **Robust C++ Program Development:** Modular, object-oriented, and maintainable code.
- **Comprehensive Reaction Simulation:** Support for multiple species and reaction kinetics.
- **Enhanced Accuracy:** Error control and stable numerical solutions.
- **Optimization:** Efficient computation without sacrificing accuracy.
- **Documentation:** Clear guides and comments for accessibility.

---

## 🛠 Materials and Methods

### Runge-Kutta Method
Used for solving ODEs that describe reaction kinetics. The method estimates the next value of a variable by computing slopes at several intermediate points, improving accuracy over simpler methods.

**Workflow:**
1. **Initialization:** Set initial values for all variables.
2. **Iteration:** At each step, compute intermediate slopes and update variables.
3. **Repetition:** Continue until the desired accuracy or endpoint is reached.

### Newton-Raphson Method
Applied for equilibrium calculations, using the Jacobian matrix to iteratively solve nonlinear equations.

---

## 🗂 Project Structure

- `another_set/`: Additional C++ programs for matrix operations and reactor models.
- `Initial Value Problems/`: Problem statements (images) for initial value ODEs.
- `Initial Value solutions/`: C++ solutions for the initial value problems.
- `PlugFlowReactor problems/`: Problem statements (images) for plug flow reactor (PFR) scenarios.
- `PlugFlow Solutions/`: C++ solutions for PFR problems.

---

## 📈 Results

The C++ programs successfully solve chemical kinetics and reactor design problems using the Runge-Kutta and Newton-Raphson methods.

**Sample Output:**
```
Fa = 38.5441
Fb = 154.456
Fc = 154.456
Volume = 2.092
```
Results show strong agreement with analytical solutions, validating the accuracy of the numerical approach.

---

## ✅ Conclusion

- Developed a robust, modular C++ framework for chemical reaction engineering problems.
- Achieved accurate simulation of various chemical reactions and reactor models.
- Ensured code maintainability and extensibility for future enhancements.

---

## 📚 References

1. *Chemical Reaction Engineering* by Octave Levenspiel
2. *Introduction to Numerical Methods in Chemical Engineering*
3. *Numerical Methods in Chemical Engineering* by Dr. Pradeep Ahuja

---

## 📝 Supervisor

**Name:** Dr. Pradeep Ahuja  

---

## 💡 How to Run

1. Ensure you have a C++ compiler (e.g., g++, clang++) installed.
2. Navigate to the relevant directory (e.g., `Initial Value solutions/` or `PlugFlow Solutions/`).
3. Compile the desired `.cpp` file:
   ```
   g++ 4_1.cpp -o 4_1
   ```
4. Run the executable:
   ```
   ./4_1
   ```
   *(On Windows, use `4_1.exe` instead of `./4_1`)*

---

## 📬 Contact

For questions or contributions, please contact the author. 
