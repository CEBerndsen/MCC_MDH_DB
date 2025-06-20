---
editor_options: 
  markdown: 
    wrap: 72
---

# Human MDH1

# Uniprot number P40925

# Variation Phosphorylation of S19 (pS19 in structure)

## Description

Malate dehydrogenase 1 (MDH1) is an important enzyme found in the cytoplasm of human cells. It plays a major role in cell metabolism and energy production by helping to convert malate into oxaloacetate and turning NAD+ into NADH . This reaction is reversible. The NADH made is important because it helps move energy from the cytoplasm into the mitochondria where it is used to make ATP, the main energy source for cells (1). MDH1 works by using specific parts called amino acid residues with its active site to carry out this reaction. Amino acid residues like histidine and aspartate help move protons during this process, which makes the reaction faster and more effective (1). When the malate binds to MDH1, the enzyme changes shape to fit better with the molecule. In addition to working with malate, MDH1 can also act on a similar compound called aromatic alpha-keto acids, which have a very similar shape and structure. At first scientists believed that a different enzyme was responsible for this reaction, until research showed that MDH1 can also perform this function too (2).? Small changes in the MDH1?s structure or activity can affect how the cells use energy and nutrients, Because of this MDH1 plays an important role in helping the body maintain homeostasis.?

1.  image of the unmodified site ![Unmodified structure Ser19 (light
    green).](images/Unmodified_S19.png)

2.  image of modification site ![Modified structure SEP19
    (orange).](images/Modified_SEP_3.png)

## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report Three versions of the MDH1 protein were
looked at to see a change, the unmodified version of the protein with a
serine at position 19 (Ser19), a phosphorylated version where a
phosphate group was added to make phosphoserine (SEP19), and a mimic
version where the serine was replaced with aspartic acid (D19). This
type of change is a post-translocational modification, and it can affect
how the protein works or how stable it is. Focusing on where the change
happens in the protein, what part of the protein its near, and what
amino acids it interacts with in each version.?? Ser19 is found in a
flexible loop area near the N-terminus of MDH1. It's not located in the
active site where the chemical reaction happens, but it is close to
where the two halves of the dimers come together. In the modified model,
two SEP19 residues, one from each chain form a hydrogen bond with each
other across the dimer interface. The bond only happens in the
phosphorylated model, not in the unmodified or the mimic model. In the
unmodified protein, Ser19 interacts with Gln14 through a hydrogen bond.
In the mimic, D19 forms a different hydrogen bond with lle15. This
interaction keeps some local bonding but does not have the same bond in
the modified model. In the phosphorylated protein, the phosphate group
allows each chain to bond to each other making the dimer more stable
when together while mimic, D19 does not.

1.  Image of aligned PDB files (no solvent) ![Unmodified (Light green,
    S19), modified (Dark green and orange, SEP19), and mimic (Blue and
    pink, D19) MDH1 models superposed.?](images/3_superposed.png)
    ![Overlay of unmodified (light green), mimic D19 (dark green), and
    modified SEP19 (blue) at active site
    His186.](images/3_Active_site.png)

2.  Image of the site with the aligned PDB files (no solvent) ![Ser19
    site comparison across all three models. Unmodified (light green),
    mimic D19 (dark green), and modified SEP19
    (blue).](images/3_S19.png) ![Ser19 site with all three
    models.](images/Modified_SEP_3.png)

3.  Annotated RMSF plot showing differences between the simulations
    ![RMSF plot for the mimic protein (D19).](images/Mimic_RMSF.png)
    ![RMSF plot for the unmodified.](images/Modified_RMSF.png)

4.  Annotated plots of pKa for the key amino acids ![Boxplot of pKa
    values Arg91, Arg 161, and His 186 in MDH1 from project 3,
    unmodified MDH1.?](images/Boxplot.png)

5.  If needed, show ligand bound images and how modification affects
    substrate binding

Description of the data and changes In the mimic model (D19), aspartic
acid was used to stimulate phosphorylation, which adds a negative
charge. This can affect how the protein folds and interacts with other
residues. The structure remained mostly intact, but when adding this
negative charge, it slightly changed the environment around the active
site. Focusing on three residues: Arg91, Arg161, and His186, which are
important for substrate binding as well as catalysis. Arg 91 and Arg
161, kept high and stable pKa values (averages around 12.3 and 12.9)
which means they are still positively charged and likely to interact
with the negatively charged malate. Arg 161 showed a bit more variation
which could mean the nearby D19 affected it but not enough to change the
role. The active site residue His186, is likely involved in proton
transfer, showed an increase in average pKa in the mimic (from 5.9 in
Project 3 to 7). It also kept a wide pKa range, from around 5.4 to 8.2,
which shows that it remains flexible. This higher pKa suggests that His
186 is now more likely to stay protonated at a neutral pH, which could
impact how it participates in catalysis. This shift could be due to
changes in the electrostatic environment by D19.??To study how the
protein moves we used Boltz Colab to run Root Mean Square Fluctuation
analysis. RMSF helps us see which parts of the protein are the most
flexible during the simulation (3). In our mimic version of MDH1 (D19),
the RMSF graph showed several regions with higher movement. There are
peaks in flexibility around residues 100, 250, 400, and 470, with the
highest fluctuations near residue 100, reaching over 2.3 A. These peaks
likely represent loops or surface regions that allow the protein to
change shape or interact with other molecules. Compared to the
unmodified protein (S19) used in project 2, which had large peaks near
residues 100, 200, and 330, the mimic has shifted flexibility.? While
both proteins show movement near residue 100, the mimic shows additional
fluctuations later in the sequence, around 400. The C-terminal also
shows more movement in the mimic (around 600+ residue), suggesting that
the mimic may affect the stability in that region.?? When looking at the
active site residues we found that the flexibility stayed low in both
unmodified and mimic. This means the active site remains stable.
However, some areas especially 250-260 and 400-410 were more flexible in
the mimic.?? ?

## Comparison of the mimic and the authentic PTM To see how well the D19 mimic copy matches the real phosphorylated version (SEP19) their structures were compared on Mol\* and superposed. Near the active site shows the two models look almost the same, especially around His186. The RMSD between them is 1.46, which means the two structures are very similar in shape. The His186 as previously stated is important with proton transfer during the enzymes job. In both the mimic and phosphorylated, the His186 is in the same place and makes the same hydrogen bonds with three amino acids: Asp 158, Asn185, and Asn133. These hydrogen bonds help keep the active site stable and are shown as the dashed lines. This suggests that D19 is a good structural copy of SEP19 when it comes to looking at shape and bonding at the active site. However, it might not fully show the chemical effects, especially those related to the phosphate groups charge. To support this, an RMSD plot was generated from a Boltz simulation of the D19 variant. The RMSD gradually increases to around 2.5A over the simulation, showing that the structure has some movement but still remains stable overall. There are no sharp spikes present, meaning the fold is preserved. This supports the idea that the mimic stays in a steady shape during movement and is a good stand in for studying how phosphorylation might change the proteins' structure. ?

Part 4 from the Project 4 report outline include images as needed
![Comparison of the mimic (left) and modified
(right).](images/Sidebyside.png) ![Superposed mimic (green and orange)
and modified (blue and pink).](images/2_Superposed.png) ![Superposition
of active site (His186) in the mimic model (green) and modified model
(blue).](images/PTM_activesite.png) ![RMSD plot of mimic
model.](images/rmsd_plot.png)

## Authors

Contributors names Kayla Hosseini

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

-   De Lorenzo, L.; Provost, J.; et al. Essays Biochem. 2024, 68 (2),
    73?82. ![10.1042/EBC20230086](https://doi.org/10.1042/EBC20230086)

-   Friedrich, C. A.; et al. Biochem. Genet. 1987, 25 (9?10), 657?669.
    ![10.1007/BF00556210](https://doi.org/10.1007/BF00556210)
