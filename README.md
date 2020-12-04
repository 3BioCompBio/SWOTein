# SWOTein
Here there are some files related to our paper "SWOTein: A structure-based approach to predict stability Strengths and Weaknesses of prOTEINs". More in details there are three files corresponding to three statistical potentials used in the paper: acc.en contains the numerival values of the solvent accessibility statistical potentials (Eq.5), tor.en contains the numerical value of the torsion angle domain statistical potential (Eq.6) and sds.en contains the numerical values of the distance statistical potentials (Eq.8). This energetic terms are used to define the strengh/weakness properties of a residue in the given 3D protein structure. 

Parameter used<br /> 
⚫ acc.en: windows along the sequence considered 5, number of solvent accessibility bins = 5 (0-5%, 5-15%, 15-30%, 30-50%, 50-100%).<br /> 
⚫ tor.en: windows along the sequence considered 7, number of torsion angle domain = 7 (α-helix A, 3-10-helix C, β-stand B, extended conformation P, positive ϕ G, positive ϕ E, cis-conformation O)<br /> 
⚫ sds.en: windows along the sequence considered 7 (the frequencies are considered separately for residue separation along the sequence of 2 to 7 residues, and considered together for separations of 8 residues and more), number of distance bins of 0.2 Å = 25 from 3.0 to 8.0 Å width one additional bin for d<3.0 Å and one for d>8.0 Å <br /><br />

The sizes of the sequence windows appearing in the definition ofthe potentials, Eqs (5)-(7), have been chosen to obtain the lowest average folding free energy values on the dataset D.

Difference with the preliminary SWOTein version of de Laet et al. (2016):<br />
- Sequence windows of all potentials have been changed (precviously = 2) <br />
- Solvent accessibity potential of Eq. (5) has been modified (previously DWsaa + DWssa)/2) <br />
- Torsion potential of Eq. (6) has been modified (previously DWstt + DWsst)/2) <br />
- The database for deriving the potetials has been updated <br />
