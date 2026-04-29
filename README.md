# quantum_circuit

A small playground for poking at Qiskit. `1_setup.py` builds a Bell pair, samples it, and plots the result histogram — about as minimal as quantum hello-world gets.

## Run

```bash
pip install qiskit qiskit-ibm-runtime matplotlib
python 1_setup.py
```

`hello-world.ipynb` is the same idea in notebook form.

`ibm_quantum_platorm_instructions.txt` has my notes for connecting to IBM Quantum's hosted backends if you want to run on real hardware instead of the local statevector simulator.
