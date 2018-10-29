## Team Description

### PI
- **Tetsuya Sakurai** (University of Tsukuba)

### co-PI
- **Shao-Liang Zhang** (Nagoya University)
- **Toshiyuki Imamura** (RIKEN)
- **Yusaku Yamamoto** (University of Electro-Communications)
- **Yoshinobu Kuramashi** (University of Tsukuba)
- **Takeo Hoshi** (Tottori University)

### Research Period
2011-2018

## Published Software

- [z-Pares](http://zpares.cs.tsukuba.ac.jp): Sparse eigen-engine
- [EigenExa](http://www.r-ccs.riken.jp/labs/lpnctrt/en/projects/eigenexa/): Dense eigen-engine

## Project Overview

In many cases, numerical computation arising in many fields such from fundamental science to industrial applications finally will return to solve very large eigenvalue problems. Various algorithms have been proposed, as most of them are implemented recursively or designed based on one parallel hierarchical mode, it is difficult to efficiently perform those algorithms for post-petascale machines with hierarchical architecture. The aim of this research is to develop a massively parallel eigenvalue analysis engine for post-petascale machines with a hierarchical parallel structure. The developed engine is based on newly designed algorithms created to address issues of scalability and fault tolerance that have plagued conventional eigenvalue methods. For high performance and practical applications, a variety of techniques need to be developed, such as sparse-dense hybrid methods, Krylov subspace methods, construction of performance modeling and its evaluation, implementation techniques for multi-cores and real applications etc. This analysis engine will open new doors for cutting-edge science and engineering simulations on scales that have never been feasible in the past, and then create a potential for stimulating technological innovation across a broad range of areas in science and industry.

## Reseach Groups

- Sakurai’s group
 * Theory construction of hierarchical algorithms for computing eigenvalues and development of high performance techniques
 * Implementation for petaflops environment and evaluation using real applications

- Zhang’s group
 * Robust and high performance numerical linear algorithms

- Imamura’s group
 * Study of matrix transition methods based on recursive algorithms
 * Study of implementation technique for GPUs and multi-coresImplementation for petaflops environment and evaluation using real applications
 
- Yamamoto’s group
 * Development of algorithms for computing the eigenvalues of dense matrices
 * Development of performance modeling and automatic optimization techniques

- Kuramashi’s group
 * Verification using real applications and feedback to developers
 * Technical development for high performance in real applications
 
- Hoshi’s group
 * Evaluation of SMP dense matrix solvers using real applications in material science
 * Development of algorithms for solving sparse matrices from real applications
 

