### 2.3.1 Absorption

Release of tizanidine from the tablet is modelled using the Weibull-formulation, with parameter values identified by fitting the model to observed concentration profiles after po administration of 4 and 8 mg to healthy volunteers after an overnight fast.

The same parameter values are used for the capsule and tablet formulations in fasted state. In the fed state, the capsule formulation is equal to that in the fasted state. For the tablet formulation, the parameter values differ from those in fasted state.

### 2.3.2 Distribution

Physico-chemical parameters were set to the reported values (see [Section 2.2.1](#221-in-vitro-and-physico-chemical-data)). It was assumed that the major binding partner in plasma is albumin.

After testing the available organ-plasma partition coefficient and cell permeability calculation methods available in PK-Sim, observed clinical data were best described by choosing the partition coefficient calculation by `Berezhkovskiy` and cellular permeability calculation by `PK-Sim Standard`.

### 2.3.3 Metabolism and Elimination

Metabolization of tizanidine is modeled as CYP1A2 Intrinsic clearance. with parameter `Intrinsic clearance` being identified by fitting the model to concentration data after po administration.

Glomerular filtration with `GFR fraction = 1` has been assumed.

### 2.3.4 Automated Parameter Identification

Following parameter values were estimated for the base model:

- Intrinsic CL (CYP1A2)

- Dissolution shape (Weibull formulation)

- Dissolution time (50% dissolved) (Weibull formulation)
