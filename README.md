# SWOTein
This repository is an addendum to our paper "SWOTein: A structure-based approach to predict stability Strengths and Weaknesses of prOTEINs". It contains three files corresponding to the three statistical potentials used in the paper: acc.en contains the numerical values of the solvent accessibility potential (Eq.5), tor.en contains the values of the torsion angle potential (Eq.6) and sds.en contains the values of the distance potential (Eq.7). These energy terms are used to predict strong and weak sites in a given protein structure. 

Parameter values used<br /> 
⚫ acc.en: sequence windows of 5 consecutive residues; 5 accessibility bins: 0-5%, 5-15%, 15-30%, 30-50%, 50-100%.<br /> 
⚫ tor.en: sequence windows of 7 consecutive residues; 7 backbone torsion angle domains: A: α-helix: C: 3-10-helix; B: β-strand; P: non-β extended conformation; G: positive ϕ conformation; E: other positive ϕ conformation; O: cis-conformation.<br /> 
⚫ sds.en: sequence windows of 7 consecutive residues; 25 distance bins of 0.2 Å width, from 3.0 to 8.0 Å with an additional bin for distances < 3.0 Å and another for distances > 8.0 Å; distances are computed between average side chain geometric centers.
sdvsdvsd
