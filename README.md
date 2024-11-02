# quantum-benchmark
Benchmarking Quantum Optimization with Rydberg Atom Systems

Jupyter notebooks with code to solve MIS problem and generate distributions for each parameter of interest on Amazon Braket SDK

### MIS_OD
Varies/measures parameters omega and delta

### MIS_T
Varies/measures parameters T_rise, T_max, T_flat

### Progress
- Produce random connected drop out lattice graphs
- Graphs seeded
- Solutions must be valid but not necessarily correct
- Average performance metrics over n graphs at each parameter value
- One parameter is varied at a time with the others constant

### Current
- 5 parameters varied: Omega, Delta, T_rise, T_max, T_flat
- Distributions generated for 500 shots
- MIS_OD: ~180 min runtime (exp)
- MIS_T: ~260 min runtime

### To do
- Parallelize?
