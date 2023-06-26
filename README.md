# Diatomic-Py-SrF

A useful repo for computing quantities relevant for ^2$\Sigma$ diatomic molecules like SrF.
Adapted by Qian from the Diatomic-Py module (for ^1$\Sigma$ molecules) created by Simon Cornish's group at Durham.
Paper reference: https://www.sciencedirect.com/science/article/pii/S0010465522002314

Basic idea: 
1. Input molecular constants relevant to SrF
2. Construct molecular hyperfine Hamiltonian
3. Add in effects from static external B-field (Zeeman), static external E-field (DC Stark)
4. Numerically diagonalize to find eigenenergies and eigenstates.


<!-- Best practices:

1. specify function argument type (int, float, etc) and output type
2. specify output functions in sub-modules (using leading underscore in function name to indicate internal functions and specify \_\_all\_\_ argument)
3. use dataclass instead of dict -->
