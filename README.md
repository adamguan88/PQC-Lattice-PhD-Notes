PQC Lattice PhD Notes

PhD-level lecture notes on lattice-based post-quantum cryptography.

This repository is a personal study and research project focused on the mathematical foundations, security assumptions, reductions, and cryptanalysis of lattice-based cryptography.

Course Roadmap

01 — Lattice Basics

- Euclidean lattices
- Basis and dimension
- Fundamental parallelepiped
- Short vectors
- Closest vectors

02 — Learning With Errors

- The LWE assumption
- Search-LWE
- Decision-LWE
- Error distributions
- Worst-case to average-case reductions

03 — Short Integer Solutions

- The SIS problem
- Average-case hardness
- Connections to lattice problems

04 — Ring-LWE

- Polynomial rings
- Algebraic structure
- Ring-LWE assumption
- Efficiency and security considerations

05 — Module-LWE

- Modules over polynomial rings
- Ring-LWE vs. Module-LWE
- The role of algebraic structure

06 — Security Reductions

- Reduction-based security
- Worst-case lattice problems
- What reductions actually prove
- The gap between provable hardness and concrete security

07 — Cryptanalysis

- Lattice reduction
- BKZ
- Enumeration
- Hybrid attacks
- Concrete security estimation

A Central Question

A recurring question throughout these notes is:

$$
\text{How much algebraic structure should we introduce into a lattice-based assumption?}
$$

Structure can provide substantial efficiency gains, but it may also introduce additional algebraic properties that could potentially be exploited by an attacker.

Understanding this trade-off is central to the design of practical post-quantum cryptographic systems.

---

Author

Adam

Cybersecurity & Mathematical Foundations of Post-Quantum Cryptography

---

«These notes are intended as a research-oriented study project. They are continuously revised as I work through the literature.»