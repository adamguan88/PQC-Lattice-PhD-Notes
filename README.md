# PQC Lattice PhD Notes

## PhD-Level Lecture Notes on Lattice-Based Post-Quantum Cryptography

A research-oriented set of lecture notes on the mathematical foundations of lattice-based post-quantum cryptography.

The goal is to move progressively from mathematical foundations to cryptographic assumptions, security reductions, and cryptanalysis.

---

## Course Roadmap

### 01 — Lattice Basics

- Lattices
- Bases
- Rank and dimension
- Norms
- Short vectors
- SVP
- CVP

### 02 — Learning With Errors

- LWE
- Search-LWE
- Decision-LWE
- Error distributions
- Worst-case to average-case reductions

### 03 — Short Integer Solutions

- SIS
- Average-case hardness
- Connections to lattice problems

### 04 — Ring-LWE

- Polynomial rings
- Algebraic structure
- Ring-LWE
- Efficiency and security

### 05 — Module-LWE

- Modules over polynomial rings
- Ring-LWE vs. Module-LWE
- Structured lattice assumptions

### 06 — Security Reductions

- Computational hardness
- Worst-case hardness
- Average-case hardness
- Reduction techniques

### 07 — Cryptanalysis

- LLL
- BKZ
- Enumeration
- Sieving
- Hybrid attacks
- Concrete security estimation

---

## Central Research Question

A recurring question throughout these notes is:

How does algebraic structure affect the security and efficiency of lattice-based cryptography?

In particular:

$$
\text{structure}
\longrightarrow
\text{efficiency}
$$

but potentially also:

$$
\text{structure}
\longrightarrow
\text{additional attack surface}.
$$

This creates a fundamental trade-off between efficiency and security.

---

## Research Philosophy

The course follows the progression:

$$
\text{intuition}
\rightarrow
\text{definition}
\rightarrow
\text{problem}
\rightarrow
\text{reduction}
\rightarrow
\text{cryptanalysis}
\rightarrow
\text{research question}.
$$

The goal is not simply to memorize cryptographic constructions.

The goal is to understand why their underlying assumptions are believed to be hard, what theoretical reductions actually establish, and where the remaining uncertainty lies.

---

## Author

**Adam Guan**

Cybersecurity & Mathematical Foundations of Post-Quantum Cryptography