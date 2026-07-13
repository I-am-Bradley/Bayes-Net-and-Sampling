# Bayes Net and Sampling
## 🧭 Project Overview

### Title:
Bayes Net and Sampling

### Purpose:
This repository implements exact and approximate inference algorithms for Bayesian Networks alongside continuous probability sampling techniques. The project compares inference accuracy, convergence behavior, and computational tradeoffs between multiple probabilistic reasoning algorithms while demonstrating foundational concepts in uncertainty modeling and probabilistic AI.

### Audience:
- Artificial Intelligence Students
- Machine Learning Engineers
- Data Scientists
- Researchers studying Probabilistic Graphical Models

---

# 🧱 Repository Structure

```bash
Bayes-Net-and-Sampling/
├── README.md
├── bayes_net_and_sampling.py
├── results/
│   ├── Convergence Comparison (4-node).png
│   ├── Convergence Comparison (15-node).png
│   ├── Sampling Distribution Plots/
│   └── Additional Figures/
└── Report/
    └── CS Project 4 Report.docx
```

---

# 📊 Project Summary

This repository combines two major probabilistic AI topics into a single implementation.

### Bayesian Network Inference

Implements and compares multiple inference algorithms for Bayesian Networks, including:

- Elimination-ASK (Exact Inference)
- Likelihood Weighting
- Gibbs Sampling (Markov Chain Monte Carlo)

Experiments compare:

- Exact vs. approximate inference
- Convergence as sample size increases
- Performance on both a 4-node and a 15-node Bayesian Network

---

### Continuous Probability Sampling

Implements three classical sampling techniques used throughout statistics and machine learning.

Algorithms include:

- Inverse Transform Sampling
- Rejection Sampling
- Box-Muller Transform

Experiments evaluate:

- Distribution accuracy
- Estimated expectation and variance
- Sampling efficiency
- Convergence toward theoretical probability density functions

---

# 🚀 Running the Code

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Bayes-Net-and-Sampling.git
```

Install the required packages

```bash
pip install numpy matplotlib networkx
```

Run the project

```bash
python bayes_net_and_sampling.py
```

The program executes all Bayesian Network inference experiments and continuous sampling experiments, generating console output, convergence statistics, and visualization plots.

---

# 🧠 Algorithms Included

## Bayesian Network Inference

### Elimination-ASK
- Exact probabilistic inference using variable elimination
- Computes posterior probabilities by eliminating hidden variables

### Likelihood Weighting
- Importance sampling algorithm
- Approximates posterior probabilities using weighted samples

### Gibbs Sampling
- Markov Chain Monte Carlo (MCMC) inference
- Iteratively samples variables conditioned on their Markov Blanket

---

## Continuous Probability Sampling

### Inverse Transform Sampling
Generates exponentially distributed random variables using the inverse cumulative distribution function.

### Rejection Sampling
Generates samples from an arbitrary target distribution using an acceptance-rejection process.

### Box-Muller Transform
Produces normally distributed random variables from uniformly distributed samples.

---

# 📈 Results

The repository includes visualizations demonstrating:

### Bayesian Networks

- Convergence Comparison (4-node Network)
- Convergence Comparison (15-node Network)
- Exact vs. Approximate Inference
- Sample-size convergence analysis

### Continuous Sampling

- Exponential Distribution (Inverse Transform)
- Rejection Sampling Distribution
- Normal Distribution (Box-Muller)
- Distribution convergence with increasing sample sizes

---

# 📄 Documentation

The complete project report is included in:

```text
Report/
└── CS Project 4 Report.docx
```

The report includes:

- Bayesian Network construction
- Exact inference derivations
- Approximate inference analysis
- 4-node Bayesian Network experiments
- 15-node Bayesian Network experiments
- Continuous sampling experiments
- Convergence analysis
- Performance comparisons and discussion

---

# 💡 Skills Demonstrated

- Bayesian Networks
- Exact Probabilistic Inference
- Approximate Inference
- Variable Elimination
- Gibbs Sampling
- Likelihood Weighting
- Markov Chain Monte Carlo (MCMC)
- Continuous Probability Sampling
- Monte Carlo Simulation
- Probability Theory
- Statistical Analysis
- Data Visualization
- Scientific Computing with Python

---

# 👤 Author

**Bradley Titagwan**
