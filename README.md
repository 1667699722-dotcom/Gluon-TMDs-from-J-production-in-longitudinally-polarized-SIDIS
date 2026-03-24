# Gluon-TMDs-from-J-production-in-longitudinally-polarized-SIDIS
Mathematica/FeynCalc implementation for gluon TMDs from J/ψ production in longitudinally polarized SIDIS

## 论文关联
**Reference**: H. Liu, X. Xie, Z. Lu, Gluon TMDs from J/ψ production in longitudinally polarized deeply inelastic scattering, Phys. Lett. B 849 (2024) 138439.
**DOI**: [10.1016/j.physletb.2023.138439](https://doi.org/10.1016/j.physletb.2023.138439)

## 研究背景
This code is the numerical/analytic implementation of our published work in Phys. Lett. B 849 (2024) 138439, which investigates the gluon transverse-momentum-dependent distribution functions (TMDs) via J/ψ production in semi-inclusive deeply inelastic scattering (SIDIS) with a longitudinally polarized nucleon target. The work focuses on the sin2φ azimuthal asymmetry (sensitve to T-odd gluon TMD $h_{1 L}^{\perp g}$) and double longitudinal spin asymmetry $A_{LL}$ (sensitve to $g_{1 L}^{g}$).

## 代码功能
1. Analytic derivation of the scattering amplitude for $\gamma^*g\to J/\psi$ via NRQCD color-octet mechanism;
2. Calculation of the differential cross section for J/ψ production in longitudinally polarized SIDIS;
3. Numerical simulation of the $sin2\phi_T$ azimuthal asymmetry $A_{UL}$ and double longitudinal spin asymmetry $A_{LL}$;
4. Verification of the positivity bound for the T-odd gluon TMD $h_{1 L}^{\perp g}$;
5. FeynCalc-based Feynman diagram calculation and tensor reduction (for hard scattering subprocesses).

## 依赖工具
- Mathematica 12.0+
- FeynCalc 9.0+ (Feynman diagram and tensor calculation package)

## 文件说明
- `GluonTMDs_Jpsi_SIDIS.nb`: Core code for analytic derivation of amplitude/cross section and numerical calculation of asymmetries;
