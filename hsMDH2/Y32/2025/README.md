---
editor_options: 
  markdown: 
    wrap: 72
---

# Human MDH2

# Uniprot ID: P40926

# Variation: Phosphorylation of Y56 (pY32 in structure)

## Description

Human mitochondrial malate dehydrogenase (MDH2) is a homodimeric enzyme
that catalyzes the conversion of malate to oxaloacetate in the citric
acid cycle.<sup>3</sup> The active site contains a histidine (His176 in
the processed sequence) that acts as a proton acceptor.<sup>1</sup>
Tyrosine 56 (Tyr56) of MDH2 was examined as a site for a
post-translational modification. The effects of phosphorylation of Tyr56
(Tyr32 in the processed sequence) were examined. Tyr56 is part of a
beta-pleated sheet relatively close to the dimer interface but
relatively far from the active site (His 176). A pathogenic variant has
been recorded which causes a stop codon at Leu55 and Tyr56, showing the
importance of this region for MDH2 function.<sup>2</sup> No prior
literature exists analyzing the phosphorylation or post-translational
modification of Tyr56.

Structure of MDH2 with Tyr32 (purple) and the active site (pink) labeled
![Structure of MDH2, showing Tyr32 and its distance from the active
site](images/mdh2_structure.png)

Aligned structures of MDH2, the unmodified, modified, AlphaFold3 mimic,
and Boltz-1 mimic models ![Aligned models of MDH2](images/align.png)

## Effect of the sequence variant and PTM on MDH dynamics

Alignment of unmodified (green) and modified (purple) models at the
active site (His176) ![His 176 interacts with Asp 149, the His 176 of
the modified model also interacts with Arg
86](images/modified_align_activesite.png)

The amino acids with which His 176 forms weak interactions are labeled.

Alignment of unmodified (green) and mimic (purple) models at the active
site (His176) ![The His 176 of both models align well and form a weak
interaction with Asp149](images/mimic_align_activesite.png)

At the active site, the structure of MDH2 is overall very similar. There
is an additional cation-pi interaction in the modified model between
His176 and Arg86 which has been predicted previously in models of MDH2
bound to its ligands. Structurally, the phosphorylation of Tyr32 does
not appear to create any major changes that would greatly impact the
function of MDH2.

RMSF plot of the unmodified model of MDH2 ![RMSF plot of unmodified
MDH2, RMSF is from 1.0 to 3.5](images/rmsf_plot_unmodified.png)

The solid vertical line indicates the division between the two subunits
of MDH2. The active site, amino acid 176 is labeled with the vertical
dashed line.

RMSF plot for the mimic model of MDH2 ![RMSF plot of MDH2 mimic, RMSF
spans from 0.5 to 2.5](images/rmsf_plot_mimic.png)

The RMSF plots show higher flexibility in the unmodified protein
compared to the mimic. There is less flexibility at the active site of
the mimic model of MDH2 as RMSF peaks around 1.0 at amino acid 176 for
the mimic model, compared to the unmodified model which has a wide peak
between 2.0 and 2.5. The decreased flexibility at the active site may
affect the enzyme's ability to change conformation in binding substrates
or performing its chemistry.

Plot of pKa for amino acid 176, histidine for the unmodified MDH2 ![The
pKa of His 176 is mostly around 4.5 to
5.0](images/pka_his176_unmodified.png)

Plot of pKa for amino acid 176, histidine for the mimic MDH2 ![The pKa
of His 176 is around 5 at the lowest with many wide peaks up to
7.0](images/pka_his176_mimic.png)

The His176 of the unmodified model is generally at a pKa between 4.5 and
5, meaning that it remains deprotonated for most of the time. The mimic
model's pKa trends are around 5 at the lowest, with many more wider
peaks that reach a pKa of 7. The increased pKa of His176 of the mimic
model suggests that the histidine is more likely to stay protonated
which may make it less effective performing its role in catalysis of
accepting protons.

## Comparison of the mimic and the authentic PTM

The alignment of the modified (green) model of MDH2 with the AlphaFold3
mimic (blue) at the active site of His176. ![His 176 forms a weak
interaction with Asp 149, only the modified model's His 176 interacts
with Arg 86](images/mimic_modified_align.png)

At the active site, the His176 of the modified and mimic models aligns
well and both form a weak interaction with Asp149. The His176 of the
modified model forms a cation-pi interaction with Arg86 that is not
present in the mimic model. Overall, the mimic structure is generally
accurate in modeling the impact of the modification on the general
structure and weak interactions of MDH2 but it is not completely the
same.

## Authors

Liana Torlucci

## Deposition Date

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

1.  De Lorenzo, L., Stack, T. M. M., Fox, K. M., & Walstrom, K. M.
    (2024). Catalytic mechanism and kinetics of malate dehydrogenase.
    Essays in biochemistry, 68(2), 73–82.
    <https://doi.org/10.1042/EBC20230086>

2.  National Center for Biotechnology Information (NCBI). ClinVar;
    Variant RCV002039166.
    <https://www.ncbi.nlm.nih.gov/clinvar/RCV002039166/> (accessed Apr
    2025).

3.  *UniProt.* UniProt. <https://www.uniprot.org/uniprotkb/P40926>
    (accessed 2025-05-02).
