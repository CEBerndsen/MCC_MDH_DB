---
editor_options: 
  markdown: 
    wrap: 72
---

# Mitochondrial Malate Dehydrogenase

# P40926

# phosphorylation of T170

## Description

# Part 1 from Project 4 report outline (with citations as appropriate)

Malate dehydrogenase, specifically mitochondrial (MDH2) is a human
enzyme encoded by the MDH2 gene. This enzyme plays a critical role in
cellular energy metabolism. MDH2 catalyzes the reversible oxidation of
malate to oxaloacetate using NAD⁺ as a cofactor, which is a key step in
the citric acid cycle (Krebs cycle) that happens in the mitochondrial
matrix. The reaction is important and essential in order to produce ATP
as it is the energy currency of the cell (1). Additionally, MDH2 is
found to be involved in the malate-aspartate shuttle (MAS) that is a
redox shuttle. MAS transfers reduction equivalents including NADH across
the inner mitochondrial membrane. Also, regenerating NAD⁺ from NADH in
the cytoplasm, linking cytosolic and mitochondrial metabolism (2). The
enzyme, mitochondrial malate dehydrogenase consists of 338 amino acids
and is considered part of the LDH (Lactate Dehydrogenase) and MDH
(Malate Dehydrogenase) superfamily. LDH and MDH do act on different
substrates where LDH facilitates the conversion between pyruvate and
lactate, and regenerating NAD⁺ from NADH (3). However, they are
structurally similar with operating comparable redox reactions with both
using NAD⁺/NADH as a cofactor. With this superfamily it highlights how
evolution has modified a basic enzyme structure so the enzyme can
perform different specific functions and biological roles in the body.
In addition, with looking at the biology of malate dehydrogenase in
humans, there have been mutations in the MDH2 gene that have been
correlated with various diseases (1). For example, certain metabolic
disorders and cancers including epileptic encephalopathy that can result
from genetic metabolic defects (4). 1. image of the unmodified site
![The site in mDH2 without to modification taken
place](images/weak_interactions_unmodified.png)

2.  image of modification site ![The site in mdh2 with the modification
    occurred](images/weak_interactions_PTM_modified.png)

## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report

1.  Image of aligned PDB files (no solvent) ![The alignment of the
    unmodified, mimic variant, and PTM modified
    models.](images/alignment_unmodified_variant_and_PTM_modified.png)

2.  Image of the site with the aligned PDB files (no solvent) ![The
    modification site aligned with the unmodified, variant, and PTM
    modified models.](images/modification_site.png)

3.  Annotated RMSF plot showing differences between the simulations
    ![The RMSF plot of the unmodified
    model](images/RMSF_plot_unmodified.png) ![The RMSF plot of the
    variant model](images/RMSF_plot_variant.png) The RMSF plots of the
    variant and unmodified are correlating peaks in the same amino acid
    sections. These peaks are amino acids or protein sections where
    there is a significant amount of motion compared to the drops. Based
    off the plots, amino acid 176 which is active is in an area of a dip
    indicating less motion. Whereas more motion is seen at the highest
    peaks of amino acids 220 and 314. Areas of importance which I would
    consider the substrate-binding sites and active sites were not found
    in peaks of the RMSF plot, but rather the drops and the beginning of
    the incline of a peak. The peaks for the unmodified and the variant
    models line up relatively with location, but intensity and height do
    change.. Similar to looking at the chart of RMSF values, the
    unmodified model has high values of RMSF. Then with the variant
    model, it had lower values of RMSF. The plot was able to show the
    changes with more visibility with peak heights and the actual RMSF
    values. Thus, relating how the structure has become rigid with the
    variant model than with the original unmodified model.

4.  Annotated plots of pKa for the key amino acids ![The pKA comparisons
    at key amino acids of substrate-binding sites and active
    sites.](images/pka_comparison.png) Another analysis is looking at
    the pKa values of the dynamic regions like residues 217-220,
    193-195, and 314 from the RMSF plot and values. The residue 193 does
    have a high pKa fluctuation, which could further support their
    structural flexibility. However, residues 192-195 and 314, only have
    a small fluctuation that doesn’t support the structural flexibility
    strongly.

5.  If needed, show ligand bound images and how modification affects
    substrate binding

Description of the data and changes

## Comparison of the mimic and the authentic PTM

Part 4 from the Project 4 report outline include images as needed ![The
mimic variant and PTM modified models superposed together in
mol\*.](images/AF3_superpose_variant_and_PTM_modified.png)

The comparison of the two models do not match completely as mimic
variant model structure came out as a monomer, while the PTM modified
protein came out as a dimer like it should. Data given from AlphaFold3
included a pTM score of 0.95 indicating an overall confidence in the
structure that it is a highly accurate predicted fold. Also, an ipTM
score of 0.95 that measured confidence in the interface interactions to
be very high in confidence and highly reliable. Structural differences
between the variant and modified models would include that the Boltz-1
only gave me chain A, while with the PTM modified model I was given both
chain A and B. From this chain B of the PTM modified model (purple) and
the variant structure (blue) were able to be superposed together. This
could be a difference that affects the structure and function of MDH2,
especially because mitochondrial malate dehydrogenase is known as a
dimer. MDH2 being a dimer allows the protein to be stabilized and helps
with the functional conformation as each monomer interacts at an
established dimer interface. Only having one chain or a monomer can
easily misrepresent the structure, there can be unstable interface
residues, and there could be missing functional interactions without the
dimer. When comparing the mimic variant model to the PTM modified
protein model the RMSD was 1.55. The RMSD correlates to the root mean
square deviation of atomic positions. Essentially, to measure how
similar or not the molecular structures are, so we can look at structure
changes. The RMSD of 1.55 in general means that the structures are
relatively similar to one another which correlates to what mol\* looked
like. Additionally, lines up with the previous talk about how the mimic
variant was a monomer and the PTM modified model was a dimer. Overall,
the PTM modified model should be used as the mimic given the structural
similarity and indication it is a dimer like it should be.

## Lena Garst

Contributors names

## Deposited May 12th

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

-   Broeks, M. H.; Meijer, N. W. F.; Westland, D.; Bosma, M.; Gerrits,
    J.; German, H. M.; Ciapaite, J.; Van Karnebeek, C. D. M.;
    Wanders, R. J. A.; Zwartkruis, F. J. T.; Verhoeven-Duif, N. M.;
    Jans, J. J. M. The Malate-Aspartate Shuttle Is Important for de Novo
    Serine Biosynthesis. Cell Reports 2023, 42 (9), 113043.
    <https://doi.org/10.1016/j.celrep.2023.113043>.
    ![113043](10.1016/j.celrep.2023.113043)

-   Uniprot. UniProt. <https://www.uniprot.org/uniprotkb/P00338/entry>
    (accessed 2025-05-07).

-   Uniprot. UniProt. <https://www.uniprot.org/uniprotkb/P40926/entry>
    (accessed 2025-05-07).

-   Yu, J. Y.; Pearl, P. L. Metabolic Causes of Epileptic
    Encephalopathy. Epilepsy Research and Treatment 2013, 2013, 1–20.
    <https://doi.org/10.1155/2013/124934>. ![124934
    (10.1155/2013/124934)
