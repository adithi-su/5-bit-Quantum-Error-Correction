# 5 qubit-Quantum-Error-Correction

Pre-requisites:
```
pip install qiskit
pip install pylatexenc
```
The five-qubit error correcting code is the smallest quantum error correcting code that can protect a logical qubit from any arbitrary single qubit error. In this code, 5 physical qubits are used to encode the logical qubit and checks for bit flip, phase flip and mixed (bit+phase) errors. 
The code involves:  
1. Encoding
2. Error syndrome detection 
3. Error correction
4. Decoding 

References:  
1. <a href="https://qiskit.org/"> Qiskit docs </a>
2. Quantum Computing -  From Linear Algebra to Physical Realizations: Mikio Nakahara, Tetsuo Ohmi - Chapter 10 Error correcting codes
3. <a href="https://en.wikipedia.org/wiki/Five-qubit_error_correcting_code"> Wiki article </a>
