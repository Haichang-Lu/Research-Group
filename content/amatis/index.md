---
title: AMATIS, an open source workflow for magentism analysis
date: 2025-06-30
---

<!--more-->

Automated Magnetism Analysis via Tensorial Interacting Spins ( _AMATIS_ ) is a structure to magnetism tool to predict the thermal equilibrium properties of magnets, developed by Haichang Lu of Beihang University. It is written in c++ and needs to compile with the Eigen package. Currently, it can interface only with the _ab initio_ code VASP, but we are working on it to be compatible with any package that supports total energy calculations considering spin-orbit coupling. 

The source code, the user manual and the tutorial can be found in GitHub:  https://github.com/Haichang-Lu/AMATIS

Note: it is distributed under the GNU GENERAL PUBLIC LICENSE Version 2

Anyone using the code for calculation and publication should cite the relevant paper: 

"H. Lu, B. Deng, H. Katsumoto, J. Robertson, W. Zhao and S. Blügel, Automated Magnetism Analysis via the Effective Hamiltonian with Tensorial Interacting Spins, J name, (2025)."

Anyone who is interested in redeveloping, codeveloping, commerical use should contact Haichang Lu via email: HaichangLu@buaa.edu.cn