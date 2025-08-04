---
editor_options: 
  markdown: 
    wrap: 72
---

#Malate Dehydrogenase Human 1 \# UniProt ID P40925 \# p71D

## Description

# Malate dehydrogenase (MDH) is a key oxidoreductase enzyme that catalyzes the reversible conversion of malate to oxaloacetate using NAD⁺ as a cofactor, producing NADH in the process. This reaction plays a central role in the citric acid cycle and the malate-aspartate shuttle, which are vital for energy metabolism and redox balance.1,2

In humans, two major isoforms exist: MDH1, located in the cytosol, and
MDH2, located in the mitochondria. MDH1 functions specifically within
the malate-aspartate shuttle, where it facilities the transfer of
cytosolic NADH reducing equivalents into the mitochondria. In contrast,
MDH2 operates within the mitochondrial matrix and is directly involved
in the citric acid cycle.1 The project focuses solely on MDH1.

MDH1 is important in supporting glucogenesis and redox homeostasis in
hepatocytes and other metabolically active tissues. It is subject to
regulation via substrate availability and post-translational
modifications (PTMs), such as phosphorylation and acetylation, which
modulate its structure and function. Altered MDH1 activity has been
associated with metabolic dysfunction and cancer due to its impact on
NAD/NADH.1,2

1.  image of the unmodified site ![The unmodified model shows Thr71 with
    a small, outward-facing hydroxyl group forming limited interactions,
    allowing natural flexibility in the surrounding loop
    region.](images/unmod_site.png)

2.  image of modification site ![The phosphorylated threonine (TPO70)
    forms multiple hydrogen bonds with nearby residues, anchoring the
    loop and β-sheet region. The bulky phosphate group introduces
    negative charge and stabilizes the local structure through an
    extensive interaction network.](images/mod_site.png)

## Effect of the sequence variant and PTM on MDH dynamics

The phosphorylation of T71 in MDH1 introduces a bulky, negatively
charged phosphate group that forms multiple hydrogen bonds with nearby
residues (Lys72, Asp41, Thr43, and TPO70), significantly increasing
local rigidity around the substrate access channel. This rigidity likely
restricts loop mobility and subtly influences the geometry of the
substrate-binding region, potentially affecting enzyme efficiency.

In contrast, the T71D mimic, which substitutes threonine with aspartate,
replicates the negative charge but fails to establish the same extent of
hydrogen bonding due to its shorter side chain. Molecular dynamics
simulations revealed that while the mimic modestly stabilizes the local
structure at residue 71, it causes increased flexibility in distant
regions, particularly near the active site (e.g., residue 186). This is
evidenced by broader RMSF distributions and lower pKa values in the
mimic model, indicating a more dynamic and acidic environment that could
affect substrate or cofactor interactions.

Overall, while T71D captures some electrostatic properties of
phosphorylation, it does not fully replicate the stabilizing structural
and dynamic effects. This supports the conclusion that T71D is a limited
functional mimic and may not reliably substitute for true PTMs in
experimental or computational studies.

Part 3 from the Project 4 report

1.  Image of aligned PDB files (no solvent) ![This structure shows a
    superimposition of two MDH1 models, likely the unmodified (gold) and
    phosphorylated or mimic variant (magenta). The overall alignment is
    strong, indicating minimal global structural deviation. However,
    small local differences—particularly in loop regions—may reflect the
    structural effects of the modification at residue
    71.](images/Md_align.png)

2.  Image of the site with the aligned PDB files (no solvent)
    ![Alignment of the T71 region in the unmodified (gold) and mimic
    (magenta) MDH1 models. The T71D residue (magenta) forms more
    hydrogen bonds (blue dashed lines) than the native threonine (gold),
    but the orientation and bonding geometry differ. These differences
    suggest increased rigidity in the mimic, though not fully
    replicating the conformational impact of a phosphate group,
    indicating a partial mimicry of the true phosphorylation
    state.](images/md71_align_site.png)

3.  Annotated RMSF plot showing differences between the simulations
    ![The RMSF plots compare residue-level flexibility between the
    unmodified MDH1 (left) and the T71D mimic (right). The T71D model
    shows slightly reduced fluctuation around residue 71 and surrounding
    regions, indicating modest local rigidity. However, broader
    flexibility patterns remain similar, suggesting limited global
    structural impact from the T71D
    substitution.](images/RMSF_compare.png)

4.  Annotated plots of pKa for the key amino acids ![This figure
    compares the root mean square deviation (RMSD) over time between the
    unmodified MDH1 (left) and the T71D mimic (right). Both structures
    exhibit early stabilization, but the T71D variant shows slightly
    higher fluctuations later in the trajectory. This suggests that the
    mimic may induce minor global destabilization, though the overall
    structural drift remains within a typical range for MD
    simulations.](images/pKa_over_traj.png)

![This figure compares predicted pKa values of His186 in the unmodified
MDH1 model (left) and the T71D mimic (right). The unmodified model shows
a narrower range and higher median pKa, indicating a more stable, basic
environment. In contrast, the T71D variant shows a broader distribution
and lower median, suggesting increased local variability and a more
dynamic microenvironment near the active site, likely influenced by
structural changes from the T71
substitution.](images/his186_pKa_compare.png)

5.  If needed, show ligand bound images and how modification affects
    substrate binding

The data collected in this project revealed clear structural and dynamic
differences between the unmodified MDH1, the phosphorylated model
(TPO71), and the T71D mimic. Structurally, phosphorylation at T71
introduced a bulky, negatively charged phosphate group that formed
multiple stabilizing hydrogen bonds with nearby residues such as Lys72,
Asp41, Thr43, and TPO70. This created a rigid local environment near the
substrate access channel, suggesting restricted loop mobility and
potential influence on substrate or cofactor access. In contrast, the
unmodified model showed minimal hydrogen bonding at T71, preserving
natural flexibility in the local loop structure. The T71D mimic
introduced a negative charge via an aspartate substitution, but the
shorter side chain failed to form the same extensive hydrogen bonding
network. As a result, the mimic retained greater flexibility at T71 and
did not reproduce the rigidifying effect seen with phosphorylation.

Molecular dynamics data further supported these findings. RMSD analysis
indicated that the T71D variant had higher conformational drift compared
to the unmodified model, reflecting decreased structural stability. RMSF
plots showed slightly reduced flexibility near residue 71 in the mimic,
but increased fluctuation in distant regions, particularly around
residue 186, near the active site. Additionally, pKa predictions at
His186 revealed a significant shift: the unmodified model displayed a
narrow, high median pKa (\~7.7), indicating a stable, basic environment,
while the mimic exhibited a broader, lower distribution (\~5.2),
reflecting a more acidic and dynamic microenvironment. These
observations suggest that while the T71D mimic partially simulates the
negative charge of phosphorylation, it does not fully replicate the
structural stabilization or the long-range functional consequences of
the PTM.

## Comparison of the mimic and the authentic PTM

The T71D mimic and the authentic phosphorylated T71 (PTM) differ notably
in their structural and dynamic effects on MDH1. While both introduce a
negative charge at residue 71, the PTM forms an extensive hydrogen
bonding network that increases local rigidity near the substrate access
channel. In contrast, the T71D mimic forms fewer and weaker interactions
due to geometric differences, resulting in greater flexibility.
Molecular dynamics data support these findings, showing that the mimic
causes more structural drift and altered electrostatics at the active
site compared to the PTM. Overall, the T71D variant does not fully
replicate the stabilizing effects of phosphorylation and is a limited
functional mimic.

Part 4 from the Project 4 report outline include images as needed

This project investigated the structural and functional consequences of
a post-translational modification (phosphorylation) at threonine 71 in
human cytosolic malate dehydrogenase (MDH1) and evaluated the
suitability of the T71D substitution as a phosphomimetic. Computational
modeling and molecular dynamics simulations revealed that
phosphorylation at T71 introduces a highly stabilizing network of
hydrogen bonds that increases local rigidity near the substrate access
channel. In contrast, the T71D mimic, while replicating the negative
charge, fails to fully reproduce the geometric and interactive profile
of the phosphorylated residue. It forms fewer and weaker hydrogen bonds
and allows for greater flexibility, particularly at distal sites,
including the active site region.

These findings suggest that T71D is an imperfect mimic of T71
phosphorylation, and relying on it as a functional stand-in may lead to
misinterpretation in experimental studies. This has broader implications
for biochemical research, particularly when selecting mutation
strategies to model PTMs. Furthermore, since MDH1 plays a central role
in redox balance and metabolic flux through the malate-aspartate
shuttle, even minor structural perturbations at non-catalytic sites like
T71 could influence cellular energy homeostasis and disease phenotypes.
Continued integration of structure-based modeling with functional assays
will be critical in accurately characterizing the effects of PTMs on
enzyme behavior.

## Authors

Rachel Murie

## Deposition Date

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

lightgrey.svg

## References

-   Citation1
    ![10.1042/EBC20230082](https://doi.org/10.1042/EBC20230082)
-   Citation2
    ![10.1042/EBC20230081](https://doi.org/10.1042/EBC20230081)
