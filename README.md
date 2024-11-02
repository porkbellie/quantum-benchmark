# quantum-benchmark
Benchmarking Quantum Optimization with Rydberg Atom Systems

## MIS3
Jupyter notebook with code to solve MIS problem and generate distributions for each parameter of interest on Amazon Braket SDK

### Progress
- Produce random connected drop out lattice graphs
- Graphs seeded
- Solutions must be valid but not necessarily correct
- Average performance metrics over n graphs at each parameter value
- One parameter is varied at a time with the others constant

### Current
- 3 parameters varied: Omega, Delta, T_rise
- Distributions generated for 500 shots
- ~260 min runtime

### To do
- Parallelize?
- Vary T_flat, T_max?
