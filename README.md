# Quantum-memory-channel-
Simulation of open quantum system dynamics for quantum channels with memory

Hello!

Here I represent dynamic simulation of tensor network that describes quantum channels with memory.

Script "Quantum memory channel dynamic simulation and dataset generation" is necessary for dataset generation thjis dataset is number of one-shot projective measurements.

Dataset from "Quantum memory channel dynamic simulation and dataset generation" is used in  script "Dynamic rebuilder".

"Dynamic rebuilder" is supervised learning algorithm that uses dataset in order to find effective hamiltonian that will describe dynamic of open quantum system as true hamiltonian.

Methods "dynamic learning" was taken from my collegues and changed for quantum channel purpose (https://github.com/GrigorievDmitry/Machine-learning-of-Markovian-embedding-for-non-Markovian-quantum-dynamics)



From the picture:
\Phi[\varrho(t)] = U(H)\varrho_{S+E}(0)U(H)^{+}
U(H) - evolution operator
q_{k_{i}} - enter states
\phi_{k_{i}} - states after measure
S - state system at the beginning
E - stete environment at th beginning
![alt text](https://pp.userapi.com/c850636/v850636246/152e88/WNYkqp0rzpU.jpg)
 \begin{equation}\Phi\end{equation}
