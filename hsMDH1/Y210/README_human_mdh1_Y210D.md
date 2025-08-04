---
editor_options: 
  markdown: 
    wrap: 72
---

# Human MDH1

# UniProt ID: P40925

# Variation: Phosphorylation of Y210 (D209 in structure)

## Description

A modification was made at position 209 of the processed sequence of
human malate dehydrogenase (MDH1), which corresponds to position 210 in
the unprocessed sequence found in UniProt. A modification at this site
has never been previously researched or described according to the
literature and databases. The residue at position 209 is located within
an alpha helix, a common secondary structure that often adds to the
stability and functional shape of the protein. The site of
phosphorylation in the mimic model is not positioned close to the dimer
interface, suggesting that it would not have an effect on substrate
binding or have any inhibition effects.

1.  Image of the unmodified site ![Mol\* observation of the unmodified
    site in MDH1, highlighted in pink is TYR
    209.](images/unmodified_site.png)

2.  Image of modification site ![Mol\* observation of the modification
    site in MDH1, highlighted in pink is residue 209 after
    phosphorylation.](images/modified_site.png)

## Effect of the sequence variant and PTM on MDH dynamics

RMSF is a measure of the flexibility or mobility of each residue. When
comparing the two plots visually, both the unmodified and mimic proteins
have similar fluctuation patterns, with peaks occurring at approximately
the same residue positions. The most noticeable difference is at residue
100, where the mimic only reaches roughly 1.5 Å, whereas the original
protein reaches a high of 2.25 Å. To better understand this difference,
the relative locations of the residues were visualized using Mol\*.

1.  Image of aligned PDB files ![Mol\* observation of aligned unmodified
    and mimic in MDH1. The RMSD value found is
    0.34.](images/aligned_original_mimic.png)

2.  Image of the site with the aligned PDB files ![Mol\* observation of
    TYR 209 in green and phosphorylated 209 highlighted in
    pink.](images/aligned_modsite.png)

3.  RMSF plots showing differences between the simulations ![RMSF plot
    showing peaks of the unmodified residues. Plot was generated from
    Colab 2.](images/unmodified_RMSF.png) ![RMSF plot showing peaks of
    the mimic residues. Plot was generated from Colab
    2.](images/mimic_RMSF.png)

4.  pKa box plots for the key residues in the unmodified and mimic ![pKa
    box plot of unmodified active site residues HIS 186, ASP 158, and
    ARG 161. Box plot was generated from Colab
    2.](images/pKa_unmodified.png) ![pKa box plot of mimic active site
    residues HIS 186, ASP 158, ARG 161. Box plot was generated from
    Colab 2.](images/pKa_mimic.png)

## Comparison of the mimic and the authentic PTM

While much of the data gathered has decent findings to conclude that the
mimic model mostly resembles the structural effects of phosphorylation
at position 209, it does not fully explain the functional differences
caused by the post-translational modification. The substitution of
tyrosine to aspartic acid creates a negative charge that mimics what the
phosphorylated state would be like. However, the negative charge on the
added phosphate group in the modified model introduces slight changes in
the residue orientation and weak interactions that are not shown by ASP
209 in the mimic. This could be due to the fact that PTR 209 is bulkier
and has a greater capability to participate in electrostatic
interactions. Also, while the phosphate group in the modified model
causes TYR 209 to rotate away from its nearby hydrophobic pocket, ASP
209 in the mimic forms a hydrogen bond with GLU 210. Though these
differences are minor when looking at the protein as a whole, they could
have influence on behavior dynamics and metabolic pathways in the
modified protein that are not represented in the mimic model. Therefore,
while the mimic is a useful representation when comparing structural
differences, it may not be the most accurate to describe the modified
protein. This is because it cannot account for all the functional
impacts of phosphorylation and its role in MDH1 metabolism.

## Authors

Lauren T. Levine

## 05/07/2025

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

-   MDHC_HUMAN. UniProt. <https://www.uniprot.org/uniprotkb/P40925>
    (accessed 2025-04-08).

-   Sehnal, D.; Bittrich, S.; Deshpande, M.; Svobodová Vařeková, R.;
    Berka, K.; Bazgier, V.; Velankar, S.; Burley, S. K.; Koča, J.;
    Rose, A. S. Mol\* Viewer: Modern Web App for 3D Visualization and
    Analysis of Large Biomolecular Structures. Nucleic Acids Res. 2021,
    49 (W1), W431–W437. <DOI:10.1093/nar/gkab314>

-   Kayll, A.; Sardelli, A.; Berndsen, C. Protein Structure Analysis
    Colab Notebook, Version 2; James Madison University: Harrisonburg,
    VA, 2025.
