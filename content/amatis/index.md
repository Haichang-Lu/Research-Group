---
title: AMATIS, an open source workflow for magentism analysis
date: 2025-06-30
---

<!--more-->

Automated Magnetism Analysis via Tensorial Interacting Spins ( AMATIS ) is a structure-to-magnetism tool for calculating spin interactions and predicting the thermal equilibrium properties of magnets, developed by Haichang Lu (卢海昌) of Beihang University. It is written in C++, compiled with the Eigen package. Currently, it is interfaced with the ab initio code VASP. We are working on making it compatible with any package that supports total energy calculations, considering spin-orbit coupling.

The source code, the user manual and the tutorial can be found in 

GitHub:  https://github.com/Haichang-Lu/AMATIS

Zenodo: https://doi.org/10.5281/zenodo.16005430

Note: it is distributed under the GNU GENERAL PUBLIC LICENSE Version 3.

Anyone using the code for calculation and publication should cite the relevant paper: 
"H. Lu, B. Deng, H. Katsumoto, J. Robertson, W. Zhao and S. Blügel, Automated Magnetism Analysis via the Effective Hamiltonian with Tensorial Interacting Spins, J name, (2025)."

Anyone interested in redeveloping, codeveloping, or commercial use should contact Haichang Lu via email: HaichangLu@buaa.edu.cn