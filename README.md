# Solar Wind Interactions with a Planetary Off-Center Mini-Magnetosphere: A Case Study for Mars

**Master of Science thesis (2022)**  
**Author:** Sajal Gupta  
**Supervisor:** Dr. Dibyendu Nandi  
**Institution:** Indian Institute of Science Education and Research (IISER) Kolkata — Center of Excellence in Space Sciences India (CESSI)  
**Date:** May 1, 2020

This repository hosts my Master's thesis PDF

---

## Thesis PDF

- **Final_Thesis.pdf** — the full thesis manuscript.

---

## Abstract (from the thesis)

The presence of an archaic, strong, dynamo-generated global magnetic field of
Earth is considered one of the fundamental reasons for its habitability. How-
ever, several studies have recently cast severe doubts on it. There is a resurgence
of interest in the role of planetary magnetic field on planetary habitability. The
specific question(s) that drives this study are: Do habitable worlds require a mag-
netic field? Or, keeping all other habitable requirements equal, would a planet
without intrinsic magnetic field lose more of its atmosphere rendering it inhab-
itable? Mars lacks a global intrinsic magnetic field, but it has the small-scale,
localized regions of strong magnetic field distributed inhomogeneously in its
crust. Dominance of crustal magnetic field in the southern hemisphere of Mars
makes it a great natural laboratory to understand the effects of the planetary
magnetic fields in star-planet interactions.

We carry out 3D compressible magnetohydrodynamic (MHD) simulations for a
hypothetical Sun-Mars system with a Star-Planet Interaction Module (SPIM) cre-
ated at CESSI, based on the PLUTO code. An off-centered, weak dipolar mag-
netic field is incorporated in the southern part of the planet to mimic the effects
of the crustal field. We simulate three different cases: (a) planet with no dipolar
field, (b) planet with the mini-magnetosphere in which the interplanetary mag-
netic field is oriented southward, and (c) northward, relative
to the direction of the planetary dipole axis. We discover a hybrid magnetic topol-
ogy in the simulations when the planetary magnetic field is switched on.

During interactions of the mini-magnetosphere with southward interplanetary magnetic field, we estimate a 0.5%
higher local mass-loss rate from the Northern Hemisphere compared to the
Southern Hemisphere. To illuminate the effects of interplanetary magnetic field polarity we
compare the local mass-loss rates for northward and southward cases. The moment of truth arises
when we compare the total local mass-loss rates of the no-dipole case with the
southward and northward cases: the mass-loss rates in the absence of the crustal field are
estimated to be 2% and 3% higher than the southward and northward cases.

---

## What’s inside (chapter-level map)

The thesis is organized into three main parts:

- **Part I — Role of magnetic field in star–planet interactions**
  - Chapter 1: *Magnetic field: boon or bane* (and why this matters for habitability)

- **Part II — Mars as a natural laboratory + the numerical model**
  - Chapter 2: *Mars* (crustal magnetic field, and the “new” Mars–Sun interaction picture)
  - Chapter 3: *Numerical model* (MHD equations, domain/grid, boundary driving, and setup)

- **Part III — Results**
  - Chapter 4: hybrid magnetic topology and downstream magnetic structure
  - Chapter 5: plasma boundaries (bow shock, magnetopause-like features, signatures)
  - Chapter 6: atmospheric erosion (mass-flux / “local escape” diagnostics across cases)
  - Chapter 7: conclusion

Appendices include atmosphere profiles, dipole-field equations, Rankine–Hugoniot conditions, and additional results.

---

## Methods at a glance

- **Model:** 3D compressible magnetohydrodynamics
- **Code:** PLUTO-based SPIM module developed at CESSI
- **Mini-magnetosphere:** off-centered weak dipole placed to mimic Mars’ strongly localized southern-hemisphere crustal fields
- **Cases:**  
  1) **No dipole**  
  2) **Southward interplanetary magnetic field** (relative to dipole axis)  
  3) **Northward interplanetary magnetic field** (relative to dipole axis)

> Note: The thesis uses the term “magnetic reconnection” in places when discussing magnetic topology changes in the simulations. Interpreting that physics depends on the modeled resistivity/numerical diffusion and the assumptions of the single-fluid MHD framework.

---
