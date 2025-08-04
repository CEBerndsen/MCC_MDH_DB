# Homo sapiens (Human) and Mitochondrial Malate Dehydrogenase 2 (MDH2)
# P40926
# Original Residue: Tyrosine (Y) at position 32
Modified Residue: Aspartic Acid (D) at position 32


## Description

# Mitochondrial malate dehydrogenase 2 (MDH2) is a key TCA cycle enzyme responsible for the reversible conversion of malate to oxaloacetate while generating of NAD+ to NADH. This reaction plays a significant role in energy production, redox balance, and biosynthetic pathways in eukaryotic cells. MDH2 activity is modulatively controlled through post-translational modifications (PTMs) with phosphorylation being one of the most abundant, either destabilizing or stabilizing its conformation, dynamics, and catalytic efficiency. Here we investigate the structural and functional consequences of PTMs at residue Y32, a candidate regulatory site that is relevant to MDH2's function in cellular metabolism.

1. image of the unmodified site
![Superposed structural representation of Y32 in its unmodified state (TYR 32). Y32 stabilizes distal loops and the dimer interface via hydrogen bonds and hydrophobic interactions, critical for MDH2 catalysis. Phosphorylation (PTR 32) introduces a negative charge, altering electrostatics and loop mobility, while the mimic variant (ASP 32) partially retains flexibility but lacks phosphorylation's structural effects.](images/MDH2.png)

2. image of modification site
![This figure specifically points out the mimic variant (ASP 32) in MDH2, further demonstrating the addition of a negatively charged residue at position 32. In the structural context, however, decreased phosphorylation could still partially mimic the effect noted, bearing a similar electrostatics landscape without carrying the steric wall of a phosphate group. This dynamic change affects local flexibility and dimer interface dynamics.
](images/Variant.png)


## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report

1. Image of aligned PDB files (no solvent)
![This image shows the aligned PDB structures of MDH2 at residue 32, comparing the unmodified state (TYR 32), phosphorylated state (PTR 32), and mimic variant (ASP 32). The alignment brings out structural alterations at residue 32, where PTR 32 is associated with rigidity, ASP 32 retains intervened pliancy and TYR 32 sustains local immovability through hydrogen bonding and hydrophobic interactions.](images/pdbaligned.png)

2. Image of the site with the aligned PDB files (no solvent)
![Aligned PDB structures of MDH2 at residue 32 show both the unmodified (TYR 32) and phosphorylated (PTR 32) states, alongside the mimic (ASP 32) variant. A potential residue mapped to the highlighted residue shows structural divergence, with PTR 32 adding steric bulk and a negative charge, while ASP 32 adds only charge. These changes are well correlated with the loss of loop flexibility, dimer stability, and substrate binding kinetics.](images/SitePDBnosolvent.png)

3. Annotated RMSF plot showing differences between the simulations
![RMSF comparison between Y32-modified (blue) and unmodified MDH2 (orange). The mimic variant exhibits higher flexibility in certain regions (e.g., residues 92, 313) and reduced flexibility at residue 32 due to ASP 32's electrostatic effects. Differences in flexibility near residues 222 and 417 suggest the unmodified state may have slightly greater structural dynamics in those areas. These variations highlight the impact of Y32 modification on loop dynamics, substrate accessibility, and potential intersubunit interactions.](images/RMSFGraph.png)

4. Annotated plots of pKa for the key amino acids
![pKa comparison for His 176 in mimic variant (blue) and unmodified MDH2 (orange). Mimic variant shows higher pKa values (~6.0–7.0) due to ASP 32's electrostatic effects, while unmodified MDH2 has lower pKa values (~2.5–4.0), favoring proton transfer. These differences highlight the influence of Y32 on active site dynamics, substrate interactions, and catalytic efficiency.](images/PKAGraph.png)

5. If needed, show ligand bound images and how modification affects substrate binding

Description of the data and changes


## Comparison of the mimic and the authentic PTM
![The left side shows the superimposed Phosphorylated Y32 (PTR 32) and the right shows the Mimic Variant Y32 (ASP 32). Adding a bulky and negatively charged phosphate group with PTR 32 stabilizes the dimer interfacial region but destabilizes loop regions, thereby limiting the access of the substrate and overall catalytic activity. The negative charge is mimicked by ASP 32, but no steric bulk is present, thus allowing for higher loop flexibility and less apparent dimer stabilization and local dynamics at that position. Although the electrostatic effects of phosphorylation are mimicked by ASP 32, its inability to provide steric effect makes it an incomplete mimic.](images/Side by side.png)

Part 4 from the Project 4 report outline
include images as needed


## Authors

Michael B. Bastawrous 

## 12/06/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

* Dosztányi Z. Prediction of protein disorder based on IUPred. Protein Sci. 2018 Jan;27 ![10.1002/pro.3334](https://doi.org/10.1002/pro.3334)

* Grant, B. J.; Rodrigues, A. P.; ElSawy, K. M.; McCammon, J. A.; Caves, L. S. Bio3D: An R Package for the Comparative Analysis of Protein Structures. Bioinformatics 2006, 22 (21), 2695–2696. ![10.1093/bioinformatics/btl461](https://doi.org/10.1093/bioinformatics/btl461)

* Takahashi-Íñiguez, T.; Aburto-Rodríguez, N.; Vilchis-González, A. L.; Flores, M. E. Function, Kinetic Properties, Crystallization, and Regulation of Microbial Malate Dehydrogenase. J. Zhejiang Univ. Sci. B 2016, 17 (4), 247–261 ![10.1631/jzus.B1500219](https://doi.org/10.1631/jzus.B1500219)

* Hopkins, E.; Belknap, C.; Crowe, M. Physiology, Acid Base Balance. National Library of Medicine. ![https://www.ncbi.nlm.nih.gov/books/NBK507807/.]()

* UniProt. ![https://www.uniprot.org/uniprotkb/P40926/entry.]()

* Team ZONTAL. DiffDock – A Diffusion Model for Molecular Docking. ZONTAL. ![https://zontal.io/diffdock-a-diffusion-model-for-molecular-docking-2/ ]()

