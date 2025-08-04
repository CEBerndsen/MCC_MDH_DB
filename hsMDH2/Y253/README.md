---
editor_options: 
  markdown: 
    wrap: 72
---

# Human MDH II

# Uniprot ID: P40926

# Variation: phosphorylation of y 253

## Description

# This project examines a previously uncharacterized post-translational modification (PTM) site in human mitochondrial malate dehydrogenase 2 (MDH2), an essential multimeric enzyme involved in cellular metabolism across all domains of life. MDH catalyzes the interconversion of oxaloacetate and malate, coupled to NAD(H)/NADP(H) redox reactions (Berndsen & Bell, 2024), and is a promising drug target for metabolic, neurological, and infectious diseases (Fermaintt & Wacker, 2024).

Focusing on residue 253 in the processed MDH2 sequence, this study
investigates two modifications: phosphorylation of the native tyrosine
(Y253) and substitution with aspartic acid (D253) as a phosphomimetic.
While a Y→F variant at this site is considered likely benign, the
tyrosine’s hydroxyl group suggests potential regulatory function through
phosphorylation. The residue’s proximity to the NAD⁺ binding site and a
substrate-access loop points to a possible role in cofactor interaction
and catalytic activity.

Structural modeling and molecular dynamics simulations show that both
modifications disrupt local interactions, potentially affecting the
conformational flexibility required for enzymatic efficiency and
inter-subunit communication.

1.  image of the unmodified site ![image of the unmodified
    site](images/unmodified_interactions.png)

2.  image of modification site ![image of the modified
    site](images/modified_interactions.png)

3.  Image of mimic site ![image of the mimic
    site](images/mimic_interactions.png)

## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report

1.  Image of aligned PDB files (no solvent) ![image of aligned PDB
    files](images/align.png)

2.  Image of the site with the aligned PDB files (no solvent) ![image of
    the site with the aligned PBD files](images/align_up_close.png)

3.  Annotated RMSF plot showing differences between the simulations
    ![annotated RMSF plot showing differences between the
    simulations](images/rmsf_plot.png)

4.  Annotated plots of pKa for the key amino acids ![annotated plots of
    pea for the key amino acids](images/pka_his176.png)

Description of the data and changes Structural and simulation analyses
suggest that a phosphomimetic substitution at residue 253 in MDH2
induces subtle local changes without disrupting global structure.
AlphaFold3 predictions showed minor domain rearrangements in the mimic
variant, while Boltz-1 scores indicated preserved structural integrity.
Molecular dynamics revealed reduced flexibility near the mutation site
and a slight shift in the pKa of catalytic residue His176, potentially
affecting malate oxidation. Overall, the mimic maintains stability but
may alter enzymatic efficiency through localized conformational changes.

## Comparison of the mimic and the authentic PTM

The mimic and modified models of MDH II show similar overall folds but
differ in key interaction patterns, indicating that the mimic is only a
partial approximation of the post-translational modification (PTM).
While both maintain high structural confidence, slight differences—such
as the mimic’s lower iPTM score—suggest reduced inter-subunit
coordination. Unlike the modified structure, which preserves naïve
hydrogen bonding at residue 229, the mimic alters this network by
forming a new bond with Asn 22. These changes may subtly disrupt active
site dynamics. Molecular dynamics simulations further highlight
differences: the mimic shows lower flexibility near residue 229 and a
slight shift in the pKa of His 176, which could impact proton
abstraction during catalysis. Although Boltz-1 modeling finds no major
structural disruption. Overall, the mimic retains core structure but
does not fully replicate the PTM’s interactions or dynamic behavior,
making it a functionally inadequate mimic for functional studies.

### Colab notebook links

Provide file names of completed colab notebooks

## Authors

Eeva Nurminen

## Deposition Date

05/07/2025

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

-   AlphaFold Server. (2025.). About AlphaFold Server. Retrieved
    February 18, 2025, from <https://alphafoldserver.com/about>

-   Berndsen, C. E., & Bell, J. K. (2024). The structural biology and
    dynamics of malate dehydrogenases. Essays in biochemistry, 68(2),
    57–72. <https://doi.org/10.1042/EBC20230082>.

-   Fermaintt, C. S. and Wacker, S. A. (2024). Malate Dehydrogenase as a
    multi-purpose target for drug discovery. Essays in biochemistry,
    68(2), 1-14. <https://doi.org/10.1042/EBC20230081>

-   Gharaie Amirabadi, D. (2024, December 13). Interpreting Boltz-1
    (AlphaFold3) Metrics and Visualizations on Neurosnap. Neurosnap.ai.
    <https://neurosnap.ai/blog/post/interpreting-boltz-1-alphafold3-metrics-and-visualizations-on-neurosnap/675b7b92375d5ec1fde492ef>

-   Uniprot. UniProt.
    <https://www.uniprot.org/uniprotkb/P40926/entry#sequences> (accessed
    2025-04-28)
