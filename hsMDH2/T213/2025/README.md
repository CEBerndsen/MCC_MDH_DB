# human mitochondrial malate dehydrogenase 2

# P40926

# IPLISQCTPKVDFPQ

## Description

# Part 1 from Project 4 report outline (with citations as appropriate)

1.  image of the unmodified site ![Unmodified MDH2 active site showing native hydrogen bonding network (Arg-80, Arg-86, His-176, Ser-222).](images/unmodified_active_site.png)

2.  image of modification site ![Modified MDH2 active site showing formation of ionic bridges by Asp-87 and Asp-88.](images/modified_active_site.png)

## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report

1.  Image of aligned PDB files (no solvent) ![Superposition of four MDH2 structures highlighting global and local structural differences. Structures include the unmodified (control), AF3 mimic, AF3 modified, and Boltzmann-weighted mimic variants. The alignment was performed using Mol\*, yielding a root mean square fluctuation (RMSF) of 1.54 Å. The conserved core architecture reflects general structural stability, while localized differences, particularly in loop regions and the C-terminal extension, suggest changes in flexibility and potential electrochemical remodeling near the active site.](images/superposition.png)

2.  Image of the site with the aligned PDB files (no solvent) ![Structures are color-coded: unmodified, mimic (T213D), and modified (pT213). Local shifts in Arg-80, Arg-86, and loop backbone position reflect structural consequences of post-translational modification.](images/site_aligned_pdb_files.png)

3.  Annotated RMSF plot showing differences between the simulations ![RMSF profile of Cα atoms in modified hMDH2 over the simulation. Compared to the unmodified form, backbone flexibility is reduced, with lower RMSF values overall. Peaks remain at loop regions, but suppressed fluctuations reflect added ionic interactions and active site compaction.](images/RMSF_modified.png) ![RMSF profile of Cα atoms in unmodified hMDH2 over the simulation. Most residues fluctuate between 0.5–1.0 Å, indicating structural stability. Peaks near residues \~100, \~200, \~300, and \~400 reflect flexible loops or termini. Low RMSF near active site residues suggests a stable catalytic environment.](images/RMSF_unmodified.png) ![Root mean square deviation (RMSD) of the Cα backbone atoms for unmodified human mitochondrial malate dehydrogenase 2 (hMDH2) over the course of the simulation. The RMSD quickly rises and then stabilizes around \~1.0 Å, indicating that the unmodified structure achieves equilibrium and maintains a stable global conformation throughout the simulation timeframe.](images/RMSD_unmodified.png) ![Root mean square deviation (RMSD) of the Cα backbone atoms for modified human mitochondrial malate dehydrogenase 2 (hMDH2) over the course of the simulation. The RMSD displays slightly greater fluctuations compared to the unmodified structure, particularly early in the trajectory, suggesting initial conformational](images/RMSD_modified.png)

4.  Annotated plots of pKa for the key amino acids ![Time-dependent pKa values of His-176 in unmodified hMDH2. This scatter plot shows the pKa trajectory of His-176 over a 200-second molecular dynamics simulation. The pKa remains relatively stable, with minor fluctuations around a mean of 4.64 (standard deviation = 0.52), suggesting a consistent electrostatic environment conducive to proton transfer.](images/his176_pKa_unmodified.png) ![Time-dependent pKa values of His-176 in the modified hMDH2 variant. This plot depicts the pKa fluctuations of His-176 across a 100-second trajectory in the modified enzyme. A notable increase in variability and upward shifts in pKa values are observed after \~70 seconds, indicating electrostatic instability and reduced environmental constraint around the residue.](images/his176_pKa_modified.png) ![Boxplot comparison of pKa values for Arg-80, Arg-86, and His-176 in mitochondrial malate dehydrogenase 2 (hMDH2). His-176 displays lower and more variable pKa values relative to Arg-80 and Arg-86, indicating greater electrochemical instability at the active site in the mimic and modified variants.](images/boxplot_comparison.png) ![Active site environment of His-176 in the modified mitochondrial malate dehydrogenase 2 (hMDH2) structure. Alterations in hydrogen bonding with neighboring residues such as Asp-149 and Ala-177 are observed, potentially contributing to electrochemical instability and disrupted proton transfer.](images/his176_modified.png)

5.  If needed, show ligand bound images and how modification affects substrate binding

Description of the data and changes This dataset includes structural and simulation data comparing unmodified human mitochondrial MDH2 with two modified forms at residue T213: a phosphomimetic variant (T213D) and a model containing an authentic phosphorylation (pT213). Structural models were generated using AlphaFold3 (for unmodified and PTM) and Boltz-1 (for the mimic), then subjected to molecular dynamics simulations via MD Colab. Analyses include RMSD, RMSF, and pKa trajectories to assess changes in flexibility, stability, and electrostatic properties. Key structural differences were identified in the loop containing T213, including altered hydrogen bonding networks, reduced backbone flexibility in the modified variant, and rearranged side chains at the active site. The authentic PTM introduced stronger ionic interactions and greater electrostatic shifts than the mimic, particularly around Arg-80, Arg-86, and Ser-222. Additionally, pKa analysis of His-176 revealed greater variability in the modified structure, indicating potential disruption of catalytic function. These changes were visualized through aligned structure overlays and plotted outputs, providing evidence that while the T213D mimic captures some charge-based effects, it does not fully replicate the spatial or electrochemical impact of true phosphorylation. This analysis also considers how these modifications may affect MDH2’s role in the citric acid cycle.

## Comparison of the mimic and the authentic PTM

Part 4 from the Project 4 report outline include images as needed

![Active site of hMDH2 phosphomimic (T213D) model. Close-up view of the active site from the Boltz-modeled phosphomimetic MDH2 variant, where threonine 213 is substituted with aspartate (D213). Neighboring residues, including LYS217, VAL214, and GLY212, are visualized to assess side chain orientation and potential hydrogen bonding. Dotted lines represent predicted non-covalent interactions. The local environment shows moderate disruption, indicating partial mimicry of the authentic phosphorylated residue.](images/mimic_ptm.png) ![Active site of hMDH2 with authentic PTM (pT213). Active site view from the AlphaFold3 model containing the authentic post-translational modification at threonine 213. Interactions with nearby residues such as GLU212, LYS217, and THR211 are shown, with dotted lines indicating hydrogen bonding or electrostatic interactions. The phosphorylated residue introduces a distinct charge distribution, which may affect stability and interactions differently than the mimic model.](images/authentic_ptm.png)


## Authors

Skylar Floyd

## 5/7/25

## License

Shield: [![CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

-   Citation1 ![10.2210/pdb2dfd/pdb](https://doi.org/10.2210/pdb2dfd/pdb)

-   Citation2 ![10.1042/BST0370627](https://doi.org/10.1042/BST0370627)

-   Citation3 ![10.1074/jbc.RA119.012345](https://doi.org/10.1074/jbc.RA119.012345)

-   Citation4 ![10.1101/2021.10.04.463034](https://doi.org/10.1101/2021.10.04.463034)

-   Citation5 ![10.1101/2024.11.19.624167](https://doi.org/10.1101/2024.11.19.624167)

-   Citation6 ![10.1371/journal.pcbi.1005659](https://doi.org/10.1371/journal.pcbi.1005659)

-   Citation7 ![10.1021/ct200133y](https://doi.org/10.1021/ct200133y)

-   Citation8 ![10.1093/nar/gkab314](https://doi.org/10.1093/nar/gkab314)
