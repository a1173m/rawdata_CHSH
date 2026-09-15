# rawdata_CHSH
# CHSH Correlation Data

This repository contains the correlation data associated with the CHSH
measurements presented in the research poster.

## Data

The dataset is provided as a CSV file:

- `CHSH_data.csv` — correlation measurements used in the analysis.

## Description

The dataset contains the measured correlation values obtained during
the CHSH experiments.

## Experimental details

Experiments start off with putting the two selected qubits into a Bell state (combination of Hadamard and CNOT gates) and then rotating the qubits by the relative angles of 22½° and 67½°. Both qubits are then measured into the classical register. One such process is considered a shot, a total of 8192 shots per E circuit is run. Each CHSH S-value is made up from 4 such circuits via S = E(ab) + E(a_b) + E(ab_) - E(a_b_).

## Contact

Adele Mikelsaar, IB Diploma Student at Miina Harma gumnaasium
