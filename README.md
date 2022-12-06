# Quantum Singular Value Transform and Topological Data Analysis:

The problem chosen to analyze is given by the paper *"[A streamlined quantum algorithm for topological data analysis with exponentially fewer qubits](https://arxiv.org/abs/2209.12887)"*
### Objective:
Estimate persistent Betti numbers with a quantum algortihm and proving an exponential speedup over classical algorithms.
### Method
Reduce the problem to estimating the normalised rank of a projector that encodes the relevant topological feature
of the data, and show how this problem can be efficiently solved using quantum singular value transformation (QSVT).

Betti numbers are topological invariants of a dataset that measure the number of holes that survive from one length scale to another. The normalised rank of a projector is used to encode the relevant topological features of the data, which can then be used to calculate Betti numbers.

### Definitions:
- A **streamlined quantum algorithm** is a type of algorithm that uses quantum computing to solve problems more quickly than traditional methods.
It is designed to be more efficient and faster than existing algorithms, and can be used to analyze and classify data in machine learning applications.

- **Topological data analysis (TDA)** is a method of analyzing data that uses algebraic topology to classify topological objects. It is used to identify patterns in data that are robust to noise and perturbations, and can be used to interpret datasets, compare different datasets, and as input to machine learning models.
 
- **Persistent Betti Numbers** are a type of topological invariant that measure the number of holes in a given space. They are used to track how the number of holes changes over time, and can be used to identify features in a data set. A topological invariant is a property of a space that remains unchanged under continuous deformations. It can be used to classify different shapes and spaces, as well as measure the complexity of those shapes.
 
- The **projector matrix** is a mathematical tool used to encode the important features of a dataset. It is composed of elements that represent the data points and their relationships with each other. The normalised rank of this matrix can be used to determine how many topological features are present in the dataset, which can help classify it for machine learning applications.
 
- The **normalised rank of a projector** is a measure of the complexity or size of the data set. It is calculated by dividing the number of non-zero elements in the projector matrix by its total number of elements. This value can be used to determine how many topological features are present in a dataset and can help classify it for machine learning applications. 

- **Quantum singular value transformation (QSVT)** is a technique that allows for the efficient application of a polynomial function to the singular values of a matrix given by a unitary block encoding.

- **Unitary block encoding** is a method of representing a matrix as the product of two unitary matrices. This can be used to efficiently apply polynomial functions to the singular values of the matrix. Singular values can be used to calculate Betti numbers, and polynomial functions can be applied to them using QSVT.

### Talks on QSVT:
- [A. Gilyen: Quantum Singular Value Transformation – A Unifying framework of quantum algorithms](https://www.youtube.com/watch?v=M46T_GfZ5XU) [[Slides](https://simons.berkeley.edu/sites/default/files/docs/15033/simonsprez2.pdf)] *July 6 2022*:
> An n-qubit quantum circuit performs a unitary operation on an exponentially large, $2^n$-dimensional, Hilbert space, which is a major source of quantum speed-ups. We show how Quantum Singular Value Transformation can directly harness the advantages of exponential dimensionality by applying polynomial transformations to the singular values of a block of a unitary operator. The transformations are realized by quantum circuits with a very simple structure  typically using only a constant number of ancilla qubits leading to optimal algorithms with appealing constant factors. We show that this framework allows describing and unifying many quantum algorithms on a high level, and enables remarkably concise proofs for many prominent quantum algorithms, ranging from optimal Hamiltonian simulation to quantum linear equation solving (i.e., the HHL alorithm) and advanced amplitude amplification techniques. Finally, we also prove a quantum lower bound on spectral transformations.

- [Shorter talk by A.Gilyen: ](https://www.youtube.com/watch?v=TzoP9c1N0Do) *July 23 2022* 

### Papers of interest
In [this issue](https://github.com/Marioherreroglez/QSVT_TDA/issues/1) we discuss relevant and preceding papers to better understand this work.

### Code application
- As this work is based on QSVT we could potentially use the work done [here](https://github.com/bartubisgin/QSVTinQiskit-2021-Europe-Hackathon-Winning-Project-) to better understand the concept and give an example of application.
- [Here](https://github.com/kc-howe/Betti-Numbers) is a repository which computes Betti numbers of a topological space.


