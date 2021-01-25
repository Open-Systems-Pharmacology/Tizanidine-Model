The general workflow for building an adult PBPK model has been described by Kuepfer et al. ([Kuepfer 2016](#5-References)). Relevant information on the anthropometry (height, weight) was gathered from the respective clinical study, if reported. Information on physiological parameters (e.g. blood flows, organ volumes, hematocrit) in adults was gathered from the literature and has been incorporated in PK-Sim® as described previously ([Willmann 2007](#5-References)). The  applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available 'PK-Sim® Ontogeny Database Version 7.3' ([PK-Sim Ontogeny Database Version 7.3](#5-References)).

Since concentration-time profiles following intravenous administration are not publicly available, model building was based on data following oral administration. In general, the following step-wise workflow was followed:

1. Fit intrinsic CL of CYP1A2, and Weibull absorption parameters (renal elimination fixed to GFR) using data from single dose studies where 4 or 8 mg tablets where given in the fasted state to healthy volunteers. The fitting was done for each of the five tissue distribution models available in PK-Sim. 
2. Predictions for fed-state. If adjustments are necessary, only absorption relevant parameters are fitted.
   - Tablet-Fed (2, 4, 8 mg)
   -  Capsule-Fed (4, 8 mg)
3. Model evaluation: Predict multiple dosing of 4 mg (tablet, fasted) using the best model and parameters from the previous step. If no adjustment of parameters is necessary, move on to next step.

The predefined “Standard European Male for DDI” individual (age = 30 y, weight = 73 kg, height = 176 cm, BMI = 23.57 kg/m2) was used for simulations.

Simulations of capsule administrations in fed state were carried out by adding the "High-fat breakfast" meal event at time = 0 in PK-Sim. Simulations of tablets administration in fed state were carried out without a food event but with adjusted dissolution profile.

To judge the predictive variability of the model, a population simulation was carried out generating a virtual population of 2000 healthy European male subjects with the weight and age range according to [Granfors 2004](#5-References) (21 – 31 years, 65 – 83 kg).

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#2.2-Data).

Details about the structural model and its parameters can be found in [Section 2.3](#2.3-Model-Parameters-and-Assumptions).
