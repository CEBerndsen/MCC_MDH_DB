# Homo sapiens and MDH2
# P40926
# acetylation of K157 (qK133 in structure)


## Description

Lysine 177 of human MDH2 is evaluated to test its potential as a post-translationally modified site. There are no functional studies of the role of this site in human metabolism. Studies of acetylation and KQ substitution suggests the modifications could enhance the activity of MDH2. Entry started 12/06/2024

1. Alignment of MDH2 K133 (purple), MDH2 with ALY 133 (pink), MDH2 with Q133 (blue)
![MDH2, modified, and mimic aligned with modification site, acitve site, and dimer interface labelled](images/align_annotated.png)

2. Modification site
![K133 in MDH2 unmodified, ALY133 in PTM (modified), and GLN 133 in mimimc at the modification site](images/modification_site.png)

3. Modifications at active site 
![K133 in MDH2 unmodified, ALY133 in PTM (modified), and GLN 133 in mimimc at the active site](images/active_site.png)

# The modification site is far from the active site and dimer interface.

## Effect of the sequence variant and PTM on MDH dynamics

The RMSD of MD simulations of MDH2 leveled starting at 0.2. RMSF visualized the movement of each amino acid. A high correlates with more movement. 

1. Annotated RMSF plot showing differences between the simulations
![RMSF plots of unmodified MDH2 and mimic MDH2](images/RMSF.png)

Analysis of significant peaks (~90, ~200, ~300, ~400, and ~600+) from both unmodifed MDH2 and the mimic. Amino acid that correlated with peak ~300 interacts with the modification site. Amino acid that correlated with peak ~400 interacts with the active site. 

2. Comparison of amino acid that correlates with peaks ~90, ~200, and ~600 
![Bonds that interacted with N93 (peak ~90)](images/N93.png)
![Bonds that interacted with T211 (peak ~200)](images/T211.png)
![Bonds that interacted with I12 (peak ~600)](images/I12.png)

## Comparison of the pKa at key sites
The pKa trajectories from the unmodified MDH2 and mimic were compared at the active site and substrate binding sites

1. pKa trajectories at active site and binding sites
![Graph 1 displays pKa trajectory at the active site, graph 2 is the pka trajecories at binding site R86, and graph 3 is the pka trajecories at binding site R80](images/pka.png)

2. Molecular changes at substrate binding sites R86 and R80
![Bonds that interacted with R86](images/R86.png)
![Bonds that interacted with R80](images/R80.png)

## Authors

# Julia L. Hermanson

## Deposition Date
# 12/06/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

* Iwasaki, W.; Tachiwana, H.; et al. (2011). Comprehensive Structural Analysis of Mutant Nucleosomes Containing Lysine to Glutamine (KQ) Substitutions in the H3 and H4 Histone-Fold Domains. Biochemistry, 50(36). 7822-32. ![10.1021/bi201021h](https://doi.org/10.1021/bi201021h)

* Kim, E. Y..; Han, B. S.; et al. (2013). Acceleration of adipogenic differentiation via acetylation of malate dehydrogenase 2. Biochemical and biophysical research communications, 441(1). 77-82. ![10.1016/j.bbrc.2013.10.016
](hhtps://doi.org/10.1016/j.bbrc.2013.10.016)
