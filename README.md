# Emerging Technologies: Classical and Quantum Algorithms

This repository contains a series of implementations and analyses exploring classical and quantum algorithms, with a focus on the Deutsch and Deutsch–Jozsa algorithms. The project demonstrates the transition from classical black-box function analysis to quantum oracles, using both Python and Qiskit, and provides detailed explanations, code, and practical demonstrations.

## Table of Contents

- [Key Sections](#key-sections)
- [Repository Structure](#repository-structure)
- [How to Run the Code](#how-to-run-the-code)
- [Technical Reference](#technical-reference)
- [References](#references)

---

## Key Sections

See [problems.ipynb](problems.ipynb) for detailed implementations:

**Problem 1: Generating Random Boolean Functions**  
Introduces the classical approach to modeling black-box (oracle) functions, including constant and balanced Boolean functions. Demonstrates how closures can be used to hide function details, simulating a classical oracle.

**Problem 2: Classical Testing for Function Type**  
Implements efficient algorithms to determine whether a hidden function is constant or balanced, minimizing the number of queries required. Explains the logic behind input selection and result analysis.

**Problem 3: Quantum Oracles**  
Transitions to quantum computing by constructing quantum oracles for all possible single-input Boolean functions using Qiskit. Explains the mapping between classical and quantum representations.

**Problem 4: Deutsch's Algorithm with Qiskit**  
Implements and demonstrates Deutsch’s algorithm, showing how quantum superposition and interference allow the classification of function types with a single oracle query. Includes code for running and interpreting quantum circuits.

**Problem 5: Scaling to the Deutsch–Jozsa Algorithm**  
Discusses the extension of the Deutsch algorithm to multiple inputs, highlighting the exponential speedup provided by quantum computation.

---

## Repository Structure

```
emerging-technologies/
├── README.md                  # Project overview and setup instructions
├── problems.ipynb             # Main Jupyter notebook with implementations and explanations
├── requirements.txt           # Python dependencies (Qiskit, numpy, etc.)
├── .gitignore                 # Ignore unnecessary files
```

---

## How to Run the Code

Follow these step-by-step instructions to set up and run the project on your local machine:

### Prerequisites

- Python 3.8 or higher ([download here](https://www.python.org/downloads/))
- pip (Python package installer, typically included with Python)
- Jupyter Notebook ([installation guide](https://jupyter.org/install))
- Qiskit ([installation guide](https://qiskit.org/documentation/getting_started.html))

### Step 1: Clone the Repository

Open your terminal or command prompt and run:

```bash
git clone https://github.com/JenniferOji/emerging-technologies.git
```

Navigate into the cloned repository:

```bash
cd emerging-technologies
```

### Step 2: Install Dependencies

Install all required Python packages using pip:

```bash
pip install -r requirements.txt
```

Alternatively, install packages individually:

```bash
pip install numpy qiskit jupyter
```

### Step 3: Launch Jupyter Notebook

Start the Jupyter Notebook server:

```bash
jupyter notebook
```

This will open a new browser window showing the repository contents.

### Step 4: Open and Run the Notebook

1. Click on `problems.ipynb` to open the main notebook
2. You can run all cells sequentially by selecting **Cell -> Run All** from the menu
3. Alternatively, run cells individually by selecting them and pressing **Shift + Enter**

### Step 5: Explore Each Problem

Each problem is clearly marked with a Level 2 heading in the notebook. Work through them sequentially, as later problems build upon earlier implementations.

---

## References

Below are key documentation and resources essential for understanding and using this project:

- [Qiskit Documentation](https://qiskit.org/documentation/): Used for quantum circuit construction, simulation, and visualization.
- [Deutsch Algorithm (IBM Quantum)](https://quantum.cloud.ibm.com/learning/en/modules/computer-science/deutsch-jozsa): Official IBM Quantum learning resource for the Deutsch and Deutsch–Jozsa algorithms.
- [NumPy Documentation](https://numpy.org/doc/stable/): Used for efficient numerical operations and array handling.
- [Jupyter Documentation](https://jupyter.org/documentation): For interactive notebook usage and setup.
- [Superposition and Quantum Oracles](https://en.wikipedia.org/wiki/Quantum_oracle): Background on quantum oracles and their role in quantum algorithms.
- [Classical vs Quantum Algorithms](https://en.wikipedia.org/wiki/Deutsch%E2%80%93Jozsa_algorithm): Overview of the differences and speedups between classical and quantum approaches.

---

**Author**: Jennifer Oji  
**Last Updated**: March 2026