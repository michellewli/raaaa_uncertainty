# Team Uncertainty

## Members
Irene Yang, İlayda Dilek, Michelle Li, Maksym Yemelianenko, Mattias Larsson

## About Us
We are a group of students from NYU Tandon School of Engineering, with backgrounds in Applied Physics, Computer Science, and Computer Engineering. We are participating in the **NYC Quantum Computing Hackathon** and tackling the **SandboxAQ Challenge**.

## Project Overview
Our project simulates the **ground and excited states of Lithium Hydride (LiH)** using advanced quantum computing algorithms. By exploring quantum chemistry and applying quantum computing to molecular electronic structure calculations, we aim to contribute to the growing intersection of quantum computing and materials science.

## Objective
- Simulate **ground state** and **excited states** of LiH using **Variational Quantum Eigensolver (VQE)** and **Trotter-Suzuki decomposition** for time evolution.
- Utilize quantum algorithms to calculate molecular Hamiltonians, providing a more efficient approach compared to classical computation.
  
## Methodology
1. **Molecule Selection**: We chose LiH for its simplicity and relevance in quantum chemistry.
2. **Basis Sets**: We used **6-311+G(d,p)** and **6-31G(d,p)** basis sets for accuracy.
3. **Ansatz Design**: Developed the ansatz to approximate the ground state.
4. **Hamiltonian Calculation**: Calculated the electronic Hamiltonian for LiH.
5. **Ground & Excited States**: Computed eigenvalues using VQE.
6. **Error Mitigation**: Implemented **frozen orbitals** to optimize the system.

## Data & Results
- **Basis Set 6-311+G(d,p)** yielded a ground state energy of **-7.995 eV**.
- The **6-31G(d,p)** basis set showed comparable results with a ground state energy of **-7.988 eV**.
- **Excited state energy** calculations produced results within **0.01 eV** of the theoretical estimates.

## Tools & Technologies
- **Quantum Frameworks**: Tangelo, Qiskit
- **Algorithms**: Variational Quantum Eigensolver (VQE)

## Future Work
- Extend our ansatz and algorithms to support larger molecules.
- Explore more efficient algorithms to reduce computation time and improve accuracy.

## License
This project is licensed under the GNU General Public License v3.0.