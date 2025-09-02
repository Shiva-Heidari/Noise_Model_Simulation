# Qiskit Mini-Lab: Simulating Noise & State Initialization

Hands-on Qiskit 2.x exercises that:
- Compare **ideal** vs **noisy** execution of a Bell circuit using Aer’s **`density_matrix`** simulator and a realistic noise model (**T₁/T₂ + gate durations**, **depolarizing**, **readout**).
- Demonstrate **custom state preparation** via `initialize(...)` for all qubits and **subsets** of qubits.
- Visualize outcomes with simple **probability bar charts**.

## Contents

- `notebooks/`
  - `one_cell_noisy_bell.ipynb` — One-cell, fully commented demo: ideal vs noisy Bell.
  - `init_bell_direct.ipynb` — Prepare \(|00⟩+|11⟩)/√2 directly with `initialize` + plot.
  - `init_subset_1_2_3.ipynb` — Initialize only qubits `[1,2,3]` in a 4-qubit circuit + plot.
  - `markdown/`
    - `before_code.md` — Pre-code concept explainer (problem setup).
    - `after_code.md` — Post-code results interpretation.
 



