# Homo sapiens MDH2
# Uniprot ID: P40926
# Variation: Phosphorylation of T19


## Description

1. image of the unmodified site
![Alignment of MDH2 (yellow), MDH2 with phosphorylated threonine 19 (green), and the mimic variant T19D (pink).](images/AF3_align.png)

2. image of modification site
![Modification site alignment within MDH2.](images/modification_site.png)


## Effect of the sequence variant and PTM on MDH dynamics

1. Image of aligned PDB files (no solvent)
![Superposition (RMSD 3.45 Å) of the mimic variant (green) and the unmodified MDH2 (orange) after molecular dynamic simulation.](images/mimicunmodified_align.png)


2. Image of the site with the aligned PDB files (no solvent)
![Modification site of mimic variant T19D (green) and unmodified MDH2 (orange). The variant shows hydrogen bonding between Ser20 and Gln22, as well as between Gln22 and Asn267. However, the unmodified MDH2 only shows hydrogen bonding between Ser18 and Ser20.](images/mimicunmodified_modsite.png)


3. Annotated RMSF plot showing differences between the simulations
![RMSF values for each amino acid in both the variant and unmodified MDH2. The tallest peaks around residues 0-30 and 340-370 indicate the increased flexibility of loop regions. The black line represents the end of one subunit and the beginning of the next subunit of the MDH2 dimer.](images/mimicmodified_RMSFplot.png)

The most significant RMSF spikes are observed in the regions encompassing amino acids 1–24 and 340–370. These fluctuations are expected, as the former corresponds to the transient peptide, which inherently exhibits increased flexibility, while the latter represents the dimer boundary, a region prone to dynamic movement due to inter-subunit interactions. However, the active site remained largely stable, indicating that structural changes were confined to non-catalytic regions. The increased pKa stability in the mimic could influence the protonation state of His200 during catalysis, potentially altering enzymatic efficiency under varying pH conditions.


4. Annotated plots of pKa for the key amino acids
![How the pKa of His200 changes over the course of the MD simulation in both the mimic variant (A) and the unmodified MDH2 (B). The x-axis is the frame number and the y-axis is pKa value.](images/pka_plots_his200.png)

Electrostatic changes were also evident in the mimic variant, particularly at the active site. The pKa of His200, a key catalytic residue, showed greater stability in the mimic variant, maintaining a range of 4.8 to 5 throughout the simulation. In contrast, unmodified MDH2 exhibited broader fluctuations, with pKa values dropping as low as 4.

![Boxplots of the pKa range for amino acids in the binding and active site for both the mimic variant (A) and the unmodified MDH2 (B). The x-axis is the position of the amino acid and the y-axis is the pKa value.](images/pka_boxplots.png)

A similar stabilization pattern was observed for Arg176, with a narrower pKa range in the mimic compared to the unmodified enzyme. 



## Comparison of the mimic and the authentic PTM



![Alignment of the mimic variant T19D (pink) and the phosphorylated T19 (green). The RMSD for the superposition was 3.81 Å.](images/mimicmodified_align.png)

![Modification site alignment of phosphorylated T19 (green) and the mimic variant T19D (pink).](images/mimicmodified_modsite.png)

![Binding site of phosphorylated T19 (green) and the mimic variant T19D (pink) MDH2. No differences between the two models are observed.](images/mimicmodified_bindsite.png)

![Asn142 of the phosphorylated T19 (green) and the mimic variant T19D (pink) MDH2. The PTM-modified enzyme has a hydrogen bond to Val144 whereas the mimic variant does not as shown in the red circle.](images/mimicmodified_asn142.png)

Asn142 is involved in stabilizing NAD+ binding, and the absence of this interaction in the mimic could weaken substrate stabilization, potentially reducing catalytic efficiency.



## Authors

Abby G. Kepley

## Deposition Date

12/6/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

* Acuner Ozbabacan, S. E.; Engin, H. B.; Gursoy, A.; Keskin, O. Transient Protein-Protein Interactions. Protein Engineering Design and Selection 2011, 24 (9), 635–648. ![10.1093](https://doi.org/10.1093/protein/gzr025.)

* Lasham, J.; Djurabekova, A.; Zickermann, V.; Vonck, J.; Sharma, V. Role of Protonation States in the Stability of Molecular Dynamics Simulations of High-Resolution Membrane Protein Structures. J. Phys. Chem. B 2024, 128 (10), 2304–2316. ![10.1021](https://doi.org/10.1021/acs.jpcb.3c07421)
