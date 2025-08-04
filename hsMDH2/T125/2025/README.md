---
editor_options: 
  markdown: 
    wrap: 72
---

# Malate Dehydrogenase MDH2

# Uniprot ID: P40926

# Variation: Phosphorylation of T125

## Description

# After reviewing available literature and databases, phosphorylation is a common regulatory post-translation modification (PTM) that can significantly impact a protein’s function. Phosphorylation of threonine 125 (T125) in human mitochondrial malate dehydrogenase has not been directly researched in current literature or UniProt annotations. However, there have been studies done that suggest that phosphate ions can bind within the binding site of MDH2, which would force conformational changes and affect the overall structure and function of MDH2.4

1.  image of the unmodified site ![Due to previous sequence processing,
    T125 corresponded to T101 in the wild type structure which was used
    in Project 2. When looking at T101 in the unmodified protein, it
    interacts with ALA 98 and VAL 97 by hydrogen
    bonds.](images/unmodified_site.png)

2.  image of modification site ![When looking at the modification site
    of the PTM model, the phosphorylated amino acid 125, labeled TPO
    125, interacts with THR 151 and ILE 150 by hydrogen
    bonds.](images/ptm_model_site.png)

3.  image of mimic site ![When looking at the mimic site of the sequence
    variant model, the ASP 125 amino acid interacts with THR 151 by
    hydrogen bonds.](images/mimic_variant_site.png)

## Effect of the sequence variant and PTM on MDH dynamics

1.  Image of aligned PDB files (no solvent) ![Using AlphaFold3, three
    structural models of MDH2 were generated and analyzed: Wild Type,
    PTM Mimic Variant, and Phosphorylated Form. All three models were
    aligned via their A chains (since MDH2 is a dimer) using Mol\*. At a
    larger viewpoint, the structures appeared similar; however,
    significant differences emerged upon closer inspection of the
    modification site.] (images/superimpose_large_scale.png)

2.  Image of the site with the aligned PDB files (no solvent) ![When
    zooming in on the modification site, the similarities and
    differences in weak interactions and structures emerged. All three
    models contained the similar PHE amino acid (131 & 155), along with
    similar loops and helixes. However, the phosphorylated form (TPO
    125), had a bulkier and outward orientation. This orientation pushes
    nearby side chains, causing conformational shifts in neighboring
    loops and helices interacting with THR 151 and ILE 150. This would
    trigger a longer range of interactions that alter the local
    electrostatic environment and structural dynamics that are absent
    from the unmodified model.] (images/superimpose_structures.png)

3.  Annotated RMSF plot showing differences between the simulations
    ![The RMSF (Root Mean Square Fluctuation) plot shows per-residue
    flexibility over the simulation. The x-axis represents the residue
    index (1-700), the y-axis shows the average fluctuation of each
    residue’s alpha carbon over the simulation. The peaks are the high
    RMSF values which indicate greater flexibility or movement, usually
    in loops or unstructured regions. The valleys or troughs are the low
    RMSF values which indicate stable, less mobile regions, often
    helices or sheets.7 The mutation of T125 to D125 introduces a
    negative charge and charges local interactions near the original
    threonine site. Residue 125 exhibited a drop in RMSF, indicating
    reduced flexibility at the modification site. This rigidity likely
    is caused by the new weak interactions that “lock” the side chain in
    place. This rigidity could disrupt the loop dynamics that are
    essential for substrate binding and substrate
    turnover.](images/rmsf_plot.png)

4.  Annotated plots of pKa for the key amino acids ![The graph below
    represents the predicted pKa values of aspartic (D) within the MDH2
    sequence over time or simulation steps. Aspartic (D) normally has
    pKa around 3.9, meaning it's typically deprotonated (negatively
    charged) at pH 7.4. However, in this protein environment, its pKa
    shifts significantly depending on surround residues and
    conformational changes. The pKa fluctuates based on changes in the
    residue's local environment within the protein structure (y-axis:
    pKa from 6.8 to 7.8). In the initial phase (0-20): the amino acid
    starts with a stable predicted pKa around 7.4, which suggests a
    relatively neutral or protonated state. In the middle phase (20-60):
    the pKa fluctuates between 7.0 to 7.5, which indicates that the
    surrounding environment is shifting. Potentially due to protein
    dynamic or nearby residue movements. In the transition phase (around
    70): a sharp spike to 7.8 occurs, which could suggest the amino
    acid's environment suddenly becomes less favorable to deprotonation.
    This could also be due to nearby conformational changes. In the drop
    phase (around 80): the pKa then drops significantly below 6.8, which
    suggests a drastic change in the environment. This could potentially
    be due to increased proximity to negative charges, which makes the
    amin acid more likely to deprotonate. Overall, these pKa shifts
    suggest that the variant enzyme exists in a dynamic environment,
    causing the chemical behavior of aspartic acid (D) particularly its
    protonation state to be sensitive to structural or environmental
    changes within the protein. This dynamic behavior implies that
    aspartic acid's charge state may fluctuate during the simulation.
    Such changes are critical for the function of MDH2, which relies on
    precise binding interactions and structural stability. In this
    context, pKa shifts can regulate key aspects of the enzyme's
    function, including catalytic activity, binding affinity, and
    overall protein stability.](images/trajectory_amino_acid.png)

## Comparison of the mimic and the authentic PTM

![To investigate the structural effects of phosphorylation at threonine
125 (T125) in the mitochondrial malate dehydrogenase (MDH2), I compared
a phosphorylation mimic and the authentic post-translational
modification (PTM). The mimic was generated by mutating T125 to
aspartate (D125) in the protein sequence, which is a common substitution
used to simulate the negative charge induced by phosphorylation. In
contrast, the authentic PTM structure was modeled using the Alpha Fold
server, and a phosphate group was manually added to T125, converting it
to phosphothreonine (TPO125). Both the mimic and the authentic PTM
appeared nearly identical when viewed at the whole-protein level.
However, detailed analysis of the local environment surrounding residue
125 revealed key differences. In the mimic model, ASP125 engaged in
hydrogen bonding with THR151. This interaction was not observed in the
authentic phosphorylated form. Instead, TPO125 formed hydrogen bonds
with different neighboring residues, suggesting that the phosphate group
alters the local electrostatic and hydrogen bonding environment in a
manner that cannot be fully replicated by an aspartate substitution.
This comparison supports the idea that wile aspartate mimics are useful
approximations of phosphorylation, they may not fully capture the
precise biochemical or structural consequences of the authentic PTM.]

## Authors

Mateo Moore

## Deposition date

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

-   Peterson, C. N.; Cornely, K.; Parente, A. D.; Springer, A. L.;
    Provost, J. J. Uncovering Malate Dehydrogenase: Structure, Function
    and Role in Disease. Essays Biochem. 2024, 68 (2),
    53–55.![DOI](https://doi.org/10.1042/ebc20240044)

-   Wang, R.; Hao, J.; Cao, C.; Li, J.; Zhang, X. Molecular
    Characteristics of the Malate Dehydrogenase (MDH) Gene Family in
    Spirometra mansoni (Cestoda: Diphyllobothriidea). Int. J. Mol. Sci.
    2024, 25 (16),
    8802.![DOI](https://www.mdpi.com/1422-0067/25/16/8802)

-   Leverett, B.; Austin, S.; Tan-Arroyo, J. Malate Dehydrogenase (MDH)
    in Cancer: A Promiscuous Enzyme, a Redox Regulator, and a Metabolic
    Co-conspirator. Essays Biochem. 2024, 68 (2),
    135–146.![DOI](https://doi.org/10.1042/EBC20230088.)

-   Eo, Y.; Duong, M. T. H.; Ahn, H. C. Structural Comparison of hMDH2
    Complexed with Natural Substrates and Cofactors: The Importance of
    Phosphate Binding for Active Conformation and Catalysis.
    Biomolecules 2022, 12 (9),
    1175.![DOI](https://doi.org/10.3390/biom12091175.)

-   AlphaFold Server.![DOI](https://alphafoldserver.com)

-   Mol\* Viewer.![DOI](https://molstar.org/viewer)

-   RMSD/RMSF
    Analysis.![DOI](https://ctlee.github.io/BioChemCoRe-2018/rmsd-rmsf)

-   Ait-El-Mkadem, S.; Dayem-Quere, M.; Gusic, M.; et al. Mutations in
    MDH2, Encoding a Krebs Cycle Enzyme, Cause Early-Onset Severe
    Encephalopathy. Am. J. Hum. Genet. 2017, 100 (1),
    151–159.![DOI](https://doi.org/10.1016/j.ajhg.2016.11.014.)
