# Homo sapiens MDH1
# P40925
# Phosphorylation of S146 (pS165 in structure)


## Description

# Malate dehydrogenase (MDH) is a key metabolic enzyme that catalyzes the reversible oxidation of malate to oxaloacetate, using NAD⁺ as a cofactor and producing NADH in the process (Ahern & Rajagopal, 2017). This reaction is essential for maintaining redox balance in cells and supporting energy-generating pathways. In humans, there are two main isoforms: mitochondrial MDH2, which is part of the tricarboxylic acid (TCA) cycle, and cytoplasmic MDH1, which plays a major role in the malate-aspartate shuttle (Minárik et al., 2002).

In this project, I studied human MDH1, focusing on the phosphorylation of Serine at position 145. There is currently no published literature describing the functional impact of phosphorylation at this site, making it an ideal candidate for structural modeling and simulation (UniProt Consortium, 2024). Ser145 is located in a loop region, away from the active site and substrate-binding pocket. Since I used the processed amino acid sequence, Ser145 corresponds to position 146p in the full-length sequence. To model the modification, I used AlphaFold3 with the number of chains set to two to reflect MDH1’s dimeric structure (Jumper et al., 2021). Using AlphaFold3’s PTM editing tool, I introduced a phosphoserine (SEP145). For the mimic variant, I followed standard phospho-mimic conventions and substituted Aspartic Acid (D) at the same position. Both modified sequences were structurally predicted using AlphaFold3 and analyzed for weak interactions, structural deviation, and dynamic behavior.

1. image of the unmodified site
![Position 145 in the unmodified model (green)](images/unmodified_site.png)

2. image of modification site
![Position 145 in the modified model (orange)](images/modified_site.png)


## Effect of the sequence variant and PTM on MDH dynamics

Structural comparisons of the unmodified, modified (SEP145), and mimic (ASP145) models revealed only minor changes, with RMSD values under 0.45 across all alignments. Both SEP145 and ASP145 preserved the enzyme’s overall folding and tertiary structure. In all models, the modified residue maintained hydrogen bonding with ASP116 and showed no disruption to surrounding regions. SEP145 was oriented outward toward the solvent, interacting primarily with surrounding water molecules rather than engaging in local structural contacts. The substitution site was distant from the active site and substrate-binding pocket, suggesting that neither phosphorylation at SER145 nor the ASP145 mimic is likely to interfere with MDH1’s enzymatic function.

1. Image of aligned PDB files (no solvent)
![Superimposed 3D structures of MDH1 aligned in Mol, showing the unmodified model (teal/orange), modified SEP145 model (green/yellow), and mimic ASP145 model (magenta/purple).](images/aligned.png)

2. Image of the site with the aligned PDB files (no solvent)
![Close-up view of residue 145 across the unmodified (green), modified SEP145 (yellow), and mimic ASP145 (magenta) MDH1 models, aligned in Mol*.](images/site_aligned.png)

Image of the mimic and modified structures at modification site.
![Superimposed image of the MDH1 mimic variant (ASP145) and the modified model (SEP145) aligned in Mol*. The image highlights their close structural alignment and the similar positioning of residue 145, both forming hydrogen bonds with ASP116.](images/mimic_vs_modified.png)

Image of the mimic and unmodified structures at modification site.
![Superimposed image of the MDH1 mimic variant (ASP145) and unmodified model (SER145), shown in Mol*. SER145 forms an additional backbone hydrogen bond with LYS121, not observed in the mimic. Both maintain a hydrogen bond with ASP116.](images/mimic_vs_unmodified.png)

Image of the modified and unmodified structures at modification site.
![Superimposed MDH1 models showing the modified SEP145 structure versus the unmodified SER145 structure. The phosphorylated SEP145 residue projects outward into solvent and does not form the additional hydrogen bond to LYS121 seen in the unmodified model.](images/modified_vs_unmodified.png)

3. Annotated RMSF plot showing differences between the simulations
![RMSF plot for variant structure](images/rmsf_mimic_plot.png)

![RMSF plot for unmodified structure](images/unmodified_rmsf_plot.png)

4. Annotated plots of pKa for the key amino acids
![pKa fluctuation plot for His186 in the ASP145 mimic model, showing moderate variability over simulation time](images/mimic_pKaplot.png)
![pKa fluctuation plot for His186 in the unmodified model, showing relatively stable protonation behavior](images/unmodified_pKaplot_HIS186.png)
![Box plot of predicted pKa values for residues ASP145, ARG161, and HIS186 across the mimic simulation.](images/145_161_186_pKaplot.png)

The dataset includes structural models of human MDH1 in three forms: unmodified (SER145), mimic variant (ASP145), and PTM (SEP145). Visual comparison of the superimposed models revealed minimal structural deviation between all variants. RMSD values were low in all pairwise comparisons, 0.39 (modified vs. mimic), 0.43 (mimic vs. unmodified), and 0.23 (modified vs. unmodified), indicating strong overall structural similarity. At the site of substitution, both the ASP145 mimic and SEP145 modification preserved hydrogen bonding to ASP116. The unmodified SER145 occasionally formed an additional backbone hydrogen bond to LYS121, but this was not observed in the modified or mimic variants and appeared structurally insignificant. The substituted residues remained solvent-exposed and distant from the active site, further supporting the prediction that the phosphorylation does not interfere with enzymatic function. RMSF plots from the mimic simulation showed slightly elevated flexibility in certain loop regions compared to the unmodified model, though key catalytic and substrate-binding regions, such as HIS186, remained stable. pKa analysis of HIS186 supported this, showing consistent protonation profiles across both unmodified and mimic models. These results could suggest that the structural and dynamic impact of phosphorylation at SER145 is minimal, and the mimic substitution (ASP145) is a reasonable stand-in for SEP145 in future studies.


## Comparison of the mimic and the authentic PTM

The structural comparison between the mimic (ASP145) and authentic PTM (SEP145) models revealed high similarity, with an RMSD of 0.39. Both substitutions maintained a hydrogen bond with ASP116 and showed nearly identical backbone positioning at residue 145. Neither model formed the additional hydrogen bond to LYS121 that was seen in the unmodified SER145 structure.
In both the mimic and modified models, the substituted residue pointed outward toward solvents and remained distant from the active site. No significant changes were observed in the surrounding loop or core structure, and overall folding was preserved. Given their structural and interaction similarity, the mimic substitution (ASP145) could be a reliable approximation of the authentic phosphoserine (SEP145) for modeling purposes. However, further experimentation would be necessary. 

![ASP145 mimic and SEP145 modified models superimposed in Mol*](images/mimic_vs_modified.png)

### Colab notebook links

mimic_colab1.ipynb

mimic_colab2.ipynb



## Authors

Kylie Rock 

## Deposition Date

05/07/2025

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References
* Ahern, K., & Rajagopal, I. (2017). Biochemistry Free for All (1st ed.). Oregon State University. https://biochem.oregonstate.edu/undergraduate/educational-resources

* Anderson, K. A., & Hirschey, M. D. (2012). Mitochondrial protein acetylation regulates metabolism. Essays in biochemistry, 52, 23–35. ![10.1042](https://doi.org/10.1042/bse0520023)

* Bagewadi, Z. K., Khan, T. M. Y., Gangadharappa, B., Kamalapurkar, A., Shamsudeen, S. M., & Yaraguppi, D. A. (2023). Molecular dynamics and simulation analysis against superoxide dismutase (SOD) target of Micrococcus luteus with secondary metabolites from Bacillus licheniformis recognized by genome mining approach. Saudi Journal of Biological Sciences, 30(9), 103753. ![10.1016](https://doi.org/10.1016/j.sjbs.2023.103753)

* Boland, M. L., Chourasia, A. H., & Macleod, K. F. (2013). Mitochondrial dysfunction in cancer. Frontiers in oncology, 3, 292. ![10.3389](https://doi.org/10.3389/fonc.2013.00292)

* Jumper, J., Evans, R., Pritzel, A. et al. Highly accurate protein structure prediction with AlphaFold. Nature 596, 583–589 (2021). ![10.1038](https://doi.org/10.1038/s41586-021-03819-2)

* Minárik, P., Tomásková, N., Kollárová, M., & Antalík, M. (2002). Malate dehydrogenases--structure and function. General physiology and biophysics, 21(3), 257–265.

* UniProt Consortium. (2024). MDH1 - Malate dehydrogenase, cytoplasmic - Homo sapiens (Human) [UniProt Knowledgebase entry P40925]. UniProt. https://www.uniprot.org/uniprotkb/P40925/entry
