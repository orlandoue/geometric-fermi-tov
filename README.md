# Geometric Corrections to Fermi-Dirac Statistics: A Causal Solution to the Pulsar Mass Limit

This repository contains the source code and data generation scripts associated with the paper **"Geometric Corrections to Fermi-Dirac Statistics: A Causal Solution to the Pulsar Mass Limit"**, submitted to *Monthly Notices of the Royal Astronomical Society (MNRAS Letters)*.

**Author:** Orlando Miguel Urbina Gonzalez  
**Affiliation:** Facultad de Física, Pontificia Universidad Católica de Chile  
**Contact:** omurbina@uc.cl

## 📄 Overview

This project implements a modified Equation of State (EoS) for neutron stars based on a geometric suppression of the phase space available for fermions. By introducing a momentum-dependent kernel $\Phi(k)$ into the Fermi-Dirac integrals, we derive a thermodynamically consistent model that stiffens the EoS at high densities.

The code solves the Tolman-Oppenheimer-Volkoff (TOV) equations to demonstrate that this mechanism can support massive pulsars (like **PSR J0952-0607**, $M \approx 2.35 M_{\odot}$) while strictly preserving causality ($v_s < c$) throughout the stellar interior.

## 📂 Repository Structure

* **`figure1_mr.py`**: Main script that generates the Equation of State and solves the TOV equations to produce the Mass-Radius relation (Figure 1 in the paper).
* **`figure2_analysis.py`**: Analysis script that performs the sensitivity scan on the coupling parameter $\alpha$ and calculates the radial profile of the speed of sound (Figure 2 in the paper).
* **`requirements.txt`**: List of Python dependencies required to run the simulations.
* **`output/`**: Directory containing the generated PDF figures.

## 🚀 Installation & Usage

### 1. Clone the repository
```bash
git clone (https://github.com/orlandoue/geometric-fermi-tov)]
cd geometric-fermi-tov
