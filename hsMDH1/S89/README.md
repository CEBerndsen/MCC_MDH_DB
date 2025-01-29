# Human MDH1
# Uniprot ID:P40925
# Variation: phosphorylation of S89


## Description



 MDH1 is an essential enzyme involved in glutamine metabolism, a mechanism that supplies nutrients to rapidly growing and dividing cells; whose overexpression is also linked to a variety of cancers, like breast, pancreatic, as well as prostate cancers.2 The result of this mutation is the establishment of an O-phosphoserine group. Throughout chemistry, phosphorylation is a method to regulate the activity of proteins by changing the stability, dynamics, and chemical interactions present wherever it is added.3 There is existing research on the phosphorylation of different positions in the MDH1 protein, but there is currently no existing literature of this particular position and the subsequent events that may follow. Despite this, existing research can provide useful insight and help to refine predictions and conclusions. Serine 89 is located on an à loop near a Beta sheet consisting of  Val 83 ,ALA 84, ILE  85, and LEU 86. The phosphorylated Ser89 is approximately 18.9Å from the interacting residues in the dimer interface ,which is a substantial distance but not necessarily outside the range of influence. Relative to the active site Ser89 is 12.38Å from the His187, an amino acid located in the active site that plays a key role in ligand binding. In terms of interactions between amino acids at the site of modification, in  the PTM ( the phosphorylated Ser89) there was a hydrogen bond between the O-phosphoserine (shown SEP) and ASN 131 that is observed. A similar interaction was present in the mimic/ variant model (SER89-Asn131) but not in the unmodified MDH model. Outside of these interactions, Ser89 does not make any other interactions with surrounding amino acids.

1. image of the unmodified site
![Image of unmodified site featuring amino acid of interest and weak interactions within 5Å. Due to transient peptides the serine is displayed as Ser88.](images/unmodified_site.png)

2. image of modification site
![Image of Image of unmodified site featuring the phosphorylated serine shown as SEP89.](images/modified_site.png)


![Alignment and superposition of unmodified MDH1(Aqua), phosphorylated MDH1 variant( yellow), and the mimic variant(purple)](images/superimposed.png)

Looking at the protein globally, there were no outstanding differences in structure. Zooming into the modification site, the unmodified MDH1 was shown to participate in no weak interactions, likely in part to the neutral nature of serine at biological pH, even though it's a polar amino acid. The modified PTM model displayed a new hydrogen bond between the phosphorylated serine (SEP89) and the nearby asparagine 131. Likely due in part to the introduction of the negative charge associated with the phosphorylation.

![Layered image of active site in unmodified, phosphorylated, and mimic models. Highlighted in green is a  new H-bond in phosphorylated MDH1 between asparagine 186 and histidine 187.](images/layered_activesite_all.png)


## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report
1. Image of aligned PDB files (no solvent)
![Superimposed  images of mimic structure (gray) and unmodified MDH1(red)](images/unmodified_and_ptm.png)

2. Image of the site with the aligned PDB files (no solvent)
![Image of mimic variant modification site. Amino acid side chains of interest and new H-bonds highlighted in green.](images/nosolvent_mimic_comparison.png)
![Image of phosphorylated MDH1 model. Amino acids of interest highlighted in green.](images/nosolvent_ptm_comparison.png)

The no solvent mimic variant derived from the exhibited multiple changes in H bonding, where the H-bond between Ser89 and Asn131 was no longer observed, and instead an additional bond to Asp88 was seen.

**Comparison of enzyme dynamics 

3.  RMSF plot showing simulation differences
![Root means square fluctuation (RMSF) graph for the mimic (red) and MDH1(blue).](images/rmsf_mimic_and_ptm.png)

The root means square fluctuation plot serves to show how much each amino acid moves during the simulation. In this plot, both data sets exhibit relatively low RMSF values (lower than 1.5Å), where the peaks likely indicate certain regions of higher flexibility like loops.

4. RMSD plot showing simulation differences
![RMSD plot of MDH1 mimic showing whether the protein has reached a fixed state.](images/rmsd.png)



5. Pka plots for key amino acids 
![Comparison of pKa between unmodified MDH1 and mimic at His187](images/pKa_traj_git.png)


## Comparison of the mimic and the authentic PTM
![Image showing differences in His 187 orientation between mimic (gray) and phosphorylated MDH1 (orange)](images/activesite_mimic_and_ptmp4.png)

The His187 in the active site showed a distinct difference in it's orientation likely as a result of differences in stabilizing H-bonds.


## Authors

Mason Leslie 

## Deposition Date
12/7/2024
## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

* The UniProt Consortium. UniProt: The Universal Protein Knowledgebase in 2023. Nucleic Acids Res. 2023, 51 (D1), D523–D531![10.1093/nar/gkac1052](https://doi.org/10.1093/nar/gkac1052.)

* Parente, A. D.; Bolland, D. E.; Huisinga, K. L.; Provost, J. J. Physiology of Malate Dehydrogenase and How Dysregulation Leads to Disease. Essays Biochem. 2024, 68 (2), 121–134. ![10.1042/EBC20230085.
](https://doi.org/10.1042/EBC20230085.)

* 	Nishi, H.; Shaytan, A.; Panchenko, A. R. Physicochemical Mechanisms of Protein Regulation by Phosphorylation. Front. Genet. 2014, 5, 270.![10.3389/fgene.2014.00270.
](https://doi.org/10.3389/fgene.2014.00270.)

* Karplus, M.; McCammon, J. A. Molecular Dynamics Simulations of Biomolecules. Nat. Struct. Biol. 2002, 9 (9), 646–652 ![10.1038/nsb0902-646.
]( https://doi.org/10.1038/nsb0902-646.)

