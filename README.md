[![](https://img.shields.io/badge/arXiv-2003.07355%20-red.svg)](https://arxiv.org/abs/2003.07355)

# CLASS_EDE: CLASS for Early Dark Energy

*Updated version based on class v3.2.0. Original version of CLASS_EDE is available [HERE](https://github.com/mwt5345/class_ede)*

A modified version of the publicly available Einstein-Boltzmann code [CLASS](https://github.com/lesgourg/class_public) to implement Early Dark Energy (EDE). CLASS_EDE solves for the evolution of the scalar field perturbations directly using the perturbed Klein-Gordon equation and implements adiabatic initial conditions for the scalar field fluctuations. The code allows one to specify the EDE model parameters in terms of the particle physics parameters *f* and *m* or effective EDE parameters *f_EDE* and *z_c*.

See [Hill et al.](https://arxiv.org/abs/2003.07355) where CLASS_EDE is implemented to test the validity of the EDE model. 

![](https://github.com/mwt5345/class_ede/blob/master/class/figures-for-paper/scf/fEDE_v_z.png) <!-- .element height="10%" width="10%" -->

## CLASS edited by
- J. Colin Hill; jch2200 at columbia.edu
- Evan McDonough; evan_mcdonough at brown.edu
- Michael W. Toomey; michael_toomey at brown.edu

## Installation

After cloning or downloading the repository, compile CLASS_EDE with make

$ make class

