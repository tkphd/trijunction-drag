# Multiphase Interface Planarization

Tóth *et al.* (*Physical Review B* **92** (2015) 184105) reviewed competing
multiphase-field models for thermodynamic consistency and kinetic stability of planar
interfaces at equilibrium. This repository contains multiphase-field models intended
for evolution of multiphase systems with pairwise-asymmetric interfacial
properties. The example codes demonstrate equilibration of the planar binary
interface produced upon collapse of a ternary system with one phase encapsulated
within a circular domain (grain). The models are based on the excellent write-up in
Ref. 1, with specific details in further references. Numerical simulations for three
of the most popular/significant/relevant models are implemented in the subdirectories
using [MMSP](https://github.com/mesoscale/mmsp).

![ternary potentials](ternary-potentials.png)
*Contour plots of bulk free energy potentials, generated by `simplex.py`.*

1. Tóth, Pusztai, Gránásy. "Consistent multiphase-field theory for interface
   driven multidomain dynamics." *Physical Review B* **92** (2015) 184105.
2. Steinbach and Pezzolla. "A generalized field method for multiphase
   transformations using interface fields." *Physica D* **134**:4 (1999) 385-393.
3. Moelans, Blanpain, Wollants. "Quantitative analysis of grain boundary
   properties in a generalized phase field model for grain growth in anisotropic
   systems." *Physical Review B* **78** (2008) 024113.
