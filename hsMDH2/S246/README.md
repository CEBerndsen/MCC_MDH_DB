# Homo sapien MDH2
# Uniprot ID: P40926
# Variation: Phosphorylation of S246 (pS222 in structure)


## Description
Serine 246 (222 in this structure) of human Malate Dehydrogenase 2 (MDH2) was identified as a potential post-translational modification site in this study. The modification at this site, including phosphorylation (P246) and its aspartic acid mimic (S246D), was found to induce electrostatic shifts that affect the enzyme's structure, stability, and function. While the S246D mimic captures some of the electrostatic changes of phosphorylation, it does not fully replicate the structural rearrangements and interactions brought about by phosphorylation. These findings suggest that modifications at this site could influence enzyme activity and substrate binding, potentially impacting key metabolic processes like the citric acid cycle. There are no known studies on the functional role of this specific modification in human MDH2 to date.


1. image of the unmodified site
![Unmodified site of MDH2](images/Unmodified_Site.png)

2. image of modification site
![The modification site contains a phosphoserine residue, which may facilitate enhanced molecular interactions through electrostatic or hydrogen bonding, potentially strengthening the overall binding affinity or structural stability.](images/Modified_Site.png)


## Effect of the sequence variant and PTM on MDH dynamics


1. Image of aligned PDB files (no solvent)
![Structural alignment of MDH2, represented in dark green (left) and orange (right), with its phosphoserine 246-modified form (light green left, yellow right), as well as the S246D mutant (purple left, pink right), reveals distinct conformational changes at the modification site. These variations may provide insights into how phosphorylation and substitution of serine with aspartate influence enzyme function and substrate binding dynamics.](images/align.png)

2. Image of the site with the aligned PDB files (no solvent)
![Alignment of the modification site within MDH2, comparing the phosphoserine modification and its aspartic acid mimic, reveals potential for distinct and intriguing bonding interactions. The introduction of phosphorylation or the aspartate substitution may alter local electrostatic environments, thereby influencing substrate recognition, enzyme conformation, or catalytic efficiency.](images/Modification_Site_Aligned.png)![alt text](images/Modification_Site_Aligned_2.png)
3. Annotated RMSF plot showing differences between the simulations
![unmodified MDH2 showed relatively stable behavior, with two major peaks at residues 90 (RMSF ~1.6) and 310 (RMSF ~1.9). Smaller RMSF peaks were observed at residues 180 (RMSF ~1.3), 200 (RMSF ~1.25), 210 (RMSF ~1.4), 490 (RMSF ~1.1), and 510 (RMSF ~1.15. These regions likely correspond to areas of slight flexibility, which may play a role in substrate binding, enzyme regulation, or conformational transitions during catalysis.](images/RMSF_MDH2.png)![Modified MDH2 exhibited a significant increase in RMSF at residues 220 (RMSF ~1.7), 310 (RMSF ~2.7), 400 (RMSF ~2.3), and 510 (RMSF ~1.5), indicating more pronounced conformational fluctuations in these regions. Notably, the increase at residue 220 corresponds to the site of modification, suggesting that the introduced change has a direct impact on local protein dynamics.](images/RMSF_Modified.png)![Mimic variant displayed a substantial increase in RMSF values, particularly at residues 90 (RMSF ~2.6) and 400 (RMSF ~3.7), suggesting greater flexibility in these regions.](images/RMSF_Mimic.png)

4. Annotated plots of pKa for the key amino acids
![The pKa values of histidine at the active site of MDH2 range from 5.7 to 6.1, which is optimal for catalysis as it allows partial protonation under physiological conditions. Modifications like the aspartic acid mimic (5.76–6.14) and phosphoserine (5.73–6.05) lower the pKa slightly.
](images/PKA_Histidine_Active_Site.png)
5. If needed, show ligand bound images and how modification affects substrate binding

Description of the data and changes
RMSF analysis of unmodified MDH2 revealed stable behavior with notable peaks at residues 90 (RMSF ~1.6) and 310 (RMSF ~1.9), along with smaller peaks at residues 180, 200, 210, 490, and 510, indicating slight flexibility. In contrast, the mimic variant exhibited increased RMSF values, particularly at residues 90 (RMSF ~2.6) and 400 (RMSF ~3.7), suggesting greater flexibility in these regions. The modified MDH2 also showed higher RMSF at residues 220 (RMSF ~1.7), 310 (RMSF ~2.7), 400 (RMSF ~2.3), and 510 (RMSF ~1.5), indicating increased conformational fluctuations. The increase at residue 220, the site of modification, suggests a direct impact of the change on local protein dynamics. The pKa values of histidine at the active site typically range from 5.7 to 6.1, which supports catalysis by allowing partial protonation under physiological conditions. Modifications like the aspartic acid mimic (5.76–6.14) and phosphoserine (5.73–6.05) lower the pKa slightly, affecting protonation states and potentially influencing the enzyme's catalytic mechanism.


## Comparison of the mimic and the authentic PTM

Part 4 from the Project 4 report outline
include images as needed
![The modified MDH2 variant with phosphorylation at residue 220 introduces a bulky phosphate group that disrupts the local loop structure, alters backbone geometry, and changes electrostatic interactions, potentially stabilizing or destabilizing the protein. This modification also affects protein function by modulating interactions, enzyme activity, and substrate binding, and can induce allosteric changes that influence broader regulatory processes. The S246D mimic, where serine is replaced by aspartic acid, creates a similar electrostatic shift, but its bulkier side chain and carboxyl group cause steric clashes and alter protein dynamics differently than phosphorylation. While the mimic can simulate some electrostatic effects, it lacks the complex hydrogen bonding and ionic interactions of phosphorylation. Overall, the S246D mimic approximates some aspects of phosphorylation but cannot capture all of its effects on MDH2.](images/Mimic_Modified_Aligned.png)

## Authors

Contributors names
Eli Brockwell

## Deposition Date
12/06/2024
## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

* Citation1 de Lorenzo, L.; Stack, T. M. M.; Fox, K. M.; Walstrom, K. M. (2024). Catalytic Mechanism and Kinetics of Malate Dehydrogenase. Essays in Biochemistry, 68 (2), 73–82. ![10.1042/ebc20230087](https://pubmed.ncbi.nlm.nih.gov/38813781/)

* Citation2 Vinogradov, A. D. (2008). NADH/NAD+ Interaction with NADH: Ubiquinone Oxidoreductase (Complex I). Biochimica et Biophysica Acta (BBA) - Bioenergetics, 1777 (7–8), 729–734.![10.1016/j.bbabio.2008.04.014.](https://www.sciencedirect.com/science/article/pii/S000527280800100X)

* Citation3 Schwartz, S. D. (2023). Protein Dynamics and Enzymatic Catalysis. The Journal of Physical Chemistry B, 127 (12), 2649–2660.![10.1021/acs.jpcb.3c00477](https://pmc.ncbi.nlm.nih.gov/articles/PMC10072970/)

* Citation4 Kotarkonda, L. K.; Sinha, T. P.; Bhoi, S.; Tyagi, A.; Kumar, A.; Singh, V. P.; Bharathala, S. (2023). Nanoparticles as Potential Antimicrobial Agents for Enzyme Immobilization in Antimicrobial Wound Dressings. Antimicrobial Dressings, 43–60.![10.1016/b978-0-323-95074-9.00009-9](https://www.sciencedirect.com/science/article/abs/pii/B9780323950749000099#:~:text=Nanoparticles%20in%20antimicrobial%20dressings%20reduce,support%20systems%20for%20enzyme%20immobilization.)

* Citation5 Strickler, S. S.; Gribenko, A. V.; Gribenko, A. V.; Keiffer, T. R.; Tomlinson, J.; Reihle, T.; Loladze, V. V.; Makhatadze, G. I. (2006). Protein Stability and Surface Electrostatics: A Charged Relationship. Biochemistry, 45 (9).![10.1021/bi0600143.s001](https://pubmed.ncbi.nlm.nih.gov/16503630/)

* Citation6 Tarrant, M. K.; Cole, P. A. (2009). The Chemical Biology of Protein Phosphorylation. Annual Review of Biochemistry, 78 (1), 797–825.![10.1146/annurev.biochem.78.070907.103047](https://pmc.ncbi.nlm.nih.gov/articles/PMC3074175/)

* Citation7 Martinez-Vaz, B. M.; Howard, A. L.; Jamburuthugoda, V. K.; Callahan, K. P. (2024). Insights into the Regulation of Malate Dehydrogenase: Inhibitors, Activators, and Allosteric Modulation by Small Molecules. Essays in Biochemistry, 68 (2), 173–181.![10.1042/ebc20230087](https://pubmed.ncbi.nlm.nih.gov/38813781/)

* Citation8 Vander Heiden, M. G.; Cantley, L. C.; Thompson, C. B. (2009). Understanding the Warburg Effect: The Metabolic Requirements of Cell Proliferation. Science, 324 (5930), 1029–1033.![10.1126/science.1160809](https://www.science.org/doi/10.1126/science.1160809)

* Citation9 Zhou, H.-X.; Pang, X. (2018). Electrostatic Interactions in Protein Structure, Folding, Binding, and Condensation. Chemical Reviews, 118 (4), 1691–1741.![10.1021/acs.chemrev.7b00305](https://pubs.acs.org/doi/10.1021/acs.chemrev.7b00305)

* Citation10 Selvaraj, C.; Rudhra, O.; Alothaim, A. S.; Alkhanani, M.; Singh, S. K. (2022). Structure and Chemistry of Enzymatic Active Sites That Play a Role in the Switch and Conformation Mechanism. Advances in Protein Chemistry and Structural Biology, 59–83.![10.1016/bs.apcsb.2022.02.002](https://pubmed.ncbi.nlm.nih.gov/35534116/)

* Citation11 Lee, J. M.; Hammarén, H. M.; Savitski, M. M.; Baek, S. H. (2023). Control of Protein Stability by Post-Translational Modifications. Nature Communications, 14 (1). ![10.1038/s41467-023-35795-8](https://pubmed.ncbi.nlm.nih.gov/36639369/)

* Citation12 Li, X.; Foley, E. A.; Kawashima, S. A.; Molloy, K. R.; Li, Y.; Chait, B. T.; Kapoor, T. M. (2013). Examining Post‐translational Modification‐mediated Protein–Protein Interactions Using a Chemical Proteomics Approach. Protein Science, 22 (3), 287–295.![10.1002/pro.2210](https://pmc.ncbi.nlm.nih.gov/articles/PMC3595459/)

* Citation13 Kim, M. O.; Nichols, S. E.; Wang, Y.; McCammon, J. A. (2013). Effects of Histidine Protonation and Rotameric States on Virtual Screening of M. Tuberculosis RMLC. Journal of Computer-Aided Molecular Design, 27 (3), 235–246.![10.1007/s10822-013-9643-9](https://link.springer.com/article/10.1007/s10822-013-9643-9)

* Citation14 Kokkinidis, M.; Glykos, N. M.; Fadouloglou, V. E. (2020). Catalytic Activity Regulation through Post-Translational Modification: The Expanding Universe of Protein Diversity. Advances in Protein Chemistry and Structural Biology, 97–125.![10.1016/bs.apcsb.2020.05.001](https://pmc.ncbi.nlm.nih.gov/articles/PMC7320668/)

* Citation15 Miranda, F. F.; Thórólfsson, M.; Teigen, K.; Sanchez‐Ruiz, J. M.; Martínez, A. (2004). Structural and Stability Effects of Phosphorylation: Localized Structural Changes in Phenylalanine Hydroxylase. Protein Science, 13 (5), 1219–1226.![10.1110/ps.03595904](https://pmc.ncbi.nlm.nih.gov/articles/PMC2286772/)

* Citation16 Pincus, D.; Pandey, J. P.; Creixell, P.; Resnekov, O.; Reynolds, K. A. (2017). Evolution and engineering of Allosteric regulation in protein kinases.![10.1101/189761](https://www.researchgate.net/publication/345079397_Evolution_and_Engineering_of_Allosteric_Regulation_in_Protein_Kinases)
